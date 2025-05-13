# csf211-lab-12-c-on-linux-solved
**TO GET THIS SOLUTION VISIT:** [CSF211 Lab 12-C on Linux Solved](https://www.ankitcodinghub.com/product/csf211-lab-12-c-on-linux-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91924&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSF211 Lab 12-C on Linux Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
Programming Environment: C on Linux

Problem-1: Read the following problem and its possible solution. Since this is the last lab of the course and first lab on graphs, see the solution to understand how graphs are implemented. Then, go to implement Problem-2.

Consider a graph G = (V, E, w) – where w is an integer function on V – stored as an adjacency list. Write a best-first traversal procedure: starting at the root, pick the next vertex to be visited as one with the highest weight among the children of all vertices already visited. Given count of vertices, V, create an empty graph with adjacency list representation. The directed graph will be supplied as edge list, where each edge is represented by a pair of vertices which are integers in the range [0, V). Another function will then supply the weights to all the vertices of the graph.

Complete definition of following functions in graph.c. Write any additional functions and data structures in extras.c and extras.h. Consider driver.c as the driver program.

<ol>
<li>a) &nbsp;Graph initGraph(int V)
Return an empty V-vertices adjacency list with all relevant fields properly initialized.
</li>
<li>b) &nbsp;void printAdjacencyList(Graph g)
Print data of each vertex in a line, with following format:

&lt;vertex id&gt; &lt;tab&gt; ==&gt; &lt;adjacent vertex id 1&gt; &lt;adjacent vertex id 2&gt;
</li>
<li>c) &nbsp;void insertEdge(Graph g, unsigned int u, unsigned int v)
Add an edge in the graph between u and v.
</li>
<li>d) &nbsp;void bestFirstTraverse(Graph g)
Traverse and print the graph in best first traversal order.
</li>
</ol>
[Hint: You may implement a priority queue in extras.c and extras.h to identify the best adjacent neighbour to pick for expansion during traversal.]

</div>
</div>
<div class="layoutArea">
<div class="column">
Sample Test Case:

Input: Output: 81 65 39 89 61 85

</div>
<div class="column">
15042018 10

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
24 25 87 50 79 95 82 98 60 37 84 27 59 02

<pre>Weights: 70
Adjacency List:
</pre>
<ol start="0">
<li>0 &nbsp;(70) ==&gt; 2</li>
<li>1 &nbsp;(90) ==&gt;</li>
<li>2 &nbsp;(70) ==&gt; 7</li>
<li>3 &nbsp;(40)==&gt;7</li>
<li>4 &nbsp;(90) ==&gt;</li>
<li>5 &nbsp;(60)==&gt;9</li>
<li>6 &nbsp;(30) ==&gt; 0</li>
<li>7 &nbsp;(80) ==&gt; 9</li>
<li>8 &nbsp;(10) ==&gt; 4</li>
<li>9 &nbsp;(20)==&gt;8</li>
</ol>
</div>
<div class="column">
90 70

</div>
<div class="column">
40 90

</div>
<div class="column">
60 30 80 10 20

</div>
</div>
<div class="layoutArea">
<div class="column">
5 4 9

0

1 5

</div>
</div>
<div class="layoutArea">
<div class="column">
2 7591 5

</div>
</div>
<div class="layoutArea">
<div class="column">
Best First Traversal: 0213794568

Problem-2: Depth First Search for a Graph

Depth First Traversal (or Search) for a graph is similar to Depth First Traversal of a tree. The only catch here is, unlike trees, graphs may contain cycles, so we may come to the same node again. To avoid processing a node more than once, we use a boolean visited array.

For example, in the following graph, we start traversal from vertex 2. When we come to vertex 0, we look for all adjacent vertices of it. 2 is also an adjacent vertex of 0. If we don’t mark visited vertices, then 2 will be processed again and it will become a non-terminating process. A Depth First Traversal of the following graph is 2, 0, 1, 3.

Store the graph as an adjacency list representation and find its DFS. Modularize the code yourself.

</div>
</div>
</div>
