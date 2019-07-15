This is a resource file to easily access a solution for fixing carriage returns 
that may come up in your programs using JavaScript. 

resultVariable = resultVariable.replace(/(\r\n|\n|\r)/gm,"");

Before:
<a herf="https://photos.google.com/search/_tra_/photo/AF1QipOYed3_Va3SioI2c8pkkWuWhUb_5CKrKSvCnew0"> 
console.log results Before </a>


After :
<a href="https://photos.google.com/share/AF1QipMD_EoJUMDFffqSZDbCr_ilANKCXQkk1W57bOB9iTLiMlbFMEPkHmONYsL0ZlqyEw?key=UHZYYS05VFVvVmZYSmJwbEV5cjlMUm1zalg4MjdR" >
console.log results After </a>


Happy Hacking ! ^_^ 