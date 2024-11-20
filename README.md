# INSTALLING AND RUNNING APPLICATIONS ON ANDROID STUDIO DATE

## Step 1 
System Requirements
The required tools to develop Android applications are open source and can be downloaded from the Web. Following is the list of software you will need before you start your Android application programming.
Java JDK5 or later version
Java Runtime Environment (JRE) 6Android Studio

## Step 2 
Setup Android Studio

Android Studio is the official IDE for android application development.It works based on IntelliJ IDEA, You can download the latest version of android studio from Android Studio 2.2 Download, If you are new to installing Android Studio on windows,you will find a file, which is named as android-studio-bundle-143.3101438-windows.exe.So just download and run on windows machine according to android studio wizard guideline.
If you are installing Android Studio on Mac or Linux, You can download the latest version from Android Studio Mac Download,or Android Studio Linux Download, check the instructions provided along with the downloaded file for Mac OS and Linux. This tutorial will consider that you are going to setup your environment on Windows machine having Windows 8.1 operating system. Installation So let's launch Android Studio.exe,Make sure before launch Android Studio, Our Machine should required installed Java JDK. To install Java JDK,take a references of Android environment setup

![image](https://github.com/user-attachments/assets/0c572354-c5fa-4ac8-97a5-b0cca2288187)

Once you launched Android Studio, its time to mention JDK7 path or later version in androidstudio installer.

![image](https://github.com/user-attachments/assets/a5e6a98f-0cf8-461e-916d-dccd2a01ab27)

Below the image initiating JDK to android SDK

![image](https://github.com/user-attachments/assets/bb61c4a8-0cd4-4d22-9862-befd51568234)


Need to check the components, which are required to create applications, below the image hasselected Android Studio, Android SDK, Android Virtual Machine and performance(Intel chip).

![image](https://github.com/user-attachments/assets/cfe6d822-f980-4dd5-a406-88b6d95ba982)

Need to specify the location of local machine path for Android studio and Android SDK, below the image has taken default location of windows 8.1 x64 bit architecture.

![image](https://github.com/user-attachments/assets/b1a797c7-2f7a-4fc2-9813-a07947913d1a)

Need to specify the ram space for Android emulator by default it would take 512MB of localmachine RAM.

![image](https://github.com/user-attachments/assets/b93dd921-f639-465d-a6fa-833baed02170)

At final stage, it would extract SDK packages into our local machine, it would take a while time to finish the task and would take 2626MB of Hard disk space.

![image](https://github.com/user-attachments/assets/494ee43e-7368-416f-9344-6b40571b75cf)

After done all above steps perfectly, you must get finish button and it gonna be open androidstudio project with Welcome to android studio message as shown below

![image](https://github.com/user-attachments/assets/131f98e4-e6a6-4efc-a187-23e431f9830a)

You can start your application development by calling start a new android studio project. in a new installation frame should ask Application name, package information and location of the project.

![image](https://github.com/user-attachments/assets/981d5ebb-d46b-4b2a-9979-b8bdf806cec2)

After entered application name, it going to be called select the form factors your application runson, here need to specify Minimum SDK, in our tutorial, I have declared as API23: Android 6.0(Mashmallow)

![image](https://github.com/user-attachments/assets/ec5b8e27-1e6e-4b57-8681-a67ea8851988)


The next level of installation should contain selecting the activity to mobile, it specifies the default layout for Applications

![image](https://github.com/user-attachments/assets/f3325bae-3a28-4d91-b716-da168df086ed)

At the final stage it going to be open development tool to write the application code.

![image](https://github.com/user-attachments/assets/39143bbe-2f9e-4409-b33e-36fd658bd2f9)

## Step 3 
Create Android Virtual Device
To test your Android applications, you will need a virtual Android device. So before we start writing our code, let us create an Android virtual device. Launch Android AVD Manager Clicking AVD_Manager icon as shown below
![image](https://github.com/user-attachments/assets/b074a0cf-e03f-4026-aa58-50f56d884a97)

After Click on a virtual device icon, it going to be shown by default virtual devices which are present on your SDK, or else need to create a virtual device by clicking Create new Virtual device button
![image](https://github.com/user-attachments/assets/671c840b-ba20-43e0-ad9b-48fe4dfe23e2)


If your AVD is created successfully it means your environment is ready for Android application development. If you like, you can close this window using top-right cross button. Better you re- start your machine and once you are done with this last step, you are ready to proceed for your first Android example but before that we will see few more important concepts related to AndroidApplication Development.
