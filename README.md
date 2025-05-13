# comp2421-project-1-solved
**TO GET THIS SOLUTION VISIT:** [COMP2421 Project 1 Solved](https://www.ankitcodinghub.com/product/comp2421-project-1-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94185&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP2421 Project 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this project, you will implement a system, that is based on Linked List, to assign passengers to various busses to help them commute based on their scheduled times.

Each student (i.e., passenger) has the following information: traveler ID (the student ID), travelling date, travelling time, from, and to (destination). Following is an example of the input file called (passengers.txt):

<pre>1190001#18042022#14:00#Birzeit#Nablus
1190112#18042022#11:00#Beit Rima#Birzeit
1190554#19042022#13:00#Birzeit#Atara
1190201#20042022#14:00#Birzeit#Ramallah
</pre>
Another file containing the registered bus lines (busses.txt) contains: a bus number, date, departure time, from, to, price of ticket, and capacity. Example of the input file:

<pre>1#18042022#14:30#Birzeit#Ramallah#6#15
2#18042022#11:45# Beit Rima#Birzeit#6#1
13#19042022#14:30# Birzeit#Atara#6#20
53#20042022#14:00#Birzeit#Nablus#6#7
</pre>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Your application should do the following:

1. Read the drivers file and load it into an array, then read the second file (passengers) which should be added to the busses in a linked list (array of linked lists). Before assigning passengers to busses you should make sure that:

<ol>
<li>Each passenger is added to a bus based on the date and departure time. Meaning, each passenger should match the bus based on his/her travelling time and the departure time of the bus</li>
<li>The length of each linked list should be decided based on the capacity of the available bus</li>
<li>If a student has no matching travelling date/time, there should be another linked list for those</li>
</ol>
Your application should be able to show the following information through a proper menu of the application:

<ol>
<li>Loadthebusinformationfile</li>
<li>Loadthepassengerinformationfile</li>
<li>Assign passengers and print assignment information of all
busses
</li>
<li>Print a specific bus information along with its passengers
information (names and IDs)
</li>
<li>Printunmatchedpassengers</li>
<li>Addnewpassenger</li>
<li>Deletepassenger</li>
<li>Delete bus number</li>
<li>Exit</li>
</ol>
Grading policy:

<ol>
<li>Yourapplicationshouldhaveallfunctionalitiesworking properly. Twenty marks will be graded for the functionality of the project;</li>
<li>The following notes will make up the remaining 10 marks of the grade:</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
a. There has to be adequate documentation and comments in the code (i.e., functions, loops, etc.);

b. Your code should follow the code convention (i.e., spaces, indentations, etc.); and

c. Your application should contain a menu to allow the user to select which option (s) he would like to run.

</div>
</div>
</div>
