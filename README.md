pkg update && pkg upgrade -y
pkg install python unzip -y
termux-setup-storage
cd ~/storage/downloads
unzip TECHHVEN_WEB_SECURITY.zip
cd TECHHVEN_WEB_SECURITY
chmod +x start.sh
./start.sh
