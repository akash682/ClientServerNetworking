COLLABORATE WORK WITH SOHIL SHRESTHA
https://www.linkedin.com/in/sohilshrestha/

Following are the steps to run the code: 

1) Download the latest version of Eclispe from https://www.eclipse.org/downloads/ 

2) Unzip the project 

3) Make sure your JAVA is update date

4) In Eclipse, Go to File -> Open Project From file system 
	a)Click on directory and load the project by selecting the project folder 
	b) hit Finish

5) Expand the src. Under src, project is divided into 4 packages for each assignment questions. 

6) For Question one, go to(click on) edu.uta.distributed.singlethreaded.
	a) Open server.java . Right click on java file and Run as -> Java applications
	b) Open Client.java . Right click on java file and Run as -> Java applications
You can toggle between client and server terminal using terminal icon at bottom right. Test the program giving inputs. 
Make sure you terminate both client and server before going to next program. You can click on red square icon to terminate terminal one by one. 

7) For Question two, go to(click on) edu.uta.distributed.multithreaded package.
	a) Open server.java . Right click on java file and Run as -> Java applications
	b) Open Client.java . Right click on java file and Run as -> Java applications
The program will automatically create 30 client threads and randomly choose the client commands.  The Server terminal will display how different client request are being handled. 
Make sure you terminate both client and server before going to next program.  You can click on red square icon to terminate terminal one by one. 

8) For Question three, go to(click on) edu.uta.distributed.RPC package.
	a) Open server_RPC.java . Right click on java file and Run as -> Java applications
	b) Open Client_RPC.java . Right click on java file and Run as -> Java applications
You can toggle between client and server terminal using terminal icon at bottom right. Test the program giving inputs (1,2,3,4,5). 
Make sure you terminate both client and server before going to next program.  You can click on red square icon to terminate terminal one by one.

9) For Question three, go to(click on) edu.uta.distributed.bonus package.
	a) Open Server.java . Right click on java file and Run as -> Java applications (You dont need to run the code as it is unnecessary)
	b) Open Client.java . Right click on java file and Run as -> Java applications(You dont need to run the code as it is unnecessary)
	b) Open Helper.java . Right click on java file and Run as -> Java applications
First the helper thread will synchonize both client and server. Then You can make changes to the files in ClientFileStorage_Test folder . The helper thread will pool every 10 second and update the ServerFileStorage_Test accordingly. 

Alternatively you can run each program using java compiler from command line but it will be more tedious. Each file has to be compiled and then executed. Here is an example. 
javac server.java
java server


NOTE: Please note the program is tested on MacOSX and Windows10. It might not run on the different operating system because the file path structure is different. 

THANK YOU. 
------EOF---------


