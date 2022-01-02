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
