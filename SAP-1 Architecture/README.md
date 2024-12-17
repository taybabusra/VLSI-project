![main](https://github.com/user-attachments/assets/3f4d2bf8-9e80-43dc-9c67-a1e5ee495d55)

### Behaviour Analysis of a microprocessor :
Fect Decode Execute analysis: After the design is ready, Firstly pro
grammed the RAM with instructions code. The instruction: 0001 1010
 as LDA 10 or load the register A with memory contents of location 10.
 This instruction has two parts. The Opcode: 0001 meaning load A and
 the operand 1010 meaning 10.\
 Program the Ram\
 STEP:\
 • • Turn on debug pin\
 • • Pulse the pcreset pin.\
<img width="587" alt="image" src="https://github.com/user-attachments/assets/21e01c9f-bcd2-4ba8-9723-4bc4ba1bd712" />
 • • Set debugdata to 0000 0000.\
 • • Toggle marinen and give a clock pulse.\
 • • Turn off marinen.\
 • • Set debugdata to 0001 1010.\
 • • Toggle sramwr and give a clock pulse.\
 • • Turn off sramwr and observe the data saved in address 0000.\
 similarly, different data can be saved in a particular address\
<img width="302" alt="image" src="https://github.com/user-attachments/assets/8d25b6d2-2228-4ea8-863c-15c9a22aa702" />
<img width="273" alt="image" src="https://github.com/user-attachments/assets/6a9c91e3-aef2-4558-afcc-aabbba7028af" />
<img width="269" alt="image" src="https://github.com/user-attachments/assets/fb0602ed-fd8e-42a1-8010-9132d5778d72" />
<img width="263" alt="image" src="https://github.com/user-attachments/assets/3cd7ee89-59d6-4851-abec-6f95ef5e2788" />
<img width="248" alt="image" src="https://github.com/user-attachments/assets/b1a5aa2f-623c-4fc4-8b99-63354380759d" />
