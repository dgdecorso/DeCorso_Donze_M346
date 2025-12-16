<img width="2581" height="678" alt="image" src="https://github.com/user-attachments/assets/9ce9b66f-d467-4fce-8de4-a9e4c9477c41" />


<img width="1712" height="1026" alt="image" src="https://github.com/user-attachments/assets/e160d777-a979-41f5-99d0-6f31be203f77" />
<img width="1695" height="254" alt="image" src="https://github.com/user-attachments/assets/1f6a047f-6551-45fc-8044-d94b20264677" />


ubuntu@ip-172-31-31-118:~$ sudo sed -n '1,120p' /var/log/cloud-init-output.log
Cloud-init v. 25.2-0ubuntu1~24.04.1 running 'init-local' at Tue, 16 Dec 2025 08:40:58 +0000. Up 6.81 seconds.
Cloud-init v. 25.2-0ubuntu1~24.04.1 running 'init' at Tue, 16 Dec 2025 08:41:03 +0000. Up 10.96 seconds.
ci-info: ++++++++++++++++++++++++++++++++++++++Net device info+++++++++++++++++++++++++++++++++++++++
ci-info: +--------+------+-----------------------------+---------------+--------+-------------------+
ci-info: | Device |  Up  |           Address           |      Mask     | Scope  |     Hw-Address    |
ci-info: +--------+------+-----------------------------+---------------+--------+-------------------+
ci-info: |  ens5  | True |        172.31.31.118        | 255.255.240.0 | global | 0a:ff:e6:d6:27:d3 |
ci-info: |  ens5  | True | fe80::8ff:e6ff:fed6:27d3/64 |       .       |  link  | 0a:ff:e6:d6:27:d3 |
ci-info: |   lo   | True |          127.0.0.1          |   255.0.0.0   |  host  |         .         |
ci-info: |   lo   | True |           ::1/128           |       .       |  host  |         .         |
ci-info: +--------+------+-----------------------------+---------------+--------+-------------------+
ci-info: ++++++++++++++++++++++++++++++Route IPv4 info++++++++++++++++++++++++++++++
ci-info: +-------+-------------+-------------+-----------------+-----------+-------+
ci-info: | Route | Destination |   Gateway   |     Genmask     | Interface | Flags |
ci-info: +-------+-------------+-------------+-----------------+-----------+-------+
ci-info: |   0   |   0.0.0.0   | 172.31.16.1 |     0.0.0.0     |    ens5   |   UG  |
ci-info: |   1   |  172.31.0.2 | 172.31.16.1 | 255.255.255.255 |    ens5   |  UGH  |
ci-info: |   2   | 172.31.16.0 |   0.0.0.0   |  255.255.240.0  |    ens5   |   U   |
ci-info: |   3   | 172.31.16.1 |   0.0.0.0   | 255.255.255.255 |    ens5   |   UH  |
ci-info: +-------+-------------+-------------+-----------------+-----------+-------+
ci-info: +++++++++++++++++++Route IPv6 info+++++++++++++++++++
ci-info: +-------+-------------+---------+-----------+-------+
ci-info: | Route | Destination | Gateway | Interface | Flags |
ci-info: +-------+-------------+---------+-----------+-------+
ci-info: |   0   |  fe80::/64  |    ::   |    ens5   |   U   |
ci-info: |   2   |    local    |    ::   |    ens5   |   U   |
ci-info: |   3   |  multicast  |    ::   |    ens5   |   U   |
ci-info: +-------+-------------+---------+-----------+-------+
Generating public/private rsa key pair.
Your identification has been saved in /etc/ssh/ssh_host_rsa_key
Your public key has been saved in /etc/ssh/ssh_host_rsa_key.pub
The key fingerprint is:
SHA256:aJrhWsEkEcboSbjCTNz6c8lH7crdvzck+r3hXACSx9Y root@ip-172-31-31-118
The key's randomart image is:
+---[RSA 3072]----+
|oo=.             |
|o=.o       o .   |
|*.+ .   . o = E  |
|o* +   o . + .   |
|. . = = S     .  |
|   + X . .   . o |
|    B o o . . o..|
|   o   o . o  +oo|
|  .         o+o=o|
+----[SHA256]-----+
Generating public/private ecdsa key pair.
Your identification has been saved in /etc/ssh/ssh_host_ecdsa_key
Your public key has been saved in /etc/ssh/ssh_host_ecdsa_key.pub
The key fingerprint is:
SHA256:A7/zjWOUr8GX+/y6fxGKiRTeR39xZwMnbXG/sSUJqe0 root@ip-172-31-31-118
The key's randomart image is:
+---[ECDSA 256]---+
|            .+ooo|
|         .  .oo**|
|      . . oo. =oB|
|       o o.... +*|
|        S .o+ .oo|
|         =ooEo . |
|        o.o.o   .|
|         oo=.o  .|
|         .+oo.==+|
+----[SHA256]-----+
Generating public/private ed25519 key pair.
Your identification has been saved in /etc/ssh/ssh_host_ed25519_key
Your public key has been saved in /etc/ssh/ssh_host_ed25519_key.pub
The key fingerprint is:
SHA256:/dvUttdCR1RxUvdSJ/4JpSC5GmefyhSdP379L7DebSI root@ip-172-31-31-118
The key's randomart image is:
+--[ED25519 256]--+
|         ...  o+X|
|         .. ..o+*|
|          o .oo..|
|       . * o  .oo|
|        S + o  o.|
|       . . +.o...|
|        o . o+o.=|
|         o  E*++*|
|           .o.+*B|
+----[SHA256]-----+
Cloud-init v. 25.2-0ubuntu1~24.04.1 running 'modules:config' at Tue, 16 Dec 2025 08:41:05 +0000. Up 13.86 seconds.
Cloud-init v. 25.2-0ubuntu1~24.04.1 running 'modules:final' at Tue, 16 Dec 2025 08:41:08 +0000. Up 16.76 seconds.
Hit:1 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble InRelease
Get:2 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-updates InRelease [126 kB]
Get:3 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-backports InRelease [126 kB]
Get:4 http://security.ubuntu.com/ubuntu noble-security InRelease [126 kB]
Get:5 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble/universe amd64 Packages [15.0 MB]
Get:6 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble/universe Translation-en [5982 kB]
Get:7 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble/universe amd64 Components [3871 kB]
Get:8 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble/universe amd64 c-n-f Metadata [301 kB]
Get:9 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble/multiverse amd64 Packages [269 kB]
Get:10 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble/multiverse Translation-en [118 kB]
Get:11 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble/multiverse amd64 Components [35.0 kB]
Get:12 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble/multiverse amd64 c-n-f Metadata [8328 B]
Get:13 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-updates/main amd64 Packages [1679 kB]
Get:14 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-updates/main Translation-en [310 kB]
Get:15 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-updates/main amd64 Components [175 kB]
Get:16 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-updates/main amd64 c-n-f Metadata [15.8 kB]
Get:17 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-updates/universe amd64 Packages [1502 kB]
Get:18 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-updates/universe Translation-en [304 kB]
Get:19 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-updates/universe amd64 Components [377 kB]
Get:20 http://security.ubuntu.com/ubuntu noble-security/main amd64 Packages [1391 kB]
Get:21 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-updates/universe amd64 c-n-f Metadata [31.4 kB]
Get:22 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-updates/restricted amd64 Packages [2411 kB]
Get:23 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-updates/restricted Translation-en [550 kB]
Get:24 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-updates/restricted amd64 Components [212 B]
Get:25 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-updates/multiverse amd64 Packages [30.3 kB]
Get:26 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-updates/multiverse Translation-en [5808 B]
Get:27 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-updates/multiverse amd64 Components [940 B]
Get:28 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-updates/multiverse amd64 c-n-f Metadata [484 B]
Get:29 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-backports/main amd64 Packages [40.4 kB]
Get:30 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-backports/main Translation-en [9208 B]
Get:31 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-backports/main amd64 Components [7132 B]
Get:32 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-backports/main amd64 c-n-f Metadata [368 B]
Get:33 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-backports/universe amd64 Packages [29.2 kB]
Get:34 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-backports/universe Translation-en [17.6 kB]
Get:35 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-backports/universe amd64 Components [11.0 kB]
Get:36 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-backports/universe amd64 c-n-f Metadata [1444 B]
Get:37 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-backports/restricted amd64 Components [216 B]
Get:38 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-backports/restricted amd64 c-n-f Metadata [116 B]
Get:39 http://us-east-1.ec2.archive.ubuntu.com/ubuntu noble-backports/multiverse amd64 Components [212 B]
ubuntu@ip-172-31-31-118:~$
























