**By Referring to C-based Lab videos and RISC-V-based lab videos**

**Snapshots of the compiled C code and RISC-V**

**Step 1: check whether the leafpad is installed in ur machine by using the commands
leafpad sum1ton.c& (sum1ton.c is the file name)
If the leafpad editor is opened without any errors then type the C code.**
****If the leafpad is not installed in ur machine then install by using the following command**

**sudo snap install leafpad****
![Screenshot from 2024-02-27 11-05-53](https://github.com/karthik-singh07/karthik-singh/assets/160622150/ef7f18a3-f5e4-496e-98b3-6db9cc926d6d)

****Step 2: Writing the C code in the leafpad editor** using the following command

**leafpad sum1ton.c&**
![Screenshot from 2024-02-27 10-46-08](https://github.com/karthik-singh07/karthik-singh/assets/160622150/9408aa0a-a3d0-480c-b3d5-2fb5c7d469b9)

**Step 3: After writing the C code save the editor by Ctrl+s**

**Step 4: Check for the errors by using the following command(compilation step)**

**gcc sum1ton.c**
![Screenshot from 2024-02-27 10-46-08 (1)](https://github.com/karthik-singh07/karthik-singh/assets/160622150/83999d61-e5a5-40ee-a8c0-976b07908795)

**Step 5: Check the output by using the command**

**./a.out**
![Screenshot from 2024-02-27 10-46-08 (1)](https://github.com/karthik-singh07/karthik-singh/assets/160622150/dead5fbd-04ab-4fb1-9d05-6b219ac2a0d5)

**The results will be displayed as** 

**Sum of numbers from 1 to 400 is 80200**


********************************************************RISCV Compilation and Execution*****************************************************

**Step 1: View the C Code in the editor window using the following command**

**cat sum1ton.c**
![Screenshot from 2024-02-27 10-48-10](https://github.com/karthik-singh07/karthik-singh/assets/160622150/a1ae058e-6c94-443f-bb3f-1619fc5e50e7)

**Step 2: Compile the code in riscv using the following command**

**riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**
![Screenshot from 2024-02-27 10-50-16](https://github.com/karthik-singh07/karthik-singh/assets/160622150/69428526-8086-43ab-b8d6-0b6e657669d8)


**Step 3: The ls ltr command in Linux is used to list the contents of the current directory in long format, sorted by last modified time in reverse order.**

**use the command**

**ls -ltr sum1ton.c**

![Screenshot from 2024-02-27 11-29-43](https://github.com/karthik-singh07/karthik-singh/assets/160622150/dd1c331b-8e41-42a0-9f12-1801e3921d30)


![WhatsApp Image 2024-02-27 at 11 32 39 AM png](https://github.com/karthik-singh07/karthik-singh/assets/160622150/dbae677a-26db-4fe2-9b4c-48b687a8ca38)


**Search for the Main and check the instructions of the C code execution. It has 15 instructions in the C execution**

![WhatsApp Image 2024-02-27 at 11 32 39 AM](https://github.com/karthik-singh07/karthik-singh/assets/160622150/9e24632a-c6cd-4433-97a3-78c8c90a049d)

![WhatsApp Image 2024-02-27 at 11 32 39 AM (1)](https://github.com/karthik-singh07/karthik-singh/assets/160622150/342fa122-c5be-4f55-adb5-e35ce9ee3d51)



**Step 4:**

**riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**

![WhatsApp Image 2024-02-27 at 11 32 40 AM](https://github.com/karthik-singh07/karthik-singh/assets/160622150/bf056bef-d758-47d9-8cd7-a77a141c807d)


![WhatsApp Image 2024-02-27 at 11 32 38 AM](https://github.com/karthik-singh07/karthik-singh/assets/160622150/da8ba57c-9ae9-4fa8-8e61-cb04101e8e4d)




