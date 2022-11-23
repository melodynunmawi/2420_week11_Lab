# 2420_week11_Lab

## Create droplet in degital ocean  and connect in Window Terminal

   First need to create SSH key in terminal  $ ssh-keygen -t ed25519 -C "example@gmail.com"
   Second put the desire file where your prefer location
   Third Login with ssh -i ~/.ssh/ed25519 root@ip_address
   create username and password ans sync to connect root@ip_address
   > useradd -ms /bin/bash  name
   > sudo passwd serverone
   > sudo usermod -aG sudo serverone
   > rsync --archive --chown=serverone:serverone ~/.ssh /home/serverone

### check the SSH list
    cd .ssh
    cat id_ed25519.pub
    sudo vim authorized_keys

#### ssh -i ~/.ssh/id_ed25519 back@24.199.91.198
     rsync -aPv /home/one/testDir/ back@24.199.91.198:~/
      /home/one/test/
      
     rsync -aPv /home/serverone/testDir/ back@24.199.91.198:~/
     sudo cp backup/script /opt/backup
     sudo cp backup/backu.* /etc/systemd.system/
     sudo chmod +x /opt/backup/backup.script
     sudo vim /etc/systemd/system.backup.service
     sudo systemctl deamon-reload
     sudo systemctl start backup.service

      sudo cp week11/gtwtr /opt/gtwtr
      sudo cp week11/gtwtr.service /etc/systemd/system
      sudo cp week11/gtwtr.timer /etc/systemd/system
      [6:33 PM]
      sudo systemctl start gtwtr.service
      sudo systemctl start gtwtr.timer

      rsync -aPv /home/one/testDir/ back@24.199.91.198:~/backup
      backup.timer
      sudo cp backup /opt/backup
      sudo cp backup.service /etc/systemd/system
      sudo cp backup.timer /etc/systemd/system
      sudo systemctl start backup.service
      sudo vim /etc/systemd/system/backup.service
      mkdir testDir
      vim test1
      rsync -aPv /home/one/testDir/ back@24.199.91.198:~/backup

      /etc/systemd/system
      sudo vim /opt/backup/backup
