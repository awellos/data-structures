#data-structures
#creating a list called my_list
from typing import OrderedDict


my_list =[]
#appending items to the list
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
#adding a value to the second position in the list
my_list.insert(1,15)
#extending my_list 
my_list.extend([50,60,70])
#removing thelast element from my_list
del my_list[-1]
#sorting my_list in ascending Order
my_list.sort()
#finding and printing index of 30
print(my_list.index(30))
