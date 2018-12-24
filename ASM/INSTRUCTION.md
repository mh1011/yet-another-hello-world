# Instruction to Run An Assembly Code

### GNU/Linux

#### Requirements:
- The Netwide Assembler Project (nasm)  
- PC with **x86_64** Architecture  
- GNU Linker (ld); should be built-in   

#### Procedure: 
1. Install **nasm**  
>_sudo apt install nasm_  
2. Go to the directory of the*.asm file  
3. Open Console  
4. Create an Object file following this command  
>_nasm -f elf64 -o FileName.o Filename.asm_  

Here:   
- **elf64**         => Object file for 64 bit architechture  
- **FileName.o**    => Name of the oObject file  
- **FileName.asm**  => Name of the assembly file  
5. An Object file will be created. The Object should be Linked by GNU Linker _**ld**_. Type in console:  
>_ld FileName.o FileName  
6. Run the code by **./FileName**  



### Windows

Due Process



## Resources:

**Video Tutorial**                : (https://youtu.be/VQAKkuLL31g)  
**Text Resources**                : (http://www.tldp.org/HOWTO/Assembly-HOWTO/)  
**Official NASM Documentation**   : (https://www.nasm.us/docs.php)  