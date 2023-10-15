# Hands On Wireshark

|        Nama           | NRP|      Kelas       |
| ---                   |--- |--- |
|Gracetriana Survinta Septinaputri | 5025211199 | Jarkom D |

## Wireshark TCP
### No 1
![no 1 2 tcp](https://github.com/gracetrianaa/handson-jarkom/assets/90684914/8810bec5-5fbf-4e32-bfe0-c639a8ac78cb)
IP Address : 192.168.86.68
Port : 55639
### No 2
![no 1 2 tcp](https://github.com/gracetrianaa/handson-jarkom/assets/90684914/aae64b7b-767f-4621-8dda-cc4920be8635)
IP Address : 128.119.245.12
### No 3
![soal 3 tcp](https://github.com/gracetrianaa/handson-jarkom/assets/90684914/3185ccfb-b7fc-4152-98da-20c4999ec39c)
Sequence number (raw) TCP SYN : 4236649187
### No 4
![soal 4 tcp](https://github.com/gracetrianaa/handson-jarkom/assets/90684914/477691b9-b8d3-43d3-983e-c1b3b54db898)
Sequence number (raw) TCP SYNACK : 1068969752
Acknowledgment number : 4236649188
### No 5
![soal 5 tcp](https://github.com/gracetrianaa/handson-jarkom/assets/90684914/c2e471e9-2a9c-4be1-9b4c-e5948f16c988)
Sequence number : 4236649188
TCP payload : 1448 bytes
### No 7
length is 1514
### No 10
![soal 10 tcp](https://github.com/gracetrianaa/handson-jarkom/assets/90684914/c78cccaf-ddc0-40c0-bfbc-2f837b252756)
Receiver typically acknowledge 1448 bytes

## Wireshark UDP
### No 1
![soal 1 udp](https://github.com/gracetrianaa/handson-jarkom/assets/90684914/2d43d32c-1b60-4981-81e1-f5d56ce66d70)
Packet number : 17
Port : 57621 (UDP)
There are 4 fields in UDP header : source port, destination port, length, checksum
### No 2
![soal 2 udp](https://github.com/gracetrianaa/handson-jarkom/assets/90684914/85fa2ecc-0edc-4bf1-9bdc-8a2ad7740cfe)
UDP header memiliki panjang tetap yaitu 8 bytes. Masing-masing dari 4 fields UDP header memiliki length 2 bytes.
### No 3
![soal 3 udp](https://github.com/gracetrianaa/handson-jarkom/assets/90684914/77ad3506-232e-437a-b830-e1443a5c6b9a)
Length field memiliki value dari header + data. Explicit length value dibutuhkan karena ukuran field data dapat berbeda dari sebuah UDP segment dengan UDP segment setelahnya.
Length UDP payload pada packet ini adalah 52 bytes - 8 bytes = 44 bytes.
### No 4
Maksimum nilai pada UDP payload adalah (2^16 – 1) bytes plus header bytes sehingga 65535 bytes – 8 bytes = 65527 bytes.
### No 5
Ukuran terbesar yang mungkin dari source port number adalah (2^16 – 1) = 65535. 


