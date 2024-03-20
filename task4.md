**Execution of the Task 4**


**Use the following instructions to get the gtkwave window**


ls - to check the contents of the folder


iverilog singh.v singh_tb.v - to simulate the verilog code and to check the errors


./a.out - to get the output and make vcd file to be ready open
![121](https://github.com/karthik-singh07/karthik-singh/assets/160622150/03d720ef-c681-42af-985e-c5e4412c4322)



![12](https://github.com/karthik-singh07/karthik-singh/assets/160622150/214cc80e-564c-4dde-a5ae-34fcd213917a)



**after running the command
gtkwave abdul.vcd**


![WhatsApp Image 2024-03-20 at 15 22 27_d9abe8f3](https://github.com/karthik-singh07/karthik-singh/assets/160622150/2d8c2e5e-9c49-466b-b9b3-dc1c1f9f2f95)




**Before moving to the execution of the instructions let us understand few parts of a verilog code**

**-the code has been written in a systematic way and broken down into different parts**

1. Instruction Fetch Stage
   
  ![312794257-6009d228-beac-411e-a2ef-72ce8d6fad82](https://github.com/karthik-singh07/karthik-singh/assets/160622150/e5683b7b-a1c9-4a16-bd38-00841959e98c)


2. Instruction Decode Stage

   ![312794650-0bf49697-4e9e-42dc-adcf-eed7df8e957c](https://github.com/karthik-singh07/karthik-singh/assets/160622150/adce69fb-b56c-4303-b335-d5888358c111)

3. Contents of registers and registers used
![312795303-32ae2162-efe4-448a-afe2-7e850278e547](https://github.com/karthik-singh07/karthik-singh/assets/160622150/387459e2-b125-48db-bf07-7b7470c81084)

4. Instructions Hardcoded
![312795521-23c86e3e-d2bd-4805-a8d3-2b1f6bde84c8](https://github.com/karthik-singh07/karthik-singh/assets/160622150/bf30cd68-0ddc-42a4-a60a-2ed626cd336b)


**Lets move on to the execution Stage with Waveforms obtained for running the gtkwave abdul.vcd**


1. When instantiated module is selected we get all the registers and wires as shown in the below figure
![312796529-d0ad6822-9ef1-4424-89f5-4e8ea783609a](https://github.com/karthik-singh07/karthik-singh/assets/160622150/ecc9f111-4d40-4cd1-b2ae-be729d117a17)

 
2. Upon adding few signals the waves can be see as shown in the below figure
![312797005-edd173c1-6e89-4164-b5cb-b77a12d78c9b](https://github.com/karthik-singh07/karthik-singh/assets/160622150/0cecc3d7-73b6-4503-92e6-03fc60b3fd5a)

**Output showing the ADD Operation**

![WhatsApp Image 2024-03-20 at 17 07 52_ac83bf3a](https://github.com/karthik-singh07/karthik-singh/assets/160622150/f7cbcd0b-33bc-4e46-85c8-aebf05ea6118)



**Output showing the SUB Operation**


![WhatsApp Image 2024-03-20 at 17 15 40_cabe3700](https://github.com/karthik-singh07/karthik-singh/assets/160622150/6e02f760-48cb-4358-b276-ea81dd3ef975)

**Output showing the AND Operation**

![WhatsApp Image 2024-03-14 at 14 51 11_9e3af44e](https://github.com/Abdulbitm/Abdul/assets/160620896/c4f77171-0166-4815-8d50-7820613c9b3a)


**Output showing the OR Operation**
![WhatsApp Image 2024-03-14 at 14 51 11_64d882fe](https://github.com/Abdulbitm/Abdul/assets/160620896/45ae0f92-78ab-469a-bacd-5cdb2f7c5578)

![WhatsApp Image 2024-03-14 at 14 51 11_c263287b](https://github.com/Abdulbitm/Abdul/assets/160620896/4d337702-67ac-4800-b7b6-b4bf4a7029f8)

**Output showing the XOR Operation**

![WhatsApp Image 2024-03-14 at 14 51 11_64d882fe](https://github.com/Abdulbitm/Abdul/assets/160620896/5584f6ad-a942-460b-a2d1-c44a1a68ca8e)








