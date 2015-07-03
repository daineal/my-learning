import random
full = 0
w = 0
count1 = 0 #Регулируют все диапозоны(чисел и списков)
count2 = 0
print('Welcome to Random_numbers')
n = int(input('write range of numbers'))
q = []
for i in range (n): #Это я так наполнаяю список
    full = full + 1
    q.append(full)
while w != 2: #Условие победы
    num_com = random.randint(1+count1, n+1-count2)
    print(num_com)
    quest = int(input('This? write (2), else if more or less write (1 or 0)'))
    if quest == 2:
        w = 2
    elif quest == 1:
        for i in range(n+1-count1-count2):
            if q[i+count1] >= num_com:
                q.pop(i)
                count1 =+ 1
    elif quest == 0:
        for i in range(n+1-count1-count2):
            if q[i+count1] >= num_com:
                q.pop(i)
                count2 =+ 1
print('victory!')
