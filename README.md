# Sound Event Detection with YAMNet on Jetson Nano

## Prepare your Jetson Nano
1. [Write Image to the microSD Card](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#write)
2. [Setup and First Boot](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#setup)

## Install Dependencies
1. SSH in your Jetson Nano
2. Clone this repo  
`git clone https://github.com/x1001000/sed-yamnet-jetson-nano`
3. Run the script  
`bash sed-yamnet-jetson-nano/install-deps.sh`
4. Reboot your Jetson Nano

## Run Inference
1. SSH in your Jetson Nano
2. Run the script  
`python3 sed.py`
