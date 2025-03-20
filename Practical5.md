1. ps Command
-> (a)Display all running processes:
      ps aux
![Screenshot 2025-03-20 162731](https://github.com/user-attachments/assets/61c05025-32b7-48ea-867a-b8cacac16120)

   (b)Show processes for the current terminal session:
      ps
![Screenshot 2025-03-20 162900](https://github.com/user-attachments/assets/827d9867-18a4-451b-9d2a-46fbdb7d8dda)

   (c)Display a process tree:
      ps -e --forest
![Screenshot 2025-03-20 163001](https://github.com/user-attachments/assets/f881d640-2e1b-41b1-bfe0-126eb8e0ef0d)
   
   
   (d)Filter by process name:

      ps -C firefox
![Screenshot 2025-03-20 163042](https://github.com/user-attachments/assets/cabe9d6f-a68f-4537-a610-0464b29dab70)

   (e)Show detailed information of a specific process:
      ps -p 1234 -o pid,ppid,cmd,%mem,%cpu
![Screenshot 2025-03-20 163201](https://github.com/user-attachments/assets/1ca7fbb3-5f65-448d-89da-1587ea4e8b20)

2. kill Command
-> (a)Find the PID: 
      ps aux | grep firefox
![Screenshot 2025-03-20 163248](https://github.com/user-attachments/assets/913fef0c-7ec3-4d9a-99cb-9bd2f28820d4)

   (b)Kill a process by PID:
      kill 1234

   (c)Force kill a process: 
      kill -9 1234

   (d)Kill by process name: 
      killall firefox

3. top Command
-> top
   Sort by memory usage: Press M
   Sort by CPU usage: Press P
   Kill a process: Press k → Enter the PID
   Exit top: Press q
![Screenshot 2025-03-20 163412](https://github.com/user-attachments/assets/39726a7b-cb8c-43c9-ad3b-7bcb5a0e6259)

5. apt-get Command
-> (a)Update package list:
      sudo apt-get update
![Screenshot 2025-03-20 164859](https://github.com/user-attachments/assets/5d329ca4-8edb-4cf6-8cec-79a3c5bd2f3a)

   (b)Upgrade installed packages:
      sudo apt-get upgrade
![Screenshot 2025-03-20 163618](https://github.com/user-attachments/assets/475e192a-78d6-439c-a583-e36169645d5b)

   (c)Install a package:
      sudo apt-get install vim
![Screenshot 2025-03-20 181843](https://github.com/user-attachments/assets/6e2316a3-de1e-4a4c-a38d-feb83a37c8c5)

   (d)Remove a package:
      sudo apt-get remove vim
![Screenshot 2025-03-20 181905](https://github.com/user-attachments/assets/9a385d96-6c36-4fbd-9796-8ce1b7cb5ce4)

   (e)Remove package along with configuration files:
      sudo apt-get purge vim
![Screenshot 2025-03-20 181917](https://github.com/user-attachments/assets/ab92fa63-0d10-41eb-a29a-9184c8448af4)

   (f) Clean up unused packages: sudo apt-get autoremove:
 ![Screenshot 2025-03-20 181923](https://github.com/user-attachments/assets/451e3372-64f3-42f5-98f0-fb80fd745e88)

   (g) Clean package cache: sudo apt-get clean:
 ![Screenshot 2025-03-20 181930](https://github.com/user-attachments/assets/3b869ba2-12dd-4172-8636-4f72fba555b5)
  
