# assembly-language-NASM
# To set up in Ubuntu 20.04+  

```
# Install Doxbox  
sudo apt install dosbox 
doxbox 

# Inside dosbox (give it some path in your host machine) 
mount c /home/nam/ee213 

c: 

# Assemble and run 
nasm c.asm -o c.com 
afd c.com 

# Assemble with Listing 
nasm c.asm -l c.lst -o c.com 
