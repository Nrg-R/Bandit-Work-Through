The first ( 0th ) level of this game is very self explanatory ;
we input the ssh command as instructed by the web page and we are logged into bandit 0 
but what does all this actually mean ? 
SSH means Secure shell which is a network protocol that allows for computers to connect and communicate securely over unsafe networks like the internet. 

here the passwords for the level 0 ( Bandit 0 ) is provided to us by the creators of the program but moving forwards we have to find the passwords for levels like
Bandit 1 , Bandit 2 , ourselves by solving different types of rpoblems by using different types of tools.

here, we use 
ssh bandit0@bandit.labs.overthewire.org -p 2220
ssh is the secure shell we are using ,
we are using ssh to conntext to bandit.labs.overthewire.org 

we are joining bandit.labs.overthewire.org using port hence -p 
we are using port 2220 hence -p 2220 
and we are joining under the username bandit0 

and in future levels we will still be joining bandit.labs.overthewire.org using the port -p 2220 but we will be joining under different consequtive usernames
first bandit 0, then bandit 1 , bandit 2 and so on;

and in order to join as bandit 1, we will have to figure out the passwords for it under bandit 0 and so on,

after joining into bandit 0, you can use different commands as advised by the web site,
in almost all of the levels the main goal is to find the password, and most text are stored inside files,
you have to find the file and find a way to extract the password from the file,
the first level only requires youto understand and execute very simple commands in linux, goodluck

I hope you understood this short explanation and i want you to know that I am not an expert by any means, I am simply trying to reinforce my knowledge while 
journaling my journey, but i have a feeling that this will definetly help someone. If there are any mistakes in my logic or knowledge feel free to let me know .

