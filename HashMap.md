# Basics of Hash-Map & Patterns in Hash-Map Problems 

1. ### Frequency Counting
    - Pattern Overview:
        This pattern involves counting the frequency of elements in an array or a string using a hashtable. It's useful for finding duplicates or determining the most occurring element.
        
    - Use the following code  
    ```python
        # count occurence of items c in an array 
        dictionary_to_keep_count = {}
        for c in nums:
            dictionary_to_keep_count[c] = 1 + dictionary_to_keep_count.get(c,0)
    ```
2. ### Sorting dictionaries :
    - based on key 
    ```python 
        sorted_dict = dict(sorted(dict.items() key:lambda x:x[0]))
    ```
    - based on value
    ```python 
        sorted_dict =  dict(sorted(dict.items() key:lambda x:x[1]))
    ```
3. ###
