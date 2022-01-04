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

