# a_play_on_yocto
repo for exploring the yocto build system and kas configuration management
## Usage

To use this project, run the following commands in your terminal:

```bash
# Clone the repository
git clone https://github.com/deondavis/a_play_on_yocto.git

# Navigate into the project directory
cd a_play_on_yocto

# Run the script to setup environment
kas shell kas-config/work/<required platform yml>

#Run the menuconfig 
kas menu kas-config/kconfig/<required kconfig file>

```
