### Analysis

This algorithm uses recursion to traverse a directory and its subdirectories given its path and append the files matching the given suffix to an array. This problem use a combination of recursion and iteration over each folder, because we don't know the structure of the folder. We need to go through the entire file directory to verify each file and adding to the list if is correct.

Time complexity: O(mn) because the loop iterates over m number of sub directories, and n number of files per directory.

Space complexity: O(mn) since in the worst case, we could have n number of files to hold, and m sub directories.