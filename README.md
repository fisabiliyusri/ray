# Command
0. Ketik
sudo su && cd

1. Update Dulu 
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
1*. Update Dulu
apt-get update && apt-get upgrade && update-grub
1**. reboot

2. Install Semua VPN Batch 

sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/fisabiliyusri/ray/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh

Atau

2. Install Semua VPN Batch 

wget https://raw.githubusercontent.com/fisabiliyusri/ray/main/setup.sh && chmod +x setup.sh && screen -S setup.sh ./setup.sh


3. Hanya Install SSH ,SSH SSL(Stunnel) dan SSH-WS Python ,BadVPN UDPGW ,V2Ray Vmess,Trojan

sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/fisabiliyusri/ray/main/install/sshonly.sh && chmod +x sshonly.sh && sed -i -e 's/\r$//' sshonly.sh && screen -S sshonly ./sshonly.sh


3. SSH WS STUNNEL(SSL) ,BADVPN ,V2RAY VMESS TROJAN

wget https://raw.githubusercontent.com/fisabiliyusri/ray/main/install/sshonly.sh
&& chmod +x sshonly.sh && screen -S sshonly.sh ./sshonly.sh
