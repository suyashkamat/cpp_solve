EXPLANATION

Maintain a head and a tail pointer on the merged linked list.

Then choose the head of the merged linked list by comparing the first node of both linked lists.

For all subsequent nodes in both lists, you choose the smaller current node and link it to the tail of the merged list, and moving the current pointer of that list one step forward.

You keep doing this while there are some remaining elements in both the lists.

If there are still some elements in only one of the lists, you link this remaining list to the tail of the merged list.

Initially, the merged linked list is NULL.

Compare the value of the first two nodes and make the node with the smaller value the head node of the merged linked list.

Since it’s the first and only node in the merged list, it will also be the tail.

Then move head1 one step forward.

Time Complexity O(n+m)