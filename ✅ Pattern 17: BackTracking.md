
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