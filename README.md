# Homework 0

In this homework, you are expected to:

•	Create a GitHub account and Join GitHub Classroom

•	Install Visual Studio

•	Do the homework

## GitHub Instructions
This is the invitation URL for the first assignment: https://classroom.github.com/a/HBJQikT5 Please click the URL and follow the instructions below to set up your GitHub account.
1.	When you click to the invitation, sign in page opens. If you already have a GitHub account and willing to use it for this class, please sign in with your existing account. Otherwise, create a new account by simply “Create an account” link which is located below of the “Sign In” button. If you are already signed in before clicking, continue with the second step.
2.	After signing in, Join the classroom page opens. Please find your name from the list and click. If your name is not in the list, continue by clicking “Skip to the next step” button. 
3.	Now, you need to accept the assignment. Then, GitHub will automatically create a repository for your homework.

After following the steps above, you created a GitHub account, joined the classroom and took the first assignment. You can check your own repository for the homework-0 by changing “yourname” with your GitHub account name on the following URL:
https://github.com/BUIE201-Spring2021/homework-0-yourname
For example: https://github.com/BUIE201-Spring2021/homework-0-bugracnr

In your repository, you should be able to see homework-0.sln file and homework-0 folder which contains Source.cpp in addition to the some other files. When you click Source.cpp, you must be able to see the following “Hello, World” code on your browser.



	#include<iostream>
	

	using namespace std;
	

	int main()
	{
		cout << "Hello, World" << endl;
	

		return 0;
	}


## Visual Studio Instructions
Now, you need to install Visual Studio to start the homework. The instructions for the installation are: 
1.	Open the visual studio download page: Download Visual Studio 2019 for Windows & Mac (microsoft.com) 
2.	Download Visual Studio 2019 Community edition.
3.	Run the downloaded program (vs_community__somenumbers.exe) and give the required permissions. Then, wait Visual Studio Installer to download necessary files.
4.	On the opened screen, you should only select and install “Desktop development with C++” (C++ ile masaüstü geliştirme) which is under Desktop & Mobile in Workloads tab. You are not required to do any modifications to the default installation. 
5.	The installation process will take some time. Wait the installer to download and install necessary components automatically. 

## Homework Instructions
At this step, you have a GitHub account, a repository for your first homework and a C++ IDE (integrated development environment, which is Visual Studio 2019) on your laptop. Now, you are ready to pull the codes from your repository, modify and push it back. 
1.	Run Visual Studio 2019 and select “Clone a repository”.
2.	Go to your homework-0 repository page, click the “Code” button and copy the link on the pop-up. 
3.	Paste the link to “Repository location” on Visual Studio, select a path or simply use the default path. Then, click “Clone” at the bottom right corner. 
4.	Find Source.cpp on Solution Explorer. It is located under homework-0 -> Source Files. Double click to open it. You will see the same code on the previous page.
5.	Your task is to write your name to the console. Simple edit and add the following line to the code.
	
	cout << "My name is … " << endl;
	
6.	Run your program by clicking Debug -> Start Debugging or pressing F5. If your program runs correctly, continue.  
7.	Now, you have some changes in your code. Open View->Git Changes and see that Source.cpp is located under Changes tab. To observe the changes double click Source.cpp. A screen showing the changes will be opened. Here, you can observe the line added at Step 5 is highlighted green. You should commit your changes now. First, enter a message on Git Changes window, then, click Commit All. This operation does some local changes in your computer. To push the changes to your repository, you should click the push button which is on top-right of Git Changes window. 
8.	After pushing the changes, check Source.cpp on your GitHub repository to see the changes that you have made. 


 



