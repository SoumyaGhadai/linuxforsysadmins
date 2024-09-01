# Linux for sysadmin

# monolithic and modular linux kernel
monolithic- the necessary s/w drivers will load to memory
![image](https://github.com/user-attachments/assets/279cec29-675e-4994-9828-32dd962dd5e8)


bash- bourne again shell

id; whoami; uname; uname -a; runlevel; 
0-6 0-shutdown, 1-single user, 2-single with network, 3-multi users with network, 4 not defined, 
    5 3+gui, 6- reboot
init 0
# basic commands 1 
date; ls; ls -l; ls -ld; ls -al;
touch vi; touch myproject; vi myproject;
vi, i insert, esc, shift+:+x,
cat myproject ,cat /etc/passwd|less, cat /etc/passwd|grep rtkit, cat /etc/passwd|wc -c, cat /etc/passwd|wc -l
<!-- everything is a file(cpu, mem, hdd etc.), small programs combined together to perform a bigger task (piping) -->
file myproject

/root /home /sbin /etc /tmp /usr /boot /dev /var /bin
root home directory only the super user has access
home directory for all users workspace open for users
bin and sbin regular binaries for regular users and special binaries for root users
etc all config files are present
tmp temporary files are present
usr thirdparty installation location
boot all boot files are present
dev info about all devices
var document root, website root

id; cat /etc/passwd |grep root; cat /etc/passwd; pwd; mkdir test1; mkdir test2 test3;
cp myproject test4; ls -l test4/; cp /home/student/myproject test4;
<!-- copy files -->
rmdir test1; mv myproject test2/; ls -l test2;
<!-- rename -->
mv myproject mytestproject
<!-- user management or file system management -->
wildchars^C; * ?^C
ls -l te*; ls test*
# basic commands 2
<!-- redirection for logs process analysis etc.-->
<!-- input-> process -> output -->
![image](https://github.com/user-attachments/assets/15001e39-a0f8-4f21-a7ee-5bb5db8a06e3)






