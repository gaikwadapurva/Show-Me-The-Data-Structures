### Analysis for union method

This algorithm uses the set data structure which enables us to store unique nodes from the given input linked lists by traversing each linked list only once. 

The resulting set is then used to create union linked list. If the union linked list is empty then there is no union between the two lists.

Time complexity: The time complexity is linear O(n) because we traverse through every node from 1 to n which results in a running time that grows directly in proportion to n where n is the number of nodes.

Space complexity: The space complexity is linear O(n) where n is the input size because the size of the underlying set data structure scales proportionally to the size of the input


#### Analysis for intersection method

This algorithm uses the two set data structures which enable us to store unique nodes from each of the given input linked lists by traversing each linked list only once. 

We then find the intersection of the two sets. The resulting set is then used to create an intersection linked list. If the union linked list is empty then there is no union between the two lists. 

Time complexity: The time complexity is linear O(n) because we traverse through every node from 1 to n which results in a running time that grows directly in proportion to n where n is the number of nodes.

Space complexity: The space complexity is linear O(n) where n is the input size because the size of the underlying set data structure scales proportionally to the size of the input.