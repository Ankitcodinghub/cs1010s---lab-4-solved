# cs1010s---lab-4-solved
**TO GET THIS SOLUTION VISIT:** [CS1010S – Lab 4 Solved](https://www.ankitcodinghub.com/product/cs1010s-lab-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115079&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1010S - Lab 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Using the Visual Studio Code Debugger

Introduction

Obtaining the files

1. Obtain the zip file for the lab from Coursemology. You will be given a similar zip file for the PE.

2. Extract the contents of the zip file to a directory, e.g. Desktop or Documents.

• For Mac, double clicking the zip file will extract the contents to the current folder.

• For Windows, double clicking will open a window to examine the zip file. You will have to drag the folder out to extract the contents.

You should now see a folder called lab04 containing at least two files: lab04.cpp and lab04.code-workspace .

Note for MacOS

To disable SIP:

1. Restart your Mac into Recovery mode, by holding down + R from when it restarts until you see the Apple icon and a progress bar.

2. From the Utilities menus, select Terminal.

3. At the terminal prompt, type csrutil disable exactly and press Enter. The terminal should display a message saying that SIP was disabled.

4. From the Apple menu, select Restart.

SIP can be re-enabled by following the same steps, but entering csrutil enable instead.

Starting Visual Studio Code

lab04.cpp

lab04.code-workspace

Normally you will open the file using Visual Studio Code. But in order to use the debugger, you will instead open the file using Visual Studio Code instead.

1

If double-clicking on the file does not work, simply select File from the menu in Visual Studio Code, and Open Workspace… and open the file.

You should see the lab04.cpp file open for editing in VS Code:

Running the debugger

Switch the left pane to the debugger by clicking on the icon. At the top you should see a Run button, with two options: Debug for MAC and Debug for Windows.

Click on the appropriate option. These configurations should work if you had followed the setup given in Problem Set 0. Otherwise, you might have to modify them yourself.

Your code will be compiled and run, and the execution should be paused with the very first step highlighted.

The debugging view

The left pane shows the memory state of the program at the current step. On the code pane, the current instruction to be executed is highlighted. Since the variables are not yet initialized, we see they contain random values in memory.

Somewhere at the top there is a controls bar (that can be repositioned by dragging). Mouse over the buttons will reveal that they are Continue, Step Over (F10), Step Into (F11), Step Out (Shift+F11), Restart and Stop.

1. Click or press the Step over icon in the debugging control panel. This will advance the program execution by one step. You should see that the variables have been correctly initialized.

2. Now the next line to be executed is function call to sort . If you were to click Step over button again, the execution will “step over” that line by performing the function call without pausing. Try it.

You will notice that the variables did not change at all after the function call. Something must be wrong in the function.

3. So restart the debugger and come back to the previous step. This time, click or press Step into the function call.

Notice that the execution is now at the sort function and our variables are now replaced with the inputs a , b and c .

4. Now use the Step over or Step into buttons to control the execution of the program and view the memory state changes.

5. If you do not want to continue tracing through a function, or you stepped into a function in the C++ standard library, you can return using two ways. The first is to press Step out to continue execution until it steps out of the current function. The second is to put a breakpoint on a line of code and press Continue. The program will execute until it hits a breakpoint.

6. To put a breakpoint, click on the left of the line number of the line where you want the execution to pause. A red circle should appear, indicating a breakpoint has been created.

Fixing the code

There are some mistakes (bugs) in this code. Now try using the debugger to find what is wrong and fix it.
