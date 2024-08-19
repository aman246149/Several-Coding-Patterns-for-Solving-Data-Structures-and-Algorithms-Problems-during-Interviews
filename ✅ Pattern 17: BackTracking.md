
Backtracking used for to get all possible solutions.

```
void backtrack(arguments) {
	if (condition == true) { // Condition when we should stop our exploration.
		result.push_back(current);
		return;
	}
	for (int i = num; i <= last; i++) {
		current.push_back(i); // Choose candidate.
		backtrack(arguments); // Explore more
		current.pop_back();   // Remove candidate.
	}
}
```
**Popular Questions**

 1. [All Possible Combinations](https://www.interviewbit.com/problems/all-possible-combinations/)
 2. [Subset](https://www.interviewbit.com/problems/subset/)
 3. [Combination Sum](https://www.interviewbit.com/problems/combination-sum/)
 4. [Combination Sum 2](https://www.interviewbit.com/problems/combination-sum-ii/)
 5. [Combinations](https://www.interviewbit.com/problems/combinations/)
 6. [Subset2](https://www.interviewbit.com/problems/subsets-ii/)

**All Possible Combinations**

Input 1:

```
A = ['ab', 'cd']
```
**Example Output**  

Output 1:

```
['ac', 'ad', 'bc', 'bd']
```
CODE -- ACCORDING TO OUR PATTERN
![image](https://github.com/user-attachments/assets/f00d62aa-1a01-4080-9dfb-c872e5e6b663)


**SUBSET**
**Example Input**  

A = [1, 2, 3]

  
  
**Example Output**  

[  
 [],  
 [1],  
 [1, 2],  
 [1, 2, 3],  
 [1, 3],  
 [2],  
 [2, 3],  
 [3],  
]

![image](https://github.com/user-attachments/assets/96978d2d-5be0-4b1b-b243-507484208465)

**Combination Sum**

**Example Input**  

Input 1:

A = [2, 3]
B = 2

Input 2:

A = [2, 3, 6, 7]
B = 7

**Example Output**  

Output 1:

[ [2] ]

Output 2:

[ [2, 2, 3] , [7] ]

![image](https://github.com/user-attachments/assets/8d5d7fdd-b505-4cde-aa50-12084f495ae8)

