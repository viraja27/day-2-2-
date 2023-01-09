# day-2-2
list=[]
for i in range(1,10):
    list.append(i)
print("first three numbers in the list are",list[0:3])    
print("middle three numbers in the list are",list[3:6])    
print("last three numbers in the list are",list[6:10])    
my_pizza=['cheese','veggie','meat']
friend_pizza=my_pizza[:]#to create two diff lists
print(my_pizza)
print(friend_pizza)
my_pizza.append('bbq')
friend_pizza.append('italian')
print("my favourite pizzas are",my_pizza)
print("my friends favourite pizzas are",friend_pizza)
friend1_pizza=my_pizza#to copy same into another list
friend1_pizza.append('buffallo')
print(my_pizza)
print(friend1_pizza)
