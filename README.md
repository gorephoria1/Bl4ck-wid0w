this is currently in beta and could have bugs
Bl4ck-wid0w <img width="1920" height="1031" alt="idk" src="https://github.com/user-attachments/assets/9d5b48db-5c63-4a63-b224-54b1e3db293c" />
Bl4ck-wid0w is a fork of cyberdoor on github so it has the same features but 1 new thing a tribute to something.........
anyways to install Bl4ck-wid0w heres instructions 
step 1 git clone 
```bash
git clone https://github.com/gorephoria1/Bl4ck-wid0w.git
```
step 2 chmod the bl4ck-wid0w.sh file
```bash
chmod +x bl4ck-wid0w.sh
```
step 3 install the dependencys 
```bash
/linuxmint/ubuntu/debian/kali/parrot
sudo apt install tor postgresql
arch/manjaro/artix/endevouros/blackarch
sudo pacman -S tor postgresql
fedora/
sudo dnf install tor postgresql
```
step 4 enable them
```bash
systemd based systems
sudo systemctl enable tor
sudo systemctl enable postgresql
openrc based systems
sudo rc-update add tor default
sudo -u postgres initdb --locale=en_US.UTF-8 -E UTF-8 -D /var/lib/postgres/data
```
step 5 run the bl4ck-wid0w.sh file
```bash
./bl4ck-wid0w.sh
```
