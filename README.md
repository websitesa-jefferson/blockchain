# Instalar Anaconda no linux
sudo apt update && sudo apt upgrade

sudo apt install libgl1-mesa-glx libegl1-mesa libxrandr2 libxrandr2 libxss1 libxcursor1 libxcomposite1 libasound2 libxi6 libxtst6

# Download ultima versão do Anaconda
https://www.anaconda.com/products/individual

sudo chmod +x Anaconda3-2021.05-Linux-x86_64.sh
sha256sum Anaconda3-2020.11-Linux-x86_64.sh
./Anaconda3-2021.05-Linux-x86_64.sh
conda list
conda init
source ~/.bashrc
conda search "^python$"
anaconda-navigator
pip install Flask==0.12.2
pip install requests==2.18.4

