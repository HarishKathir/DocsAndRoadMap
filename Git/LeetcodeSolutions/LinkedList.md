# Problems
## 61 Rotate List
- check if k is zero || head is null and head.next is null
- find the length 
- make it circular linkedlist attaching the tail next to head 
- to make k rotations , find the modulus of k and length 
- to move , n lengths , subract length and k 
- find new tail , start from head and move r rotations 
- new tail.next will be the new head 
- make newtail.next to null to break the circular LL 
- return the new head