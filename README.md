# 26_sort_and_sorted
difference between sort() and sorted() 

# sorted():
'sorted is used for str,list,tuple,set and dictionaries'
sorted() method sorts the given sequence as well as set and dictionary(which is not a sequence) either in ascending order or in descending order(does unicode comparison for string char by char) and always returns the a sorted list. This method doesn’t effect the original sequence.
# Syntax: sorted(iteraable, key, reverse=False)affect
# ex:
a=[5,6,2,2,6,3,31,6,9]
print(sorted(a,reverse=True))#[31, 9, 6, 6, 6, 5, 3, 2, 2]
print(sorted(a))#[2, 2, 3, 5, 6, 6, 6, 9, 31]
# sort():
'only used for list'
sort() function is very similar to sorted() but unlike sorted it returns nothing and makes changes to the original sequence. Moreover, sort() is a method of list class and can only be used with lists.
# Syntax: List_name.sort(key, reverse=False)
# ex:
a=[5,6,2,2,6,3,31,6,9]
a.sort(reverse=True)#[31, 9, 6, 6, 6, 5, 3, 2, 2]
a.sort()#[2, 2, 3, 5, 6, 6, 6, 9, 31]
print(a)
