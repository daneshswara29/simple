
  
# Diperlukan
<br>
- DOMAIN (WAJIB)/RANDOM dari Script<br>
- NOTE domain dari script hanya dilakukan 1x saat proses install untuk mengurangi spam DOMAIN yang sering gonta ganti<br>
- Untuk mengubah Domain di menu setelah install menggunakan domain sendiri bukan dari script lagi OK<br>
- DEBIAN 9/10<br>
- Ubuntu 18/20 LTS<br>
- CPU MIN 1 CORE<br>
- RAM 1GB<br>
- Rekomendasi Ubuntu 18 
<br>

<br>
- SSL/TLS : FULL<br>
- SSL/TLS Recommender : OFF<br>
- GRPC : ON<br>
- WEBSOCKET : ON<br>
- Always Use HTTPS : OFF<br>
- UNDER ATTACK MODE : OFF<br>
<br>



## Service & Port:
<br>
- SSH Websocket : 80<br>
- SSH SSL Websocket : 443<br>
- Stunnel4 : 222,777<br>
- Vmess WS TLS : 443<br>
- Vless WS TLS : 443<br>
- Trojan WS TLS : 443<br>
- Shadowsocks WS TLS : 443<br>
- Vmess WS none TLS : 80<br>
- Vless WS none TLS : 80<br>
- Trojan WS none TLS : 80<br>
- Shadowsocks WS none TLS : 80<br>
- Vmess gRPC : 443<br>
- Vless gRPC : 443<br>
- Trojan gRPC : 443<br>
- Shadowsocks gRPC : 443<br>
<br>
  
## Fitur
- Speedtest VPS by [Ookla](https://speedtest.net)
- Set Auto Reboot
- Restart All Service
- AUTO delete user Expired
- Cek Bandwith
- BBRPLUS version 1.4.0 by [Chikage0o0](https://github.com/Chikage0o0/Linux-NetSpeed/blob/master/tcp.sh)
- DNS CHANGER
- DLL
- auto backup tidak ada ? ya... dihilangkan permanent
  




# PERHATIAN perlu masuk sebagai root
- Step 1
```
sudo su
```
- Step 2
```
cd
```
- Step 3 INSTALL, NOTE jika sudah root langsung COPAS link dibawah ini saja ya
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/daneshswara29/simple/main/setup.sh && chmod +x setup.sh && ./setup.sh
```

# Buat root di VPS bagi kamu yang login ke server masih menggunakan username yang bukan root
- Step 1
```
sudo su
```
- Step 2
```
cd
```
- Step 3
```
apt update && apt install wget -y && wget -qO- -O rootvps.sh https://raw.githubusercontent.com/givpn/rootvps/master/rootvps.sh && bash rootvps.sh
  
```

