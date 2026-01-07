# 1. install ini duku jing
pkg update
pkg upgrade
termux-setup-storage

# 2. Install packages dasar
pkg install -y git python python3 nodejs curl wget openssl termux-api
pkg install -y jq mpv figlet toilet neofetch cowsay ruby
pip install requests pycryptodome
gem install lolcat

# kalo error coba install ini
pkg install -y python-pip
pip install --upgrade pip

# 1. kalo udah langsung aja
cd $HOME
git clone https://github.com/shadownex/shadownex-tools.git
cd shadownex-tools
bash Jembot.sh


![CONTOH KALO UDAH DI RUN](https://d.uguu.se/ioFzZjuR.jpg)
