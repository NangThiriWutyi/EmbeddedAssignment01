def if_function(condition, true_result, false_result):

    if condition:
        return true_result
    else:
        return false_result

# Test cases
print(if_function(True, 2, 3))              # Output: 2
print(if_function(False, 2, 3))             # Output: 3
print(if_function(3 == 2, 3 + 2, 3 - 2))    # Output: 1
print(if_function(3 > 2, 3 + 2, 3 - 2))     # Output: 5
