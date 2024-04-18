SecNotes
===

begin 2024/04/17 9:20  
finish 

###  User Flag

- [x] Scan port

Qucikly Port Scan
![image](https://github.com/jim091418/htb_writeup/assets/67756786/65b9d9fc-dbef-43ca-a3ca-08f86bf705dc)

I try to scan port 445, maybe can use ms-17-010,but it is not easy as I think.
![image](https://github.com/jim091418/htb_writeup/assets/67756786/c31ba67c-3633-420b-a72f-cbdfc561af2b)

- [x] Check web 
Path traversal
![image](https://github.com/jim091418/htb_writeup/assets/67756786/c7978e5d-f5c2-44d2-ace9-6c49f63fda39)

I try register account named test1 and logined to test note feature.But there's nothing special.

![image](https://github.com/jim091418/htb_writeup/assets/67756786/c6ba459c-111e-4b61-b8ce-668b046bcdc6)

I noticed administrator's name might be tyler.  
![image](https://github.com/jim091418/htb_writeup/assets/67756786/5e93c567-4111-4a68-8766-d05f54f09c3f)

If account name is incorrect, it will display "No account found with that username".
![image](https://github.com/jim091418/htb_writeup/assets/67756786/a9e9f034-0b52-47d7-b27c-603ac47740f4)

If password is incorrect , it will display "The password you entered was not valid".
![image](https://github.com/jim091418/htb_writeup/assets/67756786/ccf153f4-8a27-4965-9864-7e691f3a91d2)

I try use tyler to login, and I know tyler account exist!  
![image](https://github.com/jim091418/htb_writeup/assets/67756786/ea76e053-3ed9-4173-a37f-219f10bb2bfd)

Now, hydra is flexing its muscles. 
![image](https://github.com/jim091418/htb_writeup/assets/67756786/74527708-33f0-4c74-9c2d-7a6d4b828ac2)

Blank passworld, I didn't expect that.  
![image](https://github.com/jim091418/htb_writeup/assets/67756786/1ec7ec98-f9e5-4064-bb07-f76e0d01d207)



![image](https://github.com/jim091418/htb_writeup/assets/67756786/20d4f463-ca4b-4e88-bf0e-eacb5cfbdb08)

![image](https://github.com/jim091418/htb_writeup/assets/67756786/d87ec3e6-03fe-45d1-9f4f-5ab18900508f)

![image](https://github.com/jim091418/htb_writeup/assets/67756786/24369632-2997-42e6-80b7-fcb6e687a81c)

![image](https://github.com/jim091418/htb_writeup/assets/67756786/f1528557-faf1-41b9-950d-89fe7f982738)

![image](https://github.com/jim091418/htb_writeup/assets/67756786/ff2d6518-8e71-4954-80aa-bdded526cff7)

![image](https://github.com/jim091418/htb_writeup/assets/67756786/28b3d16c-6aab-409b-81e3-a947855b46d9)




###  Root Flag

- [x] Step 1

xxxxxxxxxxx
