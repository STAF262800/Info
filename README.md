Installing the Nibiru Node


Minimum Hardware Requirements 

4\8\100 

sudo apt update
sudo apt install -y curl git jq lz4 build-essential unzip

if [ ! -f "/usr/local/go/bin/go" ]; then

  bash <(curl -s "https://raw.githubusercontent.com/nodejumper-org/cosmos-scripts/master/utils/go_install.sh")
  
  source .bash_profile
  
fi

