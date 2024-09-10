# create an HTML email

To send the email use putsemail.com

## install command line tools

```bash
sudo apt install mailutils        #[On Debian, Ubuntu and Mint]
sudo yum install mailx            #[On RHEL/CentOS/Fedora and Rocky Linux/AlmaLinux]
sudo emerge -a mail-client/mailx  #[On Gentoo Linux]
sudo pacman -S mailutils          #[On Arch Linux]
sudo zypper install mailutils     #[On OpenSUSE]  
```

# Notes
```
# image
URL?raw=true
https://github.com/christianbueno1/myservices-html-email/blob/main/cb-terminal-logo.png?raw=true

```

# Deploy
```
/var/www/estudiamosec.com/public_html

# updates
rsync =avz --update ./* server:/var/www/estudiamosec.com/public_html
# copy
scp -rp ./index.html server:/var/www/estudiamosec.com/public_html
```
