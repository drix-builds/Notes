- set SSH with: ```
  git remote set-url origin git@github.com:drix-builds/Notes.git```
- ssh server kitty
	- kitty +kitten ssh drix@192.168.1.222   
    - https://technoyard.com/2025/07/25/the-step-by-step-guide-to-nginx-proxy-manager-with-cloudflare-ssl-perfect-for-your-homelab/
    - att router access code /6?&0*%4/?
- update cachyos mirrors
	- sudo pacman -Sy --needed archlinux-keyring cachyos-keyring
sudo pacman -Syu

### minecraft chunk edit
~/Desktop/j/zulu21.32.17-ca-fx-jre21.0.2-linux_x64/bin
sudo dd if=/home/drix/Downloads/archlinux-2026.02.01-x86_64.iso of=/dev/sdc1 bs=4M status=progress oflag=sync

java -Xms1024M -Xmx10240M @libraries/net/neoforged/neoforge/21.1.215/unix_args.txt nogui


sudo dd if=/home/drix/Downloads/zimaos-x86_64-1.5.4_installer.img of=/dev/sdX bs=4M status=progress && sync     

