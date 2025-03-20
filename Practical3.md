1. Open the editing_final_lab.txt file in Vim and Nano:
-> VIM- vim editing_final_lab.txt
   NANO- nano editing_final_lab.txt
![Screenshot 2025-03-20 155524](https://github.com/user-attachments/assets/7229513d-0760-4861-92c9-5b79e92dc02c)
![Screenshot 2025-03-20 155614](https://github.com/user-attachments/assets/d1e245d1-521b-4b8d-9b4f-87ad48b6a347)


![Screenshot 2025-03-20 155926](https://github.com/user-attachments/assets/1f3d0115-0695-4552-9923-7102667f80df)
![Screenshot 2025-03-20 160007](https://github.com/user-attachments/assets/00f7f2d1-e958-41e9-bb1c-b3e77cc99c94)


2. Use the lab_file shell variable:
-> lab_file="editing_final_lab.txt"
   vim $lab_file
![Screenshot 2025-03-20 160612](https://github.com/user-attachments/assets/43d2395c-06b0-4d4a-8e7b-92cac0f25975)


3. Enter visual mode in Vim:
-> Open Vim.
   Press v to enter visual mode.
![Screenshot 2025-03-20 180941](https://github.com/user-attachments/assets/ee337a72-1c49-4850-9ec2-0ef8b33361e9)
   

5. Remove the last seven characters from the first line:
-> Press ^ (caret) to go to the beginning of the line.
   Press v to start selecting characters.
   Move to the end of the line using $.
   Press d7 to delete the last 7 characters.

6. Preserve only the first four characters of the first column:
-> Go to the beginning of the line using 0.
   Press v and move to the 4th character using l (right arrow).
   Press d to delete everything after the 4th character.

7. Save and exit:
-> :wq

