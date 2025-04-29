# cs330---assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [CS330 – Assignment 4 Solved](https://www.ankitcodinghub.com/product/cs330-assignment-4-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115627&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS330 - Assignment 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
CS330: Operating Systems

For this task, please refer to the code template and helper routines provided in part-1 folder and go through the README file carefully. In this task, a file is passed as input which is chucked into blocks of 64bytes and a hash is calculated for every block. An output array is used to store the calculated hash values of corresponding blocks. A serial implementation is provided in the provided code which does not work correctly when executed with more than one threads. Your task is to modify the hashit function in thread func.c to make it work correctly with more than one threads. Note that, the calculate and store hash function should be invoked without holding any locks. To test your program, you can use any existing file on your system. (see README)

A read-write lock allows multiple readers but one writer to enter the critical section. Refer to the slide#9 – #15 in https://www.cse.iitk.ac.in/users/deba/cs330/producer-consumer. pdf for details and an example implementation using semaphores. For this task, please refer to the code template and helper routines provided in part-2 folder and read the README file carefully.

The proposed RWLOCK uses a single 64-bit long integer. One of the ways to implement a read-write lock using a single variable is to use the single variable in an innovative manner as explained below.

Value at the bit position 47 plays a crucial role in determining the state of the lock as explained below,

Value 0x1000000000000 –&gt; unlocked

0x0000000000000 –&gt; locked for writing

0xFFFFFFFFFFFF –&gt; one reader

1

0xFFFFFFFFFFFE –&gt; two readers

…..

In the template code and helper files, you are provided with the implementation for atomic add (see common.h). The val argument can be negative. This function returns 0, 1 and -1 if the result of atomic add is zero, positive and negative, respectively. Implement the template functions in rwlock.c. A sample main program is also provided to test basic correctness (in main.c). However, you should use your own test programs to validate the lock implementation.

Submission guidelines

• The assignment is to be done individually. You have to submit only three files (thread func.c (part-1), rwlock.c (part-2) and parallel hash.c (part-3)). Put these three files in a directory named with your roll number. Create a zip archive of the directory and upload in canvas.

• Don’t modify any other files. We will not consider any file other than the above mentioned files for evaluation.

• You should remove all printf debug statements from submission files. We will taking diff of your output and expected output for evaluation.

In-case of any issues you should reach out to us at the earliest. All the best!

2
