1. Shell Script to Print System Information
-> (a)Create a file named system_info.sh:
![Screenshot 2025-03-20 174140](https://github.com/user-attachments/assets/42c42014-d6d3-4fc9-85b6-9515cb2002e1)
 
   (b)Make the script executable:
      chmod +x system_info.sh
   
   (c)Run the script:
      ./system_info.sh
![Screenshot 2025-03-20 173950](https://github.com/user-attachments/assets/b53eb717-d3b3-4b70-9445-5e0c072e8574)

3. Shell Script to Perform Basic Mathematical Calculation
-> (a)Create a file named calc.sh:
![Screenshot 2025-03-20 172638](https://github.com/user-attachments/assets/8cd2ef85-b66b-4577-b089-b8203ba661fd)

(b)Make the script executable:
chmod +x calc.sh

(c)Run the script:
./calc.sh
![Screenshot 2025-03-20 173412](https://github.com/user-attachments/assets/296e30de-aefa-4d06-8fdc-0f00ec9524f9)

3. Use Redirection Operators to Store Output of Commands
-> (a)Redirect stdout to a file:
      ls > output.txt
![Screenshot 2025-03-20 174849](https://github.com/user-attachments/assets/3431d3c9-ed1a-44ac-a7a7-b36d5929efca)

   (b)Append output to an existing file:
      date >> output.txt
![Screenshot 2025-03-20 174858](https://github.com/user-attachments/assets/a1925550-a4c3-44a5-8672-68e66f0b8a53)
![Screenshot 2025-03-20 174518](https://github.com/user-attachments/assets/b1e39db0-8d91-48c5-bc1f-31021e8e3359)

   (c)Redirect stderr to a file:
      ls nonexistentfile 2> error.txt
![Screenshot 2025-03-20 174908](https://github.com/user-attachments/assets/e587bade-fb24-4f4a-8f28-d4b7725be955)

   (d)Redirect both stdout and stderr to a file:
      ls . nonexistentfile &> all_output.txt
![Screenshot 2025-03-20 174954](https://github.com/user-attachments/assets/6a978746-2c53-4620-9227-582e2c344e2c)
![Screenshot 2025-03-20 175052](https://github.com/user-attachments/assets/a29101ff-7ad6-48f7-b985-a0d9e156ade2)


   (e)Pipe output to another command:
      cat file.txt | grep "keyword"
![Screenshot 2025-03-20 175030](https://github.com/user-attachments/assets/0db66fee-1950-45ff-8b39-1a58f1988e0c)


