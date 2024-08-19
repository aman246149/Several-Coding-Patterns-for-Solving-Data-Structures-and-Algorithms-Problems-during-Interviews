
Backtracking used for to get all possible solutions.

```
void backtrack(arguments) {
	if (condition == true) { // Condition when we should stop our exploration.
		result.push_back(current);
		return;
	}
	for (int i = num; i <= last; i++) {
		current.push_back(i); // Explore candidate.
		backtrack(arguments);
		current.pop_back();   // Abandon candidate.
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
