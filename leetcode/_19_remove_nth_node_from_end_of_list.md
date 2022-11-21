# 19. Remove Nth Node From End of List

https://leetcode.com/problems/remove-nth-node-from-end-of-list/description/

Given the head of a linked list, remove the nth node from the end of the list and return its head.

# tags: LinkedList, medium
A fast pointer to find n-th node from head. If fast = None, we remove head
A slow pointer to find node before one that need to be removed. We move slow and fast pointer together 
