# arSort
# a library for lazy people who are too lazy to write their own sorting
## there are sorting:
+ ### 1 bubble sorting
```py
import arSort

array = [0, 6, 8, 4]
sort = arSort.Sort(array)

print(sort.bubbleSort("<")) #bubble sorting from smaller to larger
print(sort.bubbleSort(">")) #bubble sorting of more to less
```
#### input:
```
[0, 4, 6, 8]
[8, 6, 4, 0]
```

+ ### 2 sorting by shaker
```py
import arSort

array = [0, 6, 8, 4]
sort = arSort.Sort(array)

print(sort.shakerSort("<")) #sorting the shaker from smaller to larger
print(sort.shakerSort(">")) #sorting the shaker from bigger to smaller
```
#### input:
```
[0, 4, 6, 8]
[8, 6, 4, 0]
```

+ ### 3 sorting comb
```py
import arSort

array = [0, 6, 8, 4]
sort = arSort.Sort(array)

print(sort.hairbrushSort("<")) #sorting with a comb from smaller to larger
print(sort.hairbrushSort(">")) #sorting with a comb from more to less
```
#### input:
```
[0, 4, 6, 8]
[8, 6, 4, 0]
```
+ ### 4 sorting by inserts
```py
import arSort

array = [0, 6, 8, 4]
sort = arSort.Sort(array)

print(sort.insertsSort("<")) #sorting by inserts from smaller to larger
print(sort.insertsSort(">")) #sorting by inserts from larger to smaller
```
#### input:
```
[0, 4, 6, 8]
[8, 6, 4, 0]
```

+ ### 5 sorting dwarves
```py
import arSort

array = [0, 6, 8, 4]
sort = arSort.Sort(array)

print(sort.dwarvesSort("<")) #sorting dwarves from smaller to larger
print(sort.dwarvesSort(">")) #sorting dwarves from bigger to smaller
```
#### input:
```
[0, 4, 6, 8]
[8, 6, 4, 0]
```

+ ### 6 sorting the bongo clown (insane)
```py
import arSort

array = [0, 6, 8, 4]
sort = arSort.Sort(array)

#we strongly advise against doing this, 
#because the worst indicator of the time of this sorting is infinity of seconds.
print(sort.bogoSort("<")) #sorting the bongo clown from smaller to larger
print(sort.bogoSort(">")) #sorting the bongo clown from bigger to smaller
```
#### input:
```
[0, 4, 6, 8]
[8, 6, 4, 0]
```
