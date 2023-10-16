# Hands-On TCP UDP
Sandhika Surya / 5025211022
## TCP
### 1
![alt text](https://github.com/Sandhika21/Jarkom/blob/main/hands-on/1.png)
IP address: 192.168.0.4	

Port: 65230
### 2
![alt text](https://github.com/Sandhika21/Jarkom/blob/main/hands-on/1.png)
IP address: 128.119.245.12

Port: 80
### 3
![alt text](https://github.com/Sandhika21/Jarkom/blob/main/hands-on/3.png)
Sequence number (raw): 1560633208
### 4
![alt text](https://github.com/Sandhika21/Jarkom/blob/main/hands-on/4.png)
Sequence number (raw): 2962726575

Acknowledgment number (raw): 1560633209
### 5
![alt text](https://github.com/Sandhika21/Jarkom/blob/main/hands-on/5.png)
Sequence Number (raw): 1560784989

TCP payload: 1258 bytes
### 7
![alt text](https://github.com/Sandhika21/Jarkom/blob/main/hands-on/7.png)
TCP payload: 1460 bytes

Header Length: 20 bytes 

Length: 1480 bytes

## UDP
### 1
![alt_text](https://github.com/Sandhika21/Jarkom/blob/main/hands-on/udp/1.png)
Packet number: 73

Port: 443

Dengan panjang header UDP adalah 8 byte. 4 field pada header UDP: Source Port, Destination Port, Length, Checksum

### 2
![alt_text](https://github.com/Sandhika21/Jarkom/blob/main/hands-on/udp/2a.png)
![alt_text](https://github.com/Sandhika21/Jarkom/blob/main/hands-on/udp/2b.png)
![alt_text](https://github.com/Sandhika21/Jarkom/blob/main/hands-on/udp/2c.png)
![alt_text](https://github.com/Sandhika21/Jarkom/blob/main/hands-on/udp/2d.png)
Length masing-masing header UDP adalah 2 byte

### 3
![alt_text](https://github.com/Sandhika21/Jarkom/blob/main/hands-on/udp/2b.png)
Field length pada header didapat dari UDP payload dan length dari header

Length: 49

UDP payload: 41 bytes

Length dari header: 8 bytes

### 4
Terdapat (2^16 - 1) dikurangi 8 bytes dari header sehingga menjadi 65535 - 8 = 65527 bytes

### 5
Ukuran terbesar dari source port number adalah (2^16 - 1) yaitu 65535 bytes

### 6
![alt_text](https://github.com/Sandhika21/Jarkom/blob/main/hands-on/udp/6.png)
Protocol number untuk UDP adalah 17

### 7
![alt_text](https://github.com/Sandhika21/Jarkom/blob/main/hands-on/udp/6.png)
Packet UDP nomor 73 memiliki source port 51108 dan destination port 443
Packet UDP nomor 74 yang merupakan reply memiliki source port 443 dan destination port 51108
Source port udp pertama merupakan destinantion port dari udp reply dan sebaliknya


