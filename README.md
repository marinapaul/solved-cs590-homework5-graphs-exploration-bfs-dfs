Download Link: https://assignmentchef.com/product/solved-cs590-homework5-graphs-exploration-bfs-dfs
<br>



<ol start="2">

 <li>Provide an implementation in C++ of the DFS, and BFS algorithms. You are given a class declaration in the header file <em>graph.h</em>, which you should implement in <em>graph.cpp</em>. You should strictly implement the method signatures provided in the header file. As you will see in the skeleton code provided, an Adjacency Matrix representation is used for the graphs. We assume that nodes are represented with unique IDs that are integer values starting from 0 to match the indexes in the Adjacency Matrix. You are also given a test case for each algorithm in <em>main.cpp. </em>You can implement additional test cases for testing purposes, but you don’t have to submit a modified main.cpp. Your submission should run successfully using the main method provided.</li>

</ol>




Regarding the output of your code, you don’t need to store the distance attribute for BFS, or the discovery and finishing times for DFS. For both algorithms the only required output is the following: whenever you visit a node of the graph, print the node ID using a <em>cout</em> instruction to show the sequence that the nodes are visited.




In order to modify your implementation compared to the pseudocode provided in the lecture notes, you are asked to use a C++ set to keep track of the visited nodes instead of coloring the nodes. This is a good opportunity to familiarize yourselves with C++ sets if you haven’t used it before.




Remarks:

<ul>

 <li>You are not allowed to use code from online resources. Your submission will be tested against that, and will receive a 0, and a report to the Graduate Academic Integrity Board if it is detected.</li>

 <li>You can use containers from the C++ Std library.</li>

 <li>A Makefile is provided to build the code in the Virtual Box.</li>

 <li>Your code has to compile, and will be graded on the Virtual Box.</li>

 <li>The programming, and testing will take some time. Start early.</li>

 <li>Your report has to be typed, and submitted in a pdf file.</li>

 <li>Feel free to use the provided source code for your implementation. You have to document your code.</li>

</ul>


