## Update-set1-by-adding-items-from-set2-except-common-items
## Sample code to check the Update the set 1
```sh
set1 = {10, 20, 30, 40, 50}
set2 = {30, 40, 50, 60, 70}

set1.symmetric_difference_update(set2)
print(set1)
```
## Expected Output
{70, 10, 20, 60}

