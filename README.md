# OSProject Running Containers for Application Development

Group Name: __P. OS__. 

Section: __4__. 

Team Mates:
1. __Muhammad Firdaus bin Zaini__ and __2217753__
2. __Amirul Fikri bin Amir__ and __2217981__
3. __Muhammad Najmi bin Muslim__ and __2129441__

## Rules
1. You are allowed to have **3 group** members. *Exception* is allowed **IFF (if and only if)** you are allowed to have 4 group members if you are a **multinational** or a **multigender** group. 
2. When you complete the project, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this OS project repository
1. First thing you need in doing this project is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the OS project repository in your own github account. 

    1. Go to https://github.com/joeynor/OSProject and click fork to copy the project into your own repository

    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork OSProject in your repository. ***(1 mark)*** 
- __https://github.com/najmihoshi/OSProject__.
2. How many files and folders are in this repository. ***(1 mark)*** 
- __1 Readme.md file and 1 image folder that contains 6 files__.
        


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own OSProject repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name, section and team members along with their matric IDs. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** 
- __It will run on Ubuntu Linux__.

2. What are the two options of ram, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** 
- __2-core CPU, 8 GB RAM, and 32 GB storage.__ 
- __4-core CPU, 16 GB RAM, and 64 GB storage.__.

3. Why must we commit and sync our current work on source control? ***(1 mark)*** 
- __To make sure our work is saved into the main repository__.


## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)***  
<img src="./images/terminalAnswer/1.png" width="70%">

2. Run the command **cat /etc/passwd** . ***(1 mark)***  
<img src="./images/terminalAnswer/2.png" width="70%">

3. Run the command **df** . ***(1 mark)***  
<img src="./images/terminalAnswer/3.png" width="70%">

4. Run the command **du** . ***(1 mark)***    
<img src="./images/terminalAnswer/4.png" width="70%">

5. Run the command **ls** . ***(1 mark)***      
<img src="./images/terminalAnswer/5.png" width="70%">

6. Run the command **ls -asl** . ***(1 mark)***        
<img src="./images/terminalAnswer/6.png" width="70%">

7. Run the command **free -h** . ***(1 mark)*** 
<img src="./images/terminalAnswer/7.png" width="70%">

8. Run the command **cat /proc/cpuinfo** . ***(1 mark)*** 
```bash
@najmihoshi ➜ /workspaces/OSProject (main) $ cat /proc/cpuinfo
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3225.700
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.84
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:

processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3229.147
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
top - 08:01:30 up 23 min,  0 users,  load average: 0.33, 0.33, 0.45
Tasks:  60 total,   1 running,  59 sleeping,   0 stopped,   0 zombie
%Cpu(s):  8.2 us,  9.6 sy,  0.0 ni, 81.5 id,  0.5 wa,  0.0 hi,  0.2 si,  0.0 st
MiB Mem :   7929.6 total,    340.0 free,   3738.6 used,   3851.0 buff/cache
MiB Swap:      0.0 total,      0.0 free,      0.0 used.   3805.4 avail Mem 
  
```

9. Run the command **top** and type **q** to quit. ***(1 mark)***        
<img src="./images/terminalAnswer/9.png" width="70%">

10. Run the command **uname -a**. ***(1 mark)*** 
<img src="./images/terminalAnswer/10.png" width="70%">

11. What is the available free memory in the system. ***(1 mark)*** 
- __218Mi__.

12. What is the available disk space mounted on /workspace. ***(1 mark)*** 
- __20771672__.

13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** 
- Version: __22.04.1-Ubuntu__.
- Hardware architecture: __x86_64__

14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** 
- __ls is command lists files and directories in the current directory.__
- __ls -asl command provide detailed listing including hidden files,in long format, file permissions, owner, group, size and modification time.__

15. What is the TLB size of the Virtual CPU. ***(1 mark)*** 
- __2560 4K pages__.

16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** 
- __3229.147 Mhz__.

17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** 
- __PID 4610__.


## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```
2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

```bash
@najmihoshi ➜ /workspaces/OSProject (main) $ docker exec -i -t gifted_shamir /bin/bash
root@0506669dd4e9:/# apt-get update
Get:1 http://deb.debian.org/debian bookworm InRelease [151 kB]
Get:2 http://deb.debian.org/debian bookworm-updates InRelease [55.4 kB]
Get:3 http://deb.debian.org/debian-security bookworm-security InRelease [48.0 kB]
Get:4 http://deb.debian.org/debian bookworm/main amd64 Packages [8788 kB]
Get:5 http://deb.debian.org/debian bookworm-updates/main amd64 Packages [13.8 kB]
Get:6 http://deb.debian.org/debian-security bookworm-security/main amd64 Packages [164 kB]
Fetched 9220 kB in 1s (7647 kB/s)                         
Reading package lists... Done
root@0506669dd4e9:/# apt-get install nano
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  libgpm2 libncursesw6
Suggested packages:
  gpm hunspell
The following NEW packages will be installed:
  libgpm2 libncursesw6 nano
0 upgraded, 3 newly installed, 0 to remove and 6 not upgraded.
Need to get 838 kB of archives.
After this operation, 3339 kB of additional disk space will be used.
Do you want to continue? [Y/n]   
Get:1 http://deb.debian.org/debian bookworm/main amd64 libncursesw6 amd64 6.4-4 [134 kB]
Get:2 http://deb.debian.org/debian bookworm/main amd64 nano amd64 7.2-1+deb12u1 [690 kB]
Get:3 http://deb.debian.org/debian bookworm/main amd64 libgpm2 amd64 1.20.7-10+b1 [14.2 kB]
Fetched 838 kB in 0s (4184 kB/s)
debconf: delaying package configuration, since apt-utils is not installed
Selecting previously unselected package libncursesw6:amd64.
(Reading database ... 6090 files and directories currently installed.)
Preparing to unpack .../libncursesw6_6.4-4_amd64.deb ...
Unpacking libncursesw6:amd64 (6.4-4) ...
Selecting previously unselected package nano.
Preparing to unpack .../nano_7.2-1+deb12u1_amd64.deb ...
Unpacking nano (7.2-1+deb12u1) ...
Selecting previously unselected package libgpm2:amd64.
Preparing to unpack .../libgpm2_1.20.7-10+b1_amd64.deb ...
Unpacking libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libncursesw6:amd64 (6.4-4) ...
Setting up nano (7.2-1+deb12u1) ...
update-alternatives: using /bin/nano to provide /usr/bin/editor (editor) in auto mode
update-alternatives: using /bin/nano to provide /usr/bin/pico (pico) in auto mode
Processing triggers for libc-bin (2.36-9+deb12u7) ...
root@0506669dd4e9:/# cd /root
root@0506669dd4e9:~# nano helloworld.txt
root@0506669dd4e9:~# exit
```

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available?
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```

```bash
@najmihoshi ➜ /workspaces/OSProject (main) $ docker stop gifted_shamir
gifted_shamir
@najmihoshi ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS                        PORTS     NAMES
0506669dd4e9   debian    "bash"    7 minutes ago   Exited (137) 30 seconds ago             gifted_shamir
@najmihoshi ➜ /workspaces/OSProject (main) $ docker restart gifted_shamir
gifted_shamir
@najmihoshi ➜ /workspaces/OSProject (main) $ docker restart gifted_shamir
gifted_shamir
@najmihoshi ➜ /workspaces/OSProject (main) $ docker exec -i -t gifted_shamir /bin/bash
root@0506669dd4e9:/# cd root
root@0506669dd4e9:~# ls
helloworld.txt
root@0506669dd4e9:~# cat helloworld.txt
Hi world
```
7. Stop the container and delete the container. What happened to your helloworld.txt?

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```

```bash
@najmihoshi ➜ /workspaces/OSProject (main) $ docker stop gifted_shamir
gifted_shamir
@najmihoshi ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                            PORTS     NAMES
0506669dd4e9   debian    "bash"    13 minutes ago   Exited (137) About a minute ago             gifted_shamir
@najmihoshi ➜ /workspaces/OSProject (main) $ docker rm gifted_shamir
gifted_shamir
```
***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** 
- __No, files in the container are not persistent because containers are meant to be temporary and disposable. When a container is removed, its file system and any files within it are also deleted.__.

2. Can we run two, or three instances of debian linux? . ***(1 mark)*** 
- __Yes we can__.

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** 
- __'root' and 'root'__.
```bash
@MirulFikri ➜ /workspaces/OSProject/myroot (main) $ ls -l /workspaces/OSProject/myroot
total 4
-rw-rw-rw- 1 root root 14 Jun 27 13:47 helloworld.txt
```

2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```

- __Yes__.
```bash
@MirulFikri ➜ /workspaces/OSProject/myroot (main) $ sudo chown -R codespace:codespace /workspaces/OSProject/myroot

@MirulFikri ➜ /workspaces/OSProject/myroot (main) $ ls -l /workspaces/OSProject/myroot
total 4
-rw-rw-rw- 1 codespace codespace 14 Jun 27 13:47 helloworld.txt
```

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** 
- The permission is __'drwxr-xr-x'__:
d indicates it's a directory,
rwx means the owner (root) has read, write, and execute permissions,
r-x means the group (root) has read and execute permissions only,
r-x means others (everyone else) also have read and execute permissions only.
- __Both the user and group are root__.

```bash
@firdauz003 ➜ /workspaces/OSProject (main) $ docker run --rm httpd ls -ld /usr/local/apache2/htdocs
drwxr-xr-x 2 root root 4096 Jun 13 18:30 /usr/local/apache2/htdocs
```

2. What port is the apache web server running. ***(1 mark)*** 
- __Port 80__.
```bash
@firdauz003 ➜ /workspaces/OSProject (main) $ docker ps
CONTAINER ID   IMAGE     COMMAND              CREATED          STATUS          PORTS                                   NAMES
635a1efe0c43   httpd     "httpd-foreground"   14 minutes ago   Up 14 minutes   0.0.0.0:8080->80/tcp, :::8080->80/tcp   relaxed_goodall
@firdauz003 ➜ /workspaces/OSProject (main) $ docker exec -it 635a1efe0c43 cat /usr/local/apache2/conf/httpd.conf | grep Listen
# Listen: Allows you to bind Apache to specific IP addresses and/or
# Change this to Listen on specific IP addresses as shown below to 
#Listen 12.34.56.78:80
Listen 80
```

3. What port is open for http protocol on the host machine? ***(1 mark)*** 
- __port 8080__.

```bash
@firdauz003 ➜ /workspaces/OSProject (main) $ docker port 635a1efe0c43 80
0.0.0.0:8080
[::]:8080
```

## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
## STEP 1:
## Create Networks ##
docker network create bluenet
docker network create rednet`

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
docker run -itd --net bluenet --name c1 busybox sh
docker run -itd --net rednet --name c2 busybox sh
```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)*** 
- __Busybox combines tiny versions of many common UNIX utilities into a single small executable.__
- __The command switch ```--name``` is used to assign a specific name to the container.__

2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)*** 
```bash
@MirulFikri ➜ /workspaces/OSProject (main) $ docker network ls
NETWORK ID     NAME      DRIVER    SCOPE
22d332f3a2fa   bluenet   bridge    local
156996483fe7   bridge    bridge    local
f09bdb1e4b73   host      host      local
95178c6816a5   none      null      local
bddc169c0874   rednet    bridge    local
```

3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)*** 
- bluenet gateway: __172.18.0.1__.
- rednet gateway: __172.19.0.1__.

4. What is the network address for the running container c1 and c2? ***(1 mark)*** 
- c1: __172.18.0.2__.
- c2: __172.19.0.2__.

5. Using the command ```docker exec c1 ping c2```, which basically tries to do a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)*** 
- __No, I was not able to ping__.
```bash
@MirulFikri ➜ /workspaces/OSProject (main) $ docker exec c1 ping c2
ping: bad address 'c2'
```

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```
***Questions:***

1. Are you able to ping? Show your output . ***(1 mark)*** 
- __Yes__.
```bash
@MirulFikri ➜ /workspaces/OSProject (main) $ docker exec c1 ping c2
PING c2 (172.20.0.3): 56 data bytes
64 bytes from 172.20.0.3: seq=0 ttl=64 time=0.132 ms
64 bytes from 172.20.0.3: seq=1 ttl=64 time=0.087 ms
64 bytes from 172.20.0.3: seq=2 ttl=64 time=0.110 ms
64 bytes from 172.20.0.3: seq=3 ttl=64 time=0.090 ms
64 bytes from 172.20.0.3: seq=4 ttl=64 time=0.119 ms
```

2. What is different from the previous ping in the section above? ***(1 mark)*** 
- __The previous ping failed because c1 and c2 were on separate networks (bluenet and rednet). Now both containers are connected to the same bridgenet network, which allows them to ping each other.__

## Intermediate Level (10 marks bonus)

### Node.js and MySQL in Docker Containers

This guide will help you set up a simple Node.js website that retrieves a random row from a MySQL database. Both the MySQL server and the Node.js server will run in separate Docker containers on two separate networks. Your job is to make it work by making the two containers in two separate network bridged together.

#### Step 1: Set Up the Docker Network

Create a Docker network to for the two containers.
For mysql, call it **mysqlnet** for nodejs call it **nodejsnet** .

#### Step 2: Set Up the MySQL Container

Run a MySQL container on the created network.

```sh
docker run --name mysql-container --network mysqlnet -e MYSQL_ROOT_PASSWORD=rootpassword -e MYSQL_DATABASE=mydatabase -e MYSQL_USER=myuser -e MYSQL_PASSWORD=mypassword -d mysql:latest
```

#### Step 3: Set Up the Node.js Container

1. **Create a directory for your Node.js application and initialize it.**

    ```sh
    mkdir nodejs-app
    cd nodejs-app
    npm init -y
    npm install express mysql
    ```

2. **Create a file named `index.js` with the following content:**

    ```js
    const express = require('express');
    const mysql = require('mysql');

    const app = express();
    const port = 3000;

    // Create a MySQL connection
    const connection = mysql.createConnection({
      host: 'mysql-container',
      user: 'myuser',
      password: 'mypassword',
      database: 'mydatabase'
    });

    // Connect to MySQL
    connection.connect((err) => {
      if (err) {
        console.error('Error connecting to MySQL:', err);
        return;
      }
      console.log('Connected to MySQL');
    });

    // Define a route to get a random row
    app.get('/random', (req, res) => {
      const query = 'SELECT * FROM mytable ORDER BY RAND() LIMIT 1';
      connection.query(query, (err, results) => {
        if (err) {
          console.error('Error executing query:', err);
          res.status(500).send('Server Error');
          return;
        }
        res.json(results[0]);
      });
    });

    // Start the server
    app.listen(port, () => {
      console.log(`Server running at http://localhost:${port}`);
    });
    ```

3. **Create a Dockerfile for the Node.js application:**

    ```Dockerfile
    # Use the official Node.js image
    FROM node:14

    # Create and change to the app directory
    WORKDIR /usr/src/app

    # Copy application dependency manifests to the container image
    COPY package*.json ./

    # Install production dependencies
    RUN npm install

    # Copy local code to the container image
    COPY . .

    # Run the web service on container startup
    CMD [ "node", "index.js" ]
    ```

#### Step 4: Build and Run the Node.js Container

1. **Build the Docker image for the Node.js application.**

    ```sh
    docker build -t nodejs-app .
    ```

2. **Run the Node.js container on the same network as the MySQL container.**

    ```sh
    docker run --name nodejs-container --network nodejsnet -p 3000:3000 -d nodejs-app
    ```

#### Step 5: Test the Setup

You can now test the setup by accessing the Node.js application in your browser or using a tool like `curl`:

```sh
curl http://localhost:3000/random
```

#### Step 6: Ensure `mytable` is Populated

Make sure you have created the `mytable` table and populated it with some data in your MySQL database for the above steps to work correctly.

You can use the following SQL commands to create and populate the table (run these commands in the MySQL container):

```sql
CREATE TABLE mytable (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(255) NOT NULL,
  value VARCHAR(255) NOT NULL
);

INSERT INTO mytable (name, value) VALUES ('example1', 'value1'), ('example2', 'value2'), ('example3', 'value3');
```

### Summary

You have now set up a Node.js application in a Docker container on nodejsnet netowrk and a MySQL database in another Docker container on mysqlnet network. Now bridge the two network together.

***Questions:***

1. What is the output of step 5 above, explain the error? ***(1 mark)*** 
- __There is error because there is no table created yet__.
```bash
@firdauz003 ➜ /workspaces/OSProject/nodejs-app (main) $ curl http://localhost:3000/random
Server Error@firdauz003 ➜ /workspaces/OSProject/nodejs-app (main) $
```

2. Show the instruction needed to make this work. ***(1 mark)*** 
- __To make the command in the step 5 work, we need to create a table first__.
```bash
@firdauz003 ➜ /workspaces/OSProject/nodejs-app (main) $ docker exec -it be05a2555eef mysql -u root -p
Enter password: 
```

- __then we will enter mysql interface__,
```bash
mysql> create database mydb;
Query OK, 1 row affected (0.03 sec)

mysql> use mydb;
Database changed
mysql> create table mytable (
    -> id INT AUTO_INCREMENT PRIMARY KEY,
    -> name VARCHAR(255) NOT NULL,
    -> value VARCHAR(255) NOT NULL
    -> );
Query OK, 0 rows affected (0.11 sec)

mysql> INSERT INTO mytable (name, value) VALUES ('example1', 'value1'), ('example2', 'value2'), ('example3', 'value3');
Query OK, 3 rows affected (0.02 sec)
Records: 3  Duplicates: 0  Warnings: 0
```

- __and then we run again the command in step 5__
```bash
curl http://localhost:3000/random
```


## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***AS STATED IN ITALEEM SYSTEM***
