## Longest Increasing Sequence

3,2,6,4,5,1

longest increasig sequence
[3, 4, 5] // 3
[2, 4, 5] // 3
How do you get it?
    
    exhaustive search
    - calculate all subsets of sequence and determine if subsets are increasing sequences
    - find sequence with longest length

brief algorithm

for i in n -> 1
    // can track longest size here
    for all subsequence of S with length of i
        if one increase subseqene break

max val value increase by 1

time complexity is big O

for i = 0, i < n:
    arr[i] = 1
    for j = 0, j < i-1
        