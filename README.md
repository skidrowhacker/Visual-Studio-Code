# Visual-Studio-Code
# installtion on Linux OS
# Write below commands in termanl 
# First
sudo apt update
sudo apt install curl gpg gnupg2 software-properties-common apt-transport-https
# 2ND
curl https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > microsoft.gpg
sudo install -o root -g root -m 644 microsoft.gpg /etc/apt/trusted.gpg.d/
# 3D 
echo "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main" | sudo tee /etc/apt/sources.list.d/vscode.list
# 4th
sudo apt update && sudo apt install code -y

# You Will Find  Visual-Studio-Code in the list of apps installed on Linux OS

# Have Fun
