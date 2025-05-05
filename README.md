# ee425-lab-5-discrete-time-series-averaging-filters-solved
**TO GET THIS SOLUTION VISIT:** [EE425 Lab 5-Discrete-time Series Averaging Filters Solved](https://www.ankitcodinghub.com/product/ee425-lab-5-discrete-time-series-averaging-filters-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95142&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE425 Lab 5-Discrete-time Series Averaging Filters Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Exp. 5: Discrete-time Series Averaging Filters

Objective: Implementation of moving average filters with application to discrete-time series.

Consider the periodic, discrete time series, x[n], shown in Figure 1, where the abscissa corresponds to a discrete-time index, while the ordinate values (in decimal number representation) are given by the marker atop each stem. Our goal in this assignment will be to implement some elementary moving average filters using the periodic time series x[n] as input. The specific tasks below have been designed to guide you through the implementation of the moving average filters.

Figure 1. One period of the time series x[n].

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Task 1

<ol>
<li>The first thing for you to do is to compile and simulate the given .asm template called “ template_for_moving_average.” For now, the variable of interest in this template is the register called value. Run a simulation of this template and use a Watch window to monitor the content of this register. Note that, as the simulation runs through the code, the values of the value register correspond exactly to those of the time series x[n] shown in Figure 1. In short, x[n]= value, where the contents of the value register will evolve in time as the code is executed in the simulator. Make sure to set the Animation Step Time of the simulator to a setting that is appropriate for you to be able to see the evolution of the values of x[n], it should be evident to you that x[n] is indeed periodic..</li>
<li>Study the given template code and note that the contents of value are being retrieved, using the TABLAT pointer, from data stored originally in the PIC’s program memory. This is something that I did not cover in class, but don’t worry, you do not need to understand the PIC’s TABLAT mechanism in order to complete this assignment. Thus, by studying the code, I mean that you should try to get a sense of what the entire code is doing (through simulations, of course) and make sure that you read all the comments that I wrote there so that you know where to start writing your code later on.</li>
<li>Do not proceed any further in this assignment until you have completed this Task. Please take step 2 very seriously and email me if something isn’t clear.</li>
</ol>
Note that Task 1 does not have anything to do with filters, yet. Task 2

The idea behind a moving average filter may be easily understood via an example. Consider again the time series x[n] from before, which is now given in Table 1 below, where n is the discrete-time index.

Note that the ellipses (…) in the table mean time continuation, and not missing data.

n … 0 1 2 3 4 5 6 7 8 9 10 11 …

x[n] … 50 0 50 100 150 200 250 200 150 100 50 0 … Table 1. Periodic discrete-time series x[n].

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
We want to convolve this time series with the trivial moving average filter given by the following difference equation.

y[n]= x[n]+ x[n−1]

Note how this simple equation just says that the output, y[n], is simply calculated, for each n, as the average of two values of x[n] at consecutive time indices, namely, n and n-1. In other words, you take x[n] (the current data value), add it to x[n-1] (the previous data value), and finally divide the resulting sum by two. All of this is shown in Table 2 below.

</div>
</div>
<div class="layoutArea">
<div class="column">
n -1 0 1 2 3 4 5 6 7 8 9 10 x[n]10050 0 5010015020025020015010050 y[n] … 75 25 25 75 125 175 225 225 175 125 75

</div>
<div class="column">
11 … 0 … 25 …

</div>
</div>
<div class="layoutArea">
<div class="column">
Table 2. Periodic time series x[n] and y[n].

Let us illustrate the idea above with another simple example corresponding to the following difference

equation.

z[n]= x[n]+ x[n−2]

Now try to convince yourself that the output z[n] corresponding to this new moving average filter should

be as in Table 3.

n -1 0 1 2 3 4 5 6 7 8 9 10 11 … x[n] 100 50 0 50 100 150 200 250 200 150 100 50 0 … z[n] … 100 50 50 50 100 150 200 200 200 150 100 50 …

Table 3. Periodic time series x[n] and z[n].

As an exercise, and to prepare you for what is to come later, please generate the output table for each of the following difference equations. You may need to extend the tables to allow for higher time indices in order to show the output correctly. Please include each table in your report. Each table should look similar to either Table 2 or 3.

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
a[n] = x[n] + x[n − 3] b[n] = x[n] + x[n − 4] c[n]= x[n]+ x[n−5]

</div>
</div>
<div class="layoutArea">
<div class="column">
Task 3

</div>
</div>
<div class="layoutArea">
<div class="column">
Now we finally arrive at the part of this assignment where you get to implement the moving average filters on the PIC using assembly language.

First, consider again the filter y[n] above, and note that in order to calculate the output we need to know x[n] at time indices t=n and t=n-1, and because of this we call y[n] a first-order filter. This should be clear from the equation for y[n]. Similarly, for the other filter, z[n], in order to compute the output for z[n] we need to know x[n] at time indices t=n and t=n-2. Thus z[n] is a second-order filter. It is important that you understand what is really going on behind the scenes with the filter z[n], so we discuss it in more detail in the following paragraph.

We have seen that in order to compute the output for z[n], at each time index, we need to know x[n] at time indices t=n and t=n-2. This means that the following sequential steps are executed as the time index increases..

<ol>
<li>To compute z[0], we need x[0] and x[-2].</li>
<li>To compute z[1], we need x[1] and x[-1].</li>
<li>To compute z[2], we need x[2] and x[0].</li>
<li>To compute z[3], we need x[3] and x[1].</li>
<li>…</li>
<li>This algorithm simply continues ad infinitum.</li>
</ol>
Note how, in step 1 above, we needed x[0] and x[-2] to compute z[0]. This is clear from the equation for z[n]. But, in doing so, what happened with the data with time index t = -1 which lies between x[0] and x[- 2], namely x[-1]? Did we discard it or throw it away? Well, we cannot simply forget about it or throw it away because, if you look at step 2 above, we will need x[-1] in order to compute z[1]. (Can you see

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
that?) If we continue this process, as step 6 indicates, then you will notice that at every time index during which the filter z[n] is acting upon the data x[n], we need to have saved, somewhere in our computer memory, the data corresponding to three consecutive time indices. That is, we need to have saved x[n] at indices t=n, n-1, and n-2. Note, however, that at each time index, the output z[n] only requires two out of the three consecutive values that we have saved in our memory. Let us call this allocated section in our computer memory, made up of only three data variables, a memory buffer. As the time series evolves in time, our memory buffer must be updated with the (three) appropriate consecutive values so that our filter produces the correct average output at each time index. It may help you to revisit Tables 2 and 3 above with this new understanding that you have to create a memory buffer.

Now, consider the more general formula for an averaging filter. d[n]= x[n]+ x[n−k]

Armed with our understanding of z[n], we can see that in order to be able to implement this more general filter, d[n], properly, we need to create a memory buffer which contains k variables. Now, there are two different memory buffers that we can use: a linear buffer and a circular buffer. Since we will be concerned with moving average filters of low order, it will be sufficient to focus on implementing a linear buffer. In order to know what the differences between these two buffers are, please take a look at the following website: https://www.allaboutcircuits.com/technical-articles/circular-buffer-a-critical-element-of-digital- signal-pro cessors/

You should pay particularly close attention to the discussion surrounding Figure 3 from that reference.

Your task now is to read up on the linear buffer details in the reference provided above and, finally, to implement the filter y[n] shown above. Below are some guidelines to help you do this. Also. please read the comments in the .asm provided to you in order to see where the code for this assignment should be written. The two main parts that you have to figure out for this are as follows:

1. Implementation of the linear buffer.

<ol>
<li>This should be done in a separate subroutine of its own.</li>
<li>You will need to create several variables for you to save data into. Hint: for y[n] your
buffer needs to be three variables long.
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
c. The discrete-time series data, x[n], to be saved in the buffer will be retrieved from the value register discussed in step 1 of Task 1 above. In other words, the input to your filter, y[n], will be the data x[n] = value, where the contents of the value register will evolve in time as the code is executed in the simulator.

<ol start="2">
<li>Arithmetical computations.
<ol>
<li>Note that the data from the value register is eight bits long.</li>
<li>y[n] requires the sum of two variables and then a division by two. In this setting of fixed-point arithmetic, it can be shown that these two operations are not commutative. Therefore, in order to achieve the full dynamic range of the filter, you need to add the data values first, and then divide the sum by two at the end.</li>
<li>An understanding of the carry bit inside the STATUS register will be crucial in this part. Take a look at my Lecture 0 slides, the book or the PIC datasheet for more details about the carry bit and the STATUS register.</li>
</ol>
</li>
<li>You must simulate your code and make sure that it produces the data corresponding to y[n] shown in Table 2 above.</li>
<li>The following instructions from the instruction set may be useful when implementing this moving average filter.
a. movff b. movf c. addwf d. rrcf e. andlw
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
Task 4

Having completed Task 3, please write the .asm code to implement the other moving average filters specified above, namely, z[n], a[b], b[n], and c[n].

<ol>
<li>Please generate separate .asm files for each filter. (Yes, I expect five (5) different .asm files.)</li>
<li>Note that once you figure out Task 3, then Task 4 becomes a simple extension of your work. If it doesn’t seem to you like that is the case, then you should go back to Task 3 and make sure that you have a thorough understanding of that Task before you attempt this Task 4.</li>
</ol>
</div>
</div>
</div>
