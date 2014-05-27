*************************************
Author - Mufaddal Makati			|
Website - http://www.rawbytes.com   |
*************************************
#Description -
Here is an implementation of dijkstra’s algorithm in C programming language. I have tried to document it a little.
It should work on all linux platforms. The graph.ospf file serves as an input file which contains the graph that the program will use. Make sure to put both – the source file and the graph.ospf file in the same directory. 

#How to write a graph in graph.ospf file: -
Each line stands for a single node. The format of each line is - node id:id of node it is connected to-corresponding cost:id of node it is connected to-corresponding cost:…;
Each line terminates with a ‘;’
Please note that there is no extra space or newline after the last ; of the last line.