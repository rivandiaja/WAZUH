Spesifikasi yang dibutuhkan untuk instalasi wazuh yaitu :
  - RAM 16 
  - core 8

Download ubuntu server
'''
https://ubuntu.com/download/server/thank-you?version=24.04.2&architecture=amd64&lts=true
'''

Buat 2 ubuntu server di vm,
  1. Wazuh-Manager
    - RAM 4 (3 jika total RAM kurang dari 16 GB)
    - ROM 20
    - core 4 atau 3 tergantung spek
    seting network NAT dan add port forwarding host port 2222 guest port 22
  2. Wazuh-Agent
    - RAM 4 (3 jika total RAM kurang dari 16 GB)
    - ROM 20
    - core 4 atau 3 tergantung spek
    seting network NAT dan add port forwarding host port 2223 guest port 22 dan port 443 guest port 443

Update & Upgrade sebelum instalasi wazuh
'''
sudo apt update
sudo apt upgrade
'''
remote vm menggunakan 'ssh'
install ssh di masing-masing vm
'''
apt install openssh-server
systemctl status ssh
systemctl enable ssh
'''

Buka command prompt untuk me-remote Wazuh-Manager danWazuh-Agent
'''
ssh Wazuh-Manager@<ip address> -p 2222 (untuk manager)
ssh Wazuh-Manager@<ip address> -p 2223 (untuk agent)
'''
