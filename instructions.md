## Instructions for MacOS

# 0. Open Terminal (Launchpad -> Terminal)

# 1. Install HomeBrew

/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

# 2. Install Python3

brew install python3

# 3. Clone GitHub Repo (https://github.com/kangaroo96/osbp_detect)

cd ~/Documents/
git clone https://github.com/kangaroo96/osbp_detect.git

# 4. Install depencies and run

cd ~/Documents/osbp_detect/
pip3 install -r requirements.txt 
python3 gui.py
