# ESBPI_MD
#01 create windows instance using AWS
1.	First user has to login to the AWS account using correct username and password.
    ![screenshot 199](https://cloud.githubusercontent.com/assets/15711984/17271755/78904792-56a2-11e6-83eb-e9cd6bc31fa4.png)


2. 	Then click “Launch Instance” button and from the list of AMI s appeared on the screen select “Microsoft Windows Server 2012 R2 Base” AMI to create windows instance.
	![screenshot 1](https://cloud.githubusercontent.com/assets/15711984/17271711/bd93c6d6-56a0-11e6-9ac6-81dfc9e7b7af.png) 

  

 3.	Select the default instance type given and click “Preview and Launch” button. 
 ![screenshot 2](https://cloud.githubusercontent.com/assets/15711984/17271722/163927ae-56a1-11e6-85d9-90c26097db3a.png)

![screenshot 3](https://cloud.githubusercontent.com/assets/15711984/17271725/4a54facc-56a1-11e6-9c04-84639c0d6fb7.png)

 

4.	Then after creating the instance next step is reviewing the instance created. Click the “Launch” button to continue. 
   ![screenshot 4](https://cloud.githubusercontent.com/assets/15711984/17271794/54ac004a-56a3-11e6-999d-783698f7ac1d.png)

5.	Next user has to create a new key pair to launch the newly created instance by providing a name to the key pair. 

![screenshot 5](https://cloud.githubusercontent.com/assets/15711984/17271806/9219226e-56a3-11e6-81aa-013fba68469a.png)

6.	Next click “Download Key pair” button to download the key pair to your system and “thanuka_reshan.pem” file will be downloaded. 
![screenshot 5](https://cloud.githubusercontent.com/assets/15711984/17271807/bdd6625e-56a3-11e6-8e4b-f9e509e00aaa.png)


7.	Then created instance will be launched as shown below and click the “View instance” button to view the instance you created. 

![screenshot 6](https://cloud.githubusercontent.com/assets/15711984/17271810/d465ddd8-56a3-11e6-9a12-5d8c9e50c70c.png)

![screenshot 7](https://cloud.githubusercontent.com/assets/15711984/17271813/ea8c6f0a-56a3-11e6-9806-7a9083be510d.png)


8. Then to connect to the instance click “Connect” button. To get connect to the instance first user should get a password. 
![screenshot 8](https://cloud.githubusercontent.com/assets/15711984/17271815/083decfe-56a4-11e6-966e-5231bc63968a.png)

 9. Next to get the password should provide the path of “Thanuka_reshan.pem” file and decrypt the password. 
 ![screenshot 9](https://cloud.githubusercontent.com/assets/15711984/17271823/50e0744a-56a4-11e6-8e83-5926cc462c4f.png)

![screenshot 11](https://cloud.githubusercontent.com/assets/15711984/17271855/21bd95de-56a5-11e6-92de-7df10d200af1.png)


10.Then user can get the password to access the instance and click “Download Remote Desktop File” button to download the file. 
![screenshot 12](https://cloud.githubusercontent.com/assets/15711984/17271860/493166c2-56a5-11e6-9639-f24dd0293dc8.png)

11.Then user can access to the created Windows instance AMI. 
![1000](https://cloud.githubusercontent.com/assets/15711984/17271867/894cfbf4-56a5-11e6-998e-e06f0a42adfd.png)

#02 Creating Linux Instance using AWS account. 
 1.	First user has to login to the AWS account and then click “Launch Instance” button and from the list of AMI s appeared on the screen select “Amazon Linux AMI 2016.03.3 (HVM)” AMI to create linux instance. 
 ![screenshot 17](https://cloud.githubusercontent.com/assets/15711984/17271902/27ab3a7c-56a6-11e6-9f07-41c3eb8bd4b0.png)

2.	Select the default instance type given and click “Preview and Launch” button. 

![screenshot 18](https://cloud.githubusercontent.com/assets/15711984/17271907/50511208-56a6-11e6-9379-2f719b408717.png)

3. Then after creating the instance next step is reviewing the instance created. Click the “Launch” button to continue. 
![screenshot 20](https://cloud.githubusercontent.com/assets/15711984/17271925/bff06686-56a6-11e6-8c77-960d33cd9b14.png)

4.Next user has to create a new key pair to launch the newly created instance by providing a name to the key pair and then click “Download Key pair” button to download the key pair to your system and “thanuka.pem” file will be downloaded. 
![screenshot 25](https://cloud.githubusercontent.com/assets/15711984/17271958/6c73a8c8-56a7-11e6-8999-0cd39c611d72.png)


5 Then created instance will be launched as shown below and click the “View instance” button to view the instance you created. 
![screenshot 26](https://cloud.githubusercontent.com/assets/15711984/17271955/6010a766-56a7-11e6-8e9b-cf26f0ec0d0d.png)

![screenshot 27](https://cloud.githubusercontent.com/assets/15711984/17271965/89cf19c0-56a7-11e6-88e9-fa8394525363.png)

6. Then download putty.exe and puttygen.exe files. 
![screenshot 28](https://cloud.githubusercontent.com/assets/15711984/17271970/a2cb28ce-56a7-11e6-98ff-891fbd81191b.png)


7. Next open the puttygen.exe file and click “Generate” button to get the putty key. Under type of key to generate, select SSH-2 RSA. 
![screenshot 40](https://cloud.githubusercontent.com/assets/15711984/17271976/e57b6ac6-56a7-11e6-8716-4b5032d31b96.png)

8.Click “Load” button and locate thanuka.pem file and click “Open”. 
![screenshot 42](https://cloud.githubusercontent.com/assets/15711984/17271978/0c40bfda-56a8-11e6-999a-95795775af78.png)

9. After generating the putty key it should be saved by clicking “Save Private Key” to use it in putty. Click “Yes” to continue and define the place where the putty key should be saved. 
![screenshot 128](https://cloud.githubusercontent.com/assets/15711984/17271983/40471536-56a8-11e6-934c-8287f9edc44b.png)

![screenshot 44](https://cloud.githubusercontent.com/assets/15711984/17271989/694548f4-56a8-11e6-818e-cb4e70fb189a.png)

10.Then open the putty.exe file to connect to the linux instance and give the public DNS as hostname and provide a name to save the creating session and click “Save”. 
![screenshot 129](https://cloud.githubusercontent.com/assets/15711984/17271997/a514e312-56a8-11e6-9508-47c65874497c.png)

11.Then go to Connection- SSH – Auth to control SSH authentication. 

![screenshot 49](https://cloud.githubusercontent.com/assets/15711984/17272012/0f0bc7ea-56a9-11e6-8751-2b7bab61cab3.png)


12.Then locate the saved private key to start the linux instance with putty. 
![screenshot 50](https://cloud.githubusercontent.com/assets/15711984/17272006/d816111e-56a8-11e6-86e2-e9a37d249d79.png)

13. Then the console will appear and user has to login as “ec2-user” to launch the Linux AMI instance.
![screenshot 56](https://cloud.githubusercontent.com/assets/15711984/17272019/3f36c3d4-56a9-11e6-885d-62e8b3ab9508.png)

![screenshot 58](https://cloud.githubusercontent.com/assets/15711984/17272020/51c6640a-56a9-11e6-8ab8-288027e4f74d.png)

#03 Create DB instance using RDS.
1. Click on RDS button
![screenshot 59](https://cloud.githubusercontent.com/assets/15711984/17272026/772711f4-56a9-11e6-849e-eff5b7344339.png)
2 Select MySql and click the select button 
![screenshot 61](https://cloud.githubusercontent.com/assets/15711984/17272033/9baa6620-56a9-11e6-833e-abd6deb0cb4c.png)
![screenshot 62](https://cloud.githubusercontent.com/assets/15711984/17272040/d79d9ee0-56a9-11e6-9713-ef9c711c2fc0.png)

3 Configure the settings given below

![screenshot 64](https://cloud.githubusercontent.com/assets/15711984/17272047/f872322a-56a9-11e6-8fc1-39089a16e6e6.png)

4 Configure the settings given below and Launch DB Instance
![screenshot 65](https://cloud.githubusercontent.com/assets/15711984/17272054/1bb6813c-56aa-11e6-9324-d758ee2d800b.png)

5. User can view the instance by clicking the “View Your DB instance” button 

![screenshot 66](https://cloud.githubusercontent.com/assets/15711984/17272057/3a414574-56aa-11e6-8587-9ff7f12bebc1.png)

6 User has to wait for few minutes.
![screenshot 67](https://cloud.githubusercontent.com/assets/15711984/17272064/5ce8b99a-56aa-11e6-8860-2ca6ab0a0854.png)
![screenshot 68](https://cloud.githubusercontent.com/assets/15711984/17272068/7bc16dda-56aa-11e6-8d93-0337085e6a9e.png)



7.Finally user can login to the DB using the given user name and the password

![screenshot 203](https://cloud.githubusercontent.com/assets/15711984/17272081/e04fb702-56aa-11e6-934b-e84749cf80e5.png)
![screenshot 204](https://cloud.githubusercontent.com/assets/15711984/17272086/f125157c-56aa-11e6-9cad-a046a29f3c21.png)
![screenshot 207](https://cloud.githubusercontent.com/assets/15711984/17272094/3abf1bf6-56ab-11e6-973b-85b53f406401.png)
![screenshot 205](https://cloud.githubusercontent.com/assets/15711984/17272095/4b4a6d36-56ab-11e6-883a-5414a7d2b7cb.png)
![screenshot 206](https://cloud.githubusercontent.com/assets/15711984/17272098/5d572f0a-56ab-11e6-9262-05aed43f0249.png)



















