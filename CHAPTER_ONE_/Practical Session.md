## WRITING CODES IN PYTHON 
*Now that Python has been installed, we have to check to see it properly functions .We will follow a very simple procedure .
*There are many ways of utilizing Python and to be a very good python programmer , you will have to be conversant with the ways of using python.

To start your work, you need the following tools:
* **An editor* which will support you in writing the code (it should have some special features, not available in simple tools); this dedicated editor will give you more than the standard OS equipment;
* **a console* in which you can launch your newly written code and stop it forcibly when it gets out of control;
* **a tool named a debugger**, able to launch your code step-by-step, which will allow you to inspect it at each moment of execution.

Standard Python installation comes with an application called IDLE (Integrated Development and Learning Environment).We will test our python application.

*Navigate through your OS menus, find IDLE somewhere under Python 3.x and launch it. This is what you should see:

<img width="1014" height="387" alt="Screenshot 2026-09-21 121025" src="https://github.com/user-attachments/assets/c0796970-e42a-491e-99b3-bd3e8d0ee0f3" />




*You* remember we said Python3 is an interpreter language? So with the IDLE application , we need to give it a file containing our python codes for it to execute .
* The next step is to *Click File* in the IDLE menu and *choose New file.*

<img width="1000" height="319" alt="Screenshot 2026-09-21 121930" src="https://github.com/user-attachments/assets/1af5ded3-d3df-4e75-9937-327e43529a64" />

As you can see in the image above, IDLE opens a new window for you. You can use it to write and amend your code.
This is the editor window. Its only purpose is to be a workplace in which your source code is treated.




We will  test out with our first python code. We want the IDLE to output a text ( Welcome to Akwannya Hub)
To do that , whilst still in our editor window, we type this script :
*Print(‘Welcome to Akwannya Hub’)*  
*Like below :
<img width="991" height="252" alt="Screenshot 2026-09-21 122424" src="https://github.com/user-attachments/assets/0492a943-263b-4b84-a6c1-0922a14846dd" />





Now for our IDLE to interpret or execute this our python code , we need to save it as a python file (python extension) for it to be able to execute .After saving the file , we can now run the python script and then the IDLE does its job.
* *Save the file (File -> Save) and run the program (Run -> Run Module)*
* With that , a new window will appear with the IDLE having run your script and showing you the output
* <img width="971" height="319" alt="Screenshot 2026-09-21 122341" src="https://github.com/user-attachments/assets/21e74574-7eb4-4f02-a898-2abaa36e4439" />



---


## FIXING CODES IN PYTHON

The IDLE application has an amazing feature that helps programmers to debug their code. This feature helps programmers to identify where the issue or error ] in their lines of codes where made.If the  IDLE may not recognize some characters or some formats , it will output an error, this error will indicate where the application is having a hard time interpreting .

Just like how some sentences if not constructed properly in English will not make sense , likewise the IDLE interpreter .The error message is usually in red color  like below .

<img width="1031" height="259" alt="Screenshot 2026-09-21 124225" src="https://github.com/user-attachments/assets/ae091378-adec-45a4-9415-f117496e27c7" />







As a Python programmer , you should be patient to read the error message in order to identify the underlying issue.
In this error message it says *‘prin’ is not defined .Did you mean: ‘print’* 
The IDLE has also identified that the issue is in line 1 (first line of code), showing you the exact area where the error message is.

Lets take a look at the source file to identify the error (‘prin’) in our script.
<img width="1000" height="255" alt="Screenshot 2026-09-21 124439" src="https://github.com/user-attachments/assets/7794d4e6-cbae-400a-9b77-eb1193e37a28" />

In the source file , we can see exactly where the issue is .we were able to identify the error “prin” in the first line of code .If we should correct this error  to  ‘print’ and save the file once more, run it , we will have a an error free code for the IDLE to execute .


And With That , the first module of the python programming essentials comes to an end .Introducing us to the history ,basics of programming language and Python programming preparing us for the more practical aspects of the course.


## NOTE
The next practical sessions in the other modules will be done on visual studio code.














