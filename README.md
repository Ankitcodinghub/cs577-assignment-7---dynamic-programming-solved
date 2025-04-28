# cs577-assignment-7---dynamic-programming-solved
**TO GET THIS SOLUTION VISIT:** [CS577 Assignment 7 – Dynamic Programming Solved](https://www.ankitcodinghub.com/product/cs577-solved-8/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120368&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS577 Assignment 7 – Dynamic Programming Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Answer the questions in the boxes provided on the question sheets. If you run out of room for an answer, add a page to the end of the document.

Dynamic Programming

Do NOT write pseudocode when describing your dynamic programs. Rather give the Bellman Equation, describe the matrix, its axis and how to derive the desired solution from it.

1. Kleinberg, Jon. Algorithm Design (p.313 q.2).

Suppose you are managing a consulting team and each week you have to choose a job for them to undertake. The set of possible jobs is divided into 2 categories of jobs: low-stress jobs and high-stress jobs.

(a) Show that the following algorithm does not correctly solve this problem.

Algorithm: JobSequence

II O a j v ja j

(b) Give an efficient algorithm that takes in the sequences L and H and outputs the value of the optimal solution. Prove that your algorithm is correct.

2. Kleinberg, Jon. Algorithm Design (p.315 q.4).

Suppose you’re running a small consulting company. You have clients in New York and clients in San Francisco. Each month you can be physically located in either New York or San Francisco, and the overall operating costs depend on the demands of your clients in a given month.

(a) Give an example of an instance where it is optimal to move at least 3 times. Explain where and why the optimal must move.

(c) Give an efficient algorithm that takes in the sequences N and S and outputs the value of the optimal solution. Prove that your algorithm is correct.

3. Kleinberg, Jon. Algorithm Design (p.333, q.26).

Consider the following inventory problem. You are running a company that sells trucks and predictions tell you the quantity of sales to expect over the next n months. Let di denote the number of sales you expect in month i. We’ll assume that all sales happen at the beginning of the month, and trucks that are not sold are stored until the beginning of the next month. You can store at most s trucks, and it costs c to store a single truck for a month. You receive shipments of trucks by placing orders for them, and there is a fixed ordering fee k each time you place an order (regardless of the number of trucks you order). You start out with no trucks. The problem is to design an algorithm that decides how to place orders so that you satisfy all the demands {di}, and minimize the costs. In summary:

• There are two parts to the cost: (1) storage cost of c for every truck on hand; and (2) ordering fees of k for every order placed.

• In each month, you need enough trucks to satisfy the demand di, but the number left over after satisfying the demand for the month should not exceed the inventory limit s.

Give an algorithm that solves this problem in time that is polynomial in n and s. Prove that the algorithm is optimal.

4. Implement the optimal algorithm for Weighted Interval Scheduling (for a definition of the problem, see the slides on Canvas) in either C, C++, C#, Java, or Python. Be efficient and implement it in O(n2) time, where n is the number of jobs. We saw this problem previously in HW3 Q2a, where we saw that there was no optimal greedy heuristic.

The input will start with an positive integer, giving the number of instances that follow. For each instance, there will be a positive integer, giving the number of jobs. For each job, there will be a trio of positive integers i, j and k, where i &lt; j, and i is the start time, j is the end time, and k is the weight. A sample input is the following:

2

14 b 2

1 4 5 Ia

3

1 2 1

3 4 2

2 6 4

For each instance, your program should output the total weight of the intervals scheduled on a separate line. Each output line should be terminated by a newline. The correct output to the sample input would be:

5

5
