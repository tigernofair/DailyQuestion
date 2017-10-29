#way_1:
subscript = 0
numbers = [10, 29, 30, 41]
for number in numbers:
    print('('+str(subscript)+','+str(number)+')')
    subscript +=1

#way_2
subscript = 0
numbers = [10, 29, 30, 41]
while subscript < len(numbers):
    print('('+str(subscript)+','+str(numbers[subscript])+')')
    subscript +=1
