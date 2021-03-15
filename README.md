# Team : AMIGO
# Developed by CS19B019, CS19B032
# AMIGO-MIPS-SIMULATOR
First download all the files<br/>
Then kepp all files in the same folder<br/>
Then run App.py file<br/>
Click on the File and Load the bubblesort.asm file which u had downloaded<br/>
Then click on run button in GUI<br/>
# instructions related to command in our simulator
The commands accepted are add,addi,sub,j,slt,bne,st<br/>
Comments should be kept in new line<br/>
If u want to skip the line or want to leave line as blank the just click enter donot give any spaces<br/>
Must keep , immidiately after declaing register<br/>
Space is not allowed between register and ,<br/>
In li command i,e: "li $s2, " it should not be incomplete<br/>
# Changes from actual MIPS architecture
1.There is no "lw(load word)" command in our simulator<br/>
2.Instead we kept "li(load integer)" command to replace it<br/>
3.We have slt command which is slightly different from the original one<br/>  that is, if comparison is true it jumps to the given adderess or label<br/>  ex: slt $s1,$s2,label, if value in s1 is <br/>  less than value in s2 then it jumps to the label.

