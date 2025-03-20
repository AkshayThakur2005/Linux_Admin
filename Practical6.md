1. Create the opr1 user:
-> sudo useradd -m opr1
![Screenshot 2025-03-20 165949](https://github.com/user-attachments/assets/7b4ce59b-dc4b-4084-a60b-dffb721ec225)

2. Confirm that opr1 exists:
-> cat /etc/passwd | grep opr1
![Screenshot 2025-03-20 170026](https://github.com/user-attachments/assets/3c00aab4-3e41-4639-bab8-2d8a97673eda)

3. Set the password for opr1:
-> sudo passwd opr1
![Screenshot 2025-03-20 170347](https://github.com/user-attachments/assets/09a1e491-a669-40f5-ab42-7371909a4799)

4. Create opr2 and opr3 users:
-> sudo useradd -m opr2
   sudo passwd opr2
   sudo useradd -m opr3
   sudo passwd opr3
![Screenshot 2025-03-20 170528](https://github.com/user-attachments/assets/62db044a-15f1-4d34-b0b0-241f718a2b5b)

5. Update the comment for opr1 using usermod -c:
-> sudo usermod -c "System Operator 1" opr 1
![Screenshot 2025-03-20 171126](https://github.com/user-attachments/assets/007c1924-d3a2-448d-b151-ccacb87e6a43)

6. Remove the opr3 user:
-> (a)To delete opr3 without removing the home directory:
      sudo userdel opr3
   ![Screenshot 2025-03-20 171207](https://github.com/user-attachments/assets/5ebfd68e-f631-4c4c-9102-9eed6112ccce)

      (b)To delete opr3 and its home directory:
      sudo userdel -r opr3
  ![Screenshot 2025-03-20 171243](https://github.com/user-attachments/assets/b156aba9-5f38-4a0d-9407-e40fb1c7fb34)

   
