# csc718-midterm-solved
**TO GET THIS SOLUTION VISIT:** [CSC718 Midterm Solved](https://www.ankitcodinghub.com/product/csc718-parallel-programming-midterm-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;131899&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC718  Midterm Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
Total: 100 points

(Midterm is a take-home exam. It includes four questions. The last one is a programming assignment.

Please submit all your solutions and source code through D2L midterm Dropbox.)

1) (20 points) Binary semaphores only allow the integer to hold the values 0 and 1. However, binary semaphore are easier to implement than general semaphores. Here we demonstrate that a general semaphore can be implemented from a binary semaphore.

A structure of general semaphore is defined as below. It utilizes two binary semaphores. The binary semaphores support two functions. b_wait(s): decrements s if s&gt;0. If not, the process executing is blocked.

b_signal(s): increments s by 1 (does not change the value if s = 1). After the increment, a process waiting on s resumes its execution.

struct semaphore

{

int value; int waiting = 0;

b_semaphore queue = 0; // initialized to 0 b_semaphore mutex = 1; // initialized to 1

}

Figure 2

Two semaphore functions, wait(s) and signal(s) are given in Figure 2. However, there are three lines of code are missing. Fill the missing code in A, B, and C.

A. _______________________________

B. _______________________________

C. _______________________________

2) (24 points) Assume n pieces of work forming into a one-dimensional array (0 to n-1), p processes, and block allocation (scatters larger blocks among processes) is used. Process rank i starts from 0.

a. What is the most pieces of work any process has?

b. What is the least pieces of work any process has?

c. How many processes have the most pieces of work?

d. What is the first element controlled by process i?

e. What is the last element controlled by process i?

f. Which process will have the control on element j?

3) (36 points) Programming Assignment: The value of the definite integral

1 4

2𝑑𝑑𝑥𝑥 0 1+𝑥𝑥

is π . We can use numerical integration to compute π by approximating the area under the curve. A simple way to do this is called the rectangle rule (Figure 4.7). We divide the interval [0, 1] into k subintervals of equal size. We find the height of the curve at the midpoint of each of these subintervals. With these heights we can construct k rectangles. The area of the rectangles approximates the area under the curve. As k increases, the accuracy of the estimate also increases.

A C program that uses the rectangle rule to approximate π appears in Figure 4.8. The source code, pi.c, can be found in the class website. You can compile and run the program in Linux.

Figure 4.8 A C program to compute the value of π using the rectangle rule.

a. (10 points) Let INTERVALS=1000000, what is pi? Show your calculation result.

b. (16 points) The program can be converted to a multithread program. A sample program, mthpi.c, has been provided as below. There are two lines, A and B, which are incomplete. Fill the blanks and complete the program.

ptharg[i].low = _____________A__________________; ptharg[i].high = ____________ B__________________;

c. (10 points) Fill the missing lines in mth-pi.c. Compile and run the program. Let

INERVAL=1000000, what is pi? Is it the same value as your calculation result in a).

#include &lt;pthread.h&gt;

#include &lt;stdio.h&gt;

#define INTERVALS 1000000

#define THNUMS 3

// thread parametes

struct ThreadParams

{

int id; // id int low; // start

int high; // end

double ysum;

};

// return partial sum

#define BLOCK_LOW(id, p, n) ((id)*(n)/(p))

#define BLOCK_HIGH(id, p, n) (BLOCK_LOW((id)+1,p,n)-1)

#define BLOCK_SIZE(id, p, n) (BLOCK_HIGH(id, p, n)-BLOCK_LOW(id, p, n)+1)

// calculate pi partial sum

void *calcpi(void *arg)

{

double ysum; double xi;

int i;

struct ThreadParams *pm = (struct ThreadParams*)arg;

ysum = 0.0;

for (i = pm-&gt;low; i &lt;= pm-&gt;high; i++)

{

xi=((1.0/INTERVALS)*(i+0.5));

ysum=ysum+4.0/(1.0+xi*xi);

}

pm-&gt;ysum = ysum;

}

int main(int arc, char* argv[])

{

struct ThreadParams ptharg[THNUMS];

double area; double ysum; int i; pthread_t tid;

void *status;

// create multithreads to calculate partial sum ysum = 0.0;

for (i = 0; i &lt; THNUMS; i++)

{

ptharg[i].id = i;

ptharg[i].low = _____________A__________________; ptharg[i].high = ____________ B__________________;

if (pthread_create(&amp;tid, NULL, calcpi, (void*)&amp;ptharg[i]) != 0)

{

perror(“error creating child”); return -1;

}

pthread_join(tid, &amp;status);

}

// calculate total area area = 0;

for (i = 0; i &lt; THNUMS; i++)

{

area = area + ptharg[i].ysum;

}

area = area * (1.0/INTERVALS);

printf(“Area is %13.11f “, area);

return 0;

}

4) (20 points) Programming Assignment: Write a parallel program using MPI that computes the sum 1+2+…+p in the following manner: Each process i assigns the value i+1 to an integer, and then the processes perform a sum reduction of these values. Process 0 should print the result of the reduction. As a way of double checking the result, process 0 should also compute and print the value p(p+1)/2. Please benchmark the running time of the parallel program using the Rushmore cluster as discussed in the class.

Np=1 Np=2 Np=3 Np=4

Execution time
