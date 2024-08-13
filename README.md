# Installation Steps
### (1) Clone The repository
git clone https://github.com/ugoMusk/wsl-ubuntu20.04_w_py39_preinstalled_dist
### (2) Change directory to the root of the repository
cd wsl-ubuntu20.04_w_py39_preinstalled_dist 
### (3) Steps to Import the tar file into WSL
Use the command: wsl --import <distro_name_of_choice> <InstallLocation> <path_of_tar_file>

example: wsl --import ugoMusk-Ubuntu20.04 '/c/Users/Admin/AppData/Local/Packages' Ubuntu-20.04_by_ugoMusk_dev.tar

Use the command wsl -l -v to check distributions installed.