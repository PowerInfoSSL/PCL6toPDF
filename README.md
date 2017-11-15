# PCL6toPDF
Convert PCL6 file format to PDF
______________________________________
Hi Everyone 
this program.script/siteServices can convert and manage and Log your activity about Converting PCL6 file format to PDF Format.
when a printer want to print a page or page's , almost all of printer communicate with windows by PCL Language , and this files writed by this language we cant read it directly.
by this script you have a web server and after click on the convert , all PCL File's converting to the PDF format.
Step By Step:



This program working by PaperCut Printer Analiz and management Server.
you can convert all pcl6 file in the log section of Papercut .
papercut get you a picture of one page per view to you but by this script you can get all of page of One Document in one PDF File.

1- Install prerequirement Application:


a- Download and Install "host-trap-installer"
  
b-add pcl6 file in 'bin' directory full address in your PATH Value of your System:
  
    b.1-Go to System Peroperties
    
    b.2-Click Advanced Tab
    
    b.3-Click Environment Variables
    
    b.4-In the System Variables find 'PATH' and select it and Click Edit
    
    b.5-in the end of the 'Variable Value' add this line :
    
      b.5.1- ;"[Your Computer pcl6.exe Path]"
      
  c-Download and Install Python 2.7 
  
  d- Download and Install Django
  
    d.1- Recomanded Install JetBrain and Select New Project then Select Django Project, JetBrain Automatically Install Django (Download it from Internet)
    
  e-download all of this project files 
  
  f-Edit webserver/webserver/setting.py
  
    f.1-find ALLOWED_HOST=['127.0.0.1'] and replace your computer or server IP Address with 127.0.0.1 .
  g-go to the webserver directory and run 'run.bat' test: open your browser and type [yourIPAddress:8090] you must see Login Page.
    g.1-Login User=Admin       Password: !1asdfghj
  
  *****( Before Click Convert , Paste Your PCL6 File's in document folder, all of file's converted to PDF Format and readable.)
  ScreenShots:
  
  ![PCL6](http://s9.picofile.com/file/8311835076/01_login.png)
  ![PCL6toPDF](http://s8.picofile.com/file/8311835100/02_admin.png)
  ![PCL6toPDF](http://s8.picofile.com/file/8311835118/03_main.png)
  ![PCL6toPDF](http://s8.picofile.com/file/8311835126/04_pcl6Files.png)
  ![PCL6toPDF](http://s8.picofile.com/file/8311835134/05_pcl6file.png)
  ![PCL6toPDF](http://s8.picofile.com/file/8311835142/06_convertStart.png)
  ![PCL6toPDF](http://s9.picofile.com/file/8311835176/07_convertComplate.png)
  
