1. Create the /home/consultants directory:
-> sudo mkdir /home/consultants
![Screenshot 2025-03-20 161003](https://github.com/user-attachments/assets/d9133f62-95e7-4001-aa19-f2fd37a07a1f)

2. Add write permission to the consultants group (symbolic method):
-> sudo chmod g+w /home/consultants
![Screenshot 2025-03-20 161042](https://github.com/user-attachments/assets/4ad7623b-ef39-4b42-b8a6-b1d69316818a)

3. Forbid others from accessing the /home/consultants directory (octal method):
-> sudo chmod 750 /home/consultants
![Screenshot 2025-03-20 161132](https://github.com/user-attachments/assets/17f96c18-caf0-4e29-84b4-34c65aaf93fa)
![Screenshot 2025-03-20 161246](https://github.com/user-attachments/assets/6678eb80-73c2-4681-9a66-3815c12e9d80)

4. Change the default umask for the operator1 user:
-> (a)Open the user's .bashrc or .profile file:
      sudo nano /home/akshay10/.bashrc
   (b)Add the following line to set the umask:
      umask 0074
![Screenshot 2025-03-20 161951](https://github.com/user-attachments/assets/845f65a5-13a1-44a4-a878-36d8afefec83)
![Screenshot 2025-03-20 162042](https://github.com/user-attachments/assets/eb30c6a2-d166-40bd-a12c-42f6579ded67)
![Screenshot 2025-03-20 162122](https://github.com/user-attachments/assets/2df50d7f-624f-47f0-a144-dccb831d3358)
   

5. Confirm the umask:
-> su - akshay10
   umask
   ![Screenshot 2025-03-20 162552](https://github.com/user-attachments/assets/9f96dbb7-cf82-4190-921b-a6b9797250f1)


