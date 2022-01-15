# 30days6Companies

## DAY 1 - 6 (Goldman Sachs)

### Q1: Group Anagrams

Link : https://leetcode.com/problems/group-anagrams/

TC : (0(n*mlogm))

Intuition: we will keep a hashmap which will store at a particular key, which anagrams are equal to that key. So the key can be sorted string of the curr string. So if the current string is present in map then for the key of sorted string of curr string, we will add the curr string as a value to the key. finally we return the new list of hm.values()

### Q2: Group Anagrams

Link: https://leetcode.com/problems/rectangle-overlap/

TC: 0(1)

Intuition: if the rectangle is a line that is if x1==x2 || y1==y2 then no overlap and if the top right corner coords > bottom left cords then it has overlap and return true

### Q3: Subarray Product Less Than K

Link: https://leetcode.com/problems/subarray-product-less-than-k/

TC: 0(n)

### Q4: Run Length Encoding 

Link: https://practice.geeksforgeeks.org/viewSol.php?subId=344331c42cd25170e182609fc9d29bf5&pid=700243&user=bhelenavjyot18

TC: 0(n)

### Q7: Find the kid which gets tha damaged toy

Link: https://practice.geeksforgeeks.org/viewSol.php?subId=4e129ba390bc0447ee62c7961ef4f087&pid=704216&user=bhelenavjyot18

TC: 0(1)

Intuition: Formula based (K-1+M)%N;

### Q10 : Stickler Thief 

Link: https://practice.geeksforgeeks.org/viewSol.php?subId=69adac43dabf0956caf9cfdf72282209&pid=701417&user=bhelenavjyot18

TC: 0(n)

Intuiton: At each stage we have two choices to rob the house and not rob the house , if robbed, add curr value and if skipped then jump to next's next index and return max of those two choices

### Q11: Find Missing and Repeating number

Link: https://practice.geeksforgeeks.org/viewSol.php?subId=9c9d8c61476dee6f0bcc702835fa1c6c&pid=702678&user=bhelenavjyot18

TC: 0(n) and Space: 0(n)

Intuition: Brute force is obvious but we will have a freq array that stores the freq of each element of the array. Hence we will return an array of two elements with one missing and other repeating which have frequencies of 0 and 2 resp.

### Q12:  Find total number of Squares in a N*N chessboard

Link: https://practice.geeksforgeeks.org/viewSol.php?subId=7725cdb19fb26c8247074902bbdda44b&pid=704775&user=bhelenavjyot18

Tc: 0(n) => 0(1);

Intuition=> formula is n(n+1)(2n+1)/6

### Q14: Minimum Size Subarray Sum

Link: https://leetcode.com/problems/minimum-size-subarray-sum/

Tc: 0(n)

Intuition: Sliding window Approche


## DAY 6 - 11 (AMAZON)


### Q1: Count ways to N'th Stair(Order does not matter)

Link : https://practice.geeksforgeeks.org/viewSol.php?subId=b5321eb5d860b1ceadc03d502c1d41a9&pid=701419&user=bhelenavjyot18

TC : (0(1))

Intuition: find the ans for n=1,2,3,4,5,6,7,8,... and you will see a pattern and come up witj formula of (n/2+1);

### Q2: Nuts and Bolts Problem 

Link: https://practice.geeksforgeeks.org/viewSol.php?subId=3d3cffc32f8f9c3fb1519e8aa1548819&pid=703024&user=bhelenavjyot18

TC: 0(n) & 0(n)

Intuiton: NA


## DAY 12-17


### Q2: Prerequisite Tasks 

Link: https://practice.geeksforgeeks.org/viewSol.php?subId=9383be384508b247ffbd4aee805c6592&pid=702128&user=bhelenavjyot18

Intuiton: If cycle is present in graph then there is no way to arrange tasks based on their prerequisites else they can be

### Q3: Rotate By 90 degree

Link: https://practice.geeksforgeeks.org/viewSol.php?subId=489bcfc014f626b134704a6ba74aa027&pid=701989&user=bhelenavjyot18

TC: 0(n)

Intuition: Reverse each row and then transpose

### Q4: Spirally traversing a matrix 

Link: Leetcode 

TC: 0(N*N)

Intuition: Dry run the matrix and you will come up with an approch

### Q6: Letter Combinations of a Phone Number

Link: https://leetcode.com/problems/letter-combinations-of-a-phone-number/

TC: 0(4^n) // No of leaf nodes * height of tree => Math.pow(recursive call at each node, n) * n => Math.pow(4, n)*n


### Q11: Generate Binary Numbers 

Link: https://practice.geeksforgeeks.org/viewSol.php?subId=97127c93441c30eda3efc403a64afa9a&pid=701347&user=bhelenavjyot18

TC: 0(Nlog2N)

### Q12: 4Sum

Link: https://leetcode.com/submissions/detail/619625044/

TC: 0(N^3)

### Q13: Given a Graph of V vertices and E edges and another edge(c - d), the task is to find if the given edge is a Bridge. i.e., removing the edge disconnects the graph.

Link: https://practice.geeksforgeeks.org/viewSol.php?subId=ac3aa17ef2d374e99ad2647d11a8acbb&pid=700463&user=bhelenavjyot18

TC: 0(N+V)

Intuition: If the number of components at start is less than number of components after removing edge from c to d and d to c then c - d was an edge else not
 
