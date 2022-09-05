## Lab 1 - Pseudo Random Number Generation
In this [lab](https://seedsecuritylabs.org/Labs_20.04/Files/Crypto_Random_Number/Crypto_Random_Number.pdf), you will apply your knowledge in class to find out some interesting facts and do some experiments on crypto programming. You need to complete all the five tasks in this lab and submit a detailed lab report, with screenshots, to describe what you have done and what you have observed with necessary explanation. Please include important code snippets followed by explanation. Simply attaching code without any explanation will receive no credits.

The lab is one of the exercises in SEED Project. It uses a Virtual Machine (VM) [image](https://seedsecuritylabs.org/labsetup.html) in order to simplify the experiment setup. We are using the Ubuntu 20.04 image for this lab. Load the VM image with your VirtualBox or VMware (whichever you prefer). Please read the VM [User Manual](https://web.ecs.syr.edu/~wedu/seed/Documentation/Ubuntu16_04_VM/Ubuntu16_04_VM_Manual.pdf) carefully before you start working on the labs.

## Useful Instructions
The lab description has the step-by-step walkthrough and detailed instruction. Here are some additional hints and notices:
* The VM image is an archive of vmdk files. VirtualBox users can follow the instruction in the [User Manual](https://web.ecs.syr.edu/~wedu/seed/Documentation/Ubuntu16_04_VM/Ubuntu16_04_VM_Manual.pdf) to import those files. For VMware user, please refer to this [video](https://www.youtube.com/watch?v=1g7qkozxh4o&ab_channel=Magazie) for lab setup.
* In Task 2, you need to implement an AES-128-CBC program to perform encryption. Python is recommended here since you may use libraries like Crypto, pycrypto or cryptography to simplify the task. However, it is also acceptable to use any other languages. Just remember to attach the code with enough explanation.
* The plaintext, ciphertext and IV provided in Task 2, together with the key you generate in Task 1, are all hexadecimal codes. Conversion may be applied to handle them in your program.
* The question at the end of Task 4 is optional.
* The 256-bit key in the last step is supposed to be a binary string (sequence of 0s and 1s of length 256).
* Please take screenshots periodically and regularly and include them in your report. They not only serve as evidence of completion but also help the grader understand what you're trying to achieve.
* Please attach your code with adequate explanation for each task in your report to receive full credits.

## Points Break Down
This lab has 40 points in total. Task 1 through Task 5 are worth 5, 15, 5, 5, 10 points respectively.

## Submission Details
* This assignment is due on TBD.
* You can work in a group of up to 3 students (class roster with email addresses posted).
* Only one report is needed from each group. Please list group members in your report explicitly.
* Submit your report at Canvas in one PDF file.
* Please type your solutions. In general NO hand-written report is accepted.

## Grading
* Completeness (25 pts): All the steps as instructed in the lab manual must be included in the report with adequate evidence.
* Presentation (15 pts): The report must be clear and correct in organization and writing with adequate explanation.