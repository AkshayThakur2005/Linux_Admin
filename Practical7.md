1. chown Command
-> (a)Change the owner of a file:
      sudo chown user1 file.txt
![Screenshot 2025-03-20 222136](https://github.com/user-attachments/assets/2410dc0c-aa95-428f-9f73-b67ef6cd05ce)

   (b)Change the owner and group of a file:
      sudo chown user1:usergroup file.txt
![Screenshot 2025-03-20 222420](https://github.com/user-attachments/assets/5fc249c4-59af-4763-a66e-c3dde2d111bb)

   (c)Change only the group:
      sudo chown :usergroup file.txt
![Screenshot 2025-03-20 222752](https://github.com/user-attachments/assets/6644f593-29cf-4a68-b052-5dfba82a4e8b)

   (d)Change ownership recursively (for directories):
      sudo chown -R user1:usergroup /path/to/directory
![Screenshot 2025-03-20 222843](https://github.com/user-attachments/assets/94f1feb5-cd86-4901-832f-53bbece42a1f)

   (e)Transfer ownership to root:
      sudo chown root file.txt
![Screenshot 2025-03-20 223109](https://github.com/user-attachments/assets/78aa0aa8-b50d-4a27-b20a-7697f9f070f2)

   (f)Use --from to change from a specific owner:
      sudo chown --from=current_owner new_owner file.txt
![Screenshot 2025-03-20 223310](https://github.com/user-attachments/assets/a6220916-4b9e-464b-95e3-d9063be7cc08)

2. chmod Command
-> (a)Give execute permission to the user:
      chmod u+x file2.txt
![Screenshot 2025-03-20 223452](https://github.com/user-attachments/assets/45af2f68-a9e9-4a89-a61e-5da06bd7bce0)

   (b)Remove write permission for others:
      chmod o-w file2.txt
![Screenshot 2025-03-20 223549](https://github.com/user-attachments/assets/5ecd04e0-bf3c-49b2-9fd1-ebf9e8ded2e0)

   (c)Give read and execute permission to the group:
      chmod g+rx file2.txt
![Screenshot 2025-03-20 223620](https://github.com/user-attachments/assets/f02ca52c-07b7-455e-8dc8-dc2c280b85d3)

   (d)Set specific permissions:
      chmod u=rwx,g=rx,o=r file2.txt
![Screenshot 2025-03-20 223657](https://github.com/user-attachments/assets/e9b65f0c-7f6d-415d-bb1e-7130d894a077)

   (e)Set permissions to rwxr-xr-- using octal mode:
      chmod 754 file2.txt
![Screenshot 2025-03-20 223727](https://github.com/user-attachments/assets/266ff36e-4591-4324-9aea-6472d52a80e2)

   (f)Recursive Change of Permissions:
      chmod -R 755 /path/to/directory
![Screenshot 2025-03-20 223751](https://github.com/user-attachments/assets/e0d49679-d973-4bd0-a4f6-cd260533927d)

   (g)Change permissions based on existing files:
      chmod --reference=ref_file.txt target_file.txt
 ![Screenshot 2025-03-20 223831](https://github.com/user-attachments/assets/97d4ca8b-7f8c-41e1-86ac-1b6ecd184865)

