How It Works:
The function initializes an empty dictionary called hashmap. This dictionary will store numbers as keys and their corresponding indices as values.

The function then iterates through each number in nums using a for loop.

For each number at index i, it calculates the complement, which is the difference between the target and the current number (nums[i]).

The function checks if the complement is already in the hashmap. If it is, this means that the complement and the current number add up to the target, so the function returns the indices of these two numbers.

If the complement is not found in the hashmap, the current number (nums[i]) is added to the hashmap with its index as the value.

The process continues until the pair is found, and the function returns their indices.

Time and Space Complexity:
Time Complexity: O(n) - The function traverses the list once, performing constant-time operations in each iteration.
Space Complexity: O(n) - The space used by the hashmap grows linearly with the size of the input list nums.
