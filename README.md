1. Initial array: [8, 3, 1, 7, 4]
2. Start with the second element (3). It's the arr[i] element.
   - Compare it with the first element (8).
   - Swap them to get [3, 8, 1, 7, 4].

3. Move to the third element (1). It's the arr[i] element.
   - Compare it with the second element (8).
   - Swap them to get [3, 1, 8, 7, 4].
   - Now, compare it with the first element (3).
   - Swap them to get [1, 3, 8, 7, 4].

4. Move to the fourth element (7). It's the arr[i] element.
   - Compare it with the third element (8).
   - Swap them to get [1, 3, 7, 8, 4].
   - Now, compare it with the second element (3).
   - Result: [1, 3, 7, 8, 4].

5. Move to the fifth element (4). It's the arr[i] element.
   - Compare it with the fourth element (8).
   - Swap them to get [1, 3, 7, 4, 8].
   - Now, compare it with the third element (7).
   - Swap them to get [1, 3, 4, 7, 8].
   - Continue swapping until it reaches the correct position.
   - Result: [1, 3, 4, 7, 8].
