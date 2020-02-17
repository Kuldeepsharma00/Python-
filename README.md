# Python-
This repository is meant for python coding 
# num = 1634
#
# # Changed num variable to string,
# # and calculated the length (number of digits)
# order = len(str(num))
#
# # initialize sum
# sum = 0
#
# # find the sum of the cube of each digit
# a = num
# while a > 0:
#    digit = a % 10
#    sum += digit ** order
#    a //= 10
#
# # display the result
# if num == sum:
#    print(num,"is an Armstrong number")
# else:
#     print("Its not a armstrong number")
#
# #how to find a even and odd  number
#
# xy = int(input("Enter the number : "))
# if (xy % 2) == 0:
#     print("The no. is even")
# else:
#     print("The no. is odd")
#
# # Guess the no. game
# Guss_no = 9
# Number_attempt = 3
# Guess_count = 0
# while Guess_count < Number_attempt:
#     Guess = int(input("Guess no : "))
#     Guess_count += 1
#
#     if Guess == Guss_no:
#         print("You won")
#         break
#
# else:
#     print("try again")
#
# abc = 'this is the first time i am revesing a string using command promt'
# aaa= '1234567890'
#
# print(len(abc))
# i = len(abc) -1
# op = ''
#
# while i >=0:
#
#     op = op + abc[i]
#     i = i-1
#
# print(op)
# #Wip to reverse a string by slicing
# string= input('enter the string:')
# output = string[::-1]
# output1 = string[::1]
# print(output)
# print(output1)
#
# #WAP to reverse the order of words in the string.
# s= 'python is easy to learn'
# l = s.split(' ')
# print(l)
#
# len1 = print(len(l))
# outpt = l[:: -1]
# print(outpt)
# secondList=[]
#
# i  = len(l) - 1
#
# while i>= 0:
#     secondList.append(l[i])
#     i = i - 1
#
# outpt1= '  '.join(secondList)
# print(outpt1)
#
# fiout= ' '.join(outpt)
# print(fiout)
#
#
# firstList = [1,2,3]
# secondList=[]
#
# counter = len(firstList)-1
#
# while counter >= 0:
#     secondList.append(firstList[counter])
#     counter -= 1
# print(secondList)
#
# s = input ('Enter the string: ')
# print(len (s))
# s1 = ''
# i = len(s)-1
# while i >=0:
#     s1 = s1 + s[i]
#     i -=1
# #print(s1)
# s2 = s1.split()
# s3 = s2[::-1]
# #print(s3)
# s4 = '  '.join(s3)
# print(s4)
#
# i = len(s4)-1
# s5 =s4 [::-1]
# print(s5)
# s6 = []
# while i >=0:
#     s6.append(s4[i])
# print(s6)
#
# #wap to print respective alphatbets in middle of string
# strng1 = 'ab cd ef gh ij kl mn op qr st uv wx yz'
# print(strng1)
# s2 = strng1.split()
# print(s2)

# loc = "this is for sharp only and is manufacterd in japan :)tttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttttt"
# print(len(loc))

# s = 'the quick brown fox jumps over the lazy dog'
# s = input ('Enter some string : ')

# print(len(s))
# i = len(s) -1
# s1 = " "
# while i >=0:
#     s1 = s1 +s[i]
#     i = i-1
# print(s1)
# s2 = s1.split()
# print(s2)
# s3 = s2[::-1]
# print(s3)
# s4 = ' '.join(s3)
# print(s4)
# print(s)
#
# l = s.split()
# print(l)
# i = 0
# l1 = []
# while i <len(l):
#     if i % 2 == 0:
#         l1.append(l[i])
#     else:
#         l1.append(l[i][::-1])
#     i = i+1
# i = 1
# while i <len(l):
#     if i % 2 == 0:
#         l1.append(l[i])
#     else:
#         l1.append(l[i][::-1])
#     i = i+1
# print(l1)
# s1= 'the quick brown fox jumps over the lazy dog'
# l = s1.split()
# print(l)


# i = len(s1)-1
# # output = " "
# while i >=0:
#     output = output + s1[i]
#     i= i - 1
# print(output)
# l1 = s1.split()
# i = 0
# print('The list of words at even positon is :')
#
# while i<len(l):
#         print(l[i])
#         i = i+2
#
# i = 1
# print('The words at odd positon are:')
# while i<len(l):
#         print(l[i])
#         i = i+2
#
# print('The words present at even place', l[0::2])
# print('The words present at odd index:', l[1::2])


# i = 1
# while i<len(l1):
#     if i % 2 == 0:
#         l2.append(l1[i])
#
#     i = i +1
# print('the list of words at odd place :')
# print(l2)
#
# s = 'kuldeep'
# i = len(s)-1
# op = ''
# while i>= 0:
#     op = op + s[i]
#     i = i-1
# print(op)
# s1 = s[::-1]
# print(s1)
#
# s2 = reversed(s)
# output = ''.join(s2)
# print(output)
#
# s = 'the quick brown fox jumps over the lazy dog'
# l = s.split()
# print(l)
# l1 = l[::-1]
# print(l1)
# l2 = ' '.join(l1)
# print(l2)

# 2nd word reversing
# we need to print reverse numbers present at odd position
# l3 = []
# for word in l1:
#     l3.append([word][::-1])
# i = i+1
# print(l3)
import numbers

s = 'my name is kuldeep and i work in sharp'
l = s.split()
i = len(s) - 1
op = ''
while i >= 0:
    op = op + s[i]
    i = i - 1
print(op)
# by using slice operator
s1 = s[::-1]
print(s1)
# by using reversed function
s1 = reversed(s)
s2 = ''.join(reversed(s))
print(s2)

# exchanging the strings
print(l)
l1 = l[::-1]
print(l1)

# internal content of a string
i = len([l1]) - 1
l2 = []
for word in l1:
    l2.append(l1[i][::-1])
    i += 1
print(l2)

# revering a second string of the list
l3 = []
i = 0
while i < len(l):
    if i % 2 == 0:
        l3.append(l[i])
    else:
        l3.append(l[i][::-1])
    i = i + 1
print(l3)

# WAP TO ARRANGE ALPHANUMERIC INTO SEPERATLY

AN = '1qq123r67hnmfg2143247879fgfg '
# an1 =AN.split()
# i = len(an1)-1
digit = []
alpha = []
for number in AN:
    if number.isalpha():
        alpha.append(number)
    else:
        digit.append(number)

print(alpha)

print(digit)
output = ' '.join(sorted(alpha) + sorted(digit))
print(output)

'''
Write a program to print a4b3c2--> aaaabbbcc
2. Write a program to print a3z2b4 --> aaabbbbzz
3. WAP to print -- input - >aaaabbbcc o/p- a4b3c2
'''
s = 'a4b3c2'
i = len(s) - 1
output = ''
for ch in s:
    if ch.isalpha():
        x = ch
    else:
        d = int(ch)
        output = output + str(x) * d
print(output)
s = 'a3z2b4'
output = ''
for ch in s:
    if ch.isalpha():
        x = ch
    else:
        d = int(ch)
        output = output + x * d
print(sorted(output))
output1 = ' '.join(sorted(output))
print(output1)
x = '*'
for i in range(10):
    print(x * i)
    i = i + 1
"""
input = aaaabbbbccczzz
output =a4b4c3z3
"""
s = 'aaaabbbccz'
op = ' '
pre = s[0]
c = 1
i = 1
while i < len(s):
    if s[i] == pre:
        c = c + 1
    else:
        op = op + str(c) + pre
        pre = s[i]
        c = 1

    if i == len(s) - 1:
        op = op + str(c) + pre
    i = i + 1

print(op)

s = 'i am a caner patient and working is sharp'
l = s.split()
i = len(l) - 1
l1 = []
for word in l:
    if i % 2 == 0:
        l1.append(word)
    else:
        l1.append(word[::-1])
    i = i + 1
print(l1)
'''
input = a4k3b2
output = aeknbd
'''
chr(ord(ch) + 3)

s = 'a4k3b2'
i = len(s) - 1
op = ' '
for ch in s:
    if ch.isalpha():
        x = ch
        op = op + ch
    else:
        d = int(ch)
        newc = chr(ord(x) + d)
        op = op + newc

print(op)

'''
to remove duplicate in a list
1. using empty list 
2. using empty string 
3. using set  
'''
s = 'aaabbzzccedefgghiijaakllmn'
s1 = set(s)
op = ''.join(s1)  # using set
print(op)

op = ''
for ch in s:
    if ch not in op:  # empty string
        op = op + ch
print(op)

'''
wap to couunt no. of occunces of character in a string 
'''
s = 'AAANNABBABRTEKKLLOPOIUY'
l = []  # empty list
for ch in s:
    if ch not in l:
        l.append(ch)
print(l)
for ch in l:
    print('{} occurs {} times'.format(ch, s.count(ch)))
'''s = input ('enter the string : ')
op = []
for ch in s:
    if ch not in op:
        op.append(ch)
print(op)
for ch in sorted(op):
    print('{} is present {} times '.format(ch,s.count(ch)))'''

# Same program with help of set:
s = 'aaabrrbbccccdddeeeaaa'
s1 = set(s)
for ch in sorted(s1):
    print('{}  IS PRESENT {} times'.format(ch, s.count(ch)))

# KEY AND VALUES METHOD
s = 'AAAAAAAAAAABBBBBEEEEEEEEEXXDEIITTHDPOIUYT'
d = {}
d['a'] = 100
d['b'] = 200
d['a'] = 300
print(d)
print(d.get('a', 330))
print(d.get('z', 30))

d['a'] = d.get('a', 0) + 2
print(d)

s = 'AAAAAAAAAAABBBBBEEEEEEEEEXXDEIITTHDPOIUYTSSAAA'
d = {}
for ch in s:
    d[ch] = d.get(ch, 0) + 1
print(d)
for k, v in d.items():
    print('{} occurs {} times'.format(k, v))
print(sorted(d))

# name = input ('Enter the name :')
# print('hello {}'.format(name))
# age= input('age is : ')
# age_months = int(age)*12
# print (age_months)

# age = int(input("Enter your age: "))
# side_job = True
# print(age > 18 and age < 65 or side_job)

nearby_people = {'Rolf', 'Jen', 'Anna'}
user_friends = set()  # This is an empty set, like {}

user_friends.add('Rolf')
user_friends.add('Anna')
s1 = user_friends.intersection(nearby_people)
print(s1)
# Add the name to number of element in a strin
# s = 'aaaabcaaad'
# d = {}
# for ch in s:
#
#     d[ch] = d.get(ch , 0) +1
# print(d)

lottery_numbers = {13, 21, 22, 5, 8}
players = [  # we can use tuple also in place of list
    {'name': 'kul','numbers': {1, 3, 8, 22, 21}},
    {'name': 'Jose','numbers': {4, 9, 10, 12, 15, 13}},
    {'name': 'jyoti','numbers': {1, 3, 5, 8, 9, 11, 13}}
]

name = players[0]['name']
xyx = players[0]['numbers'].intersection(lottery_numbers)
print('players {name} has apperead {bcd} times'.format(name=name, bcd=len(xyx)))

name = players[1]['name']
numbers = players[1]['numbers'].intersection(lottery_numbers)
print('player {name} has appeared {bcd} times.'.format(name=name, bcd=len(numbers)))

name = players[2]['name']
# number = players.get(numbers, 0 )
number1 = players[2]['numbers'].intersection(lottery_numbers)
print('player {name} has appeared {bcd} times.'.format(name=name, bcd=len(number1)))

n = 4
for i in range(n):
    print(' ' * (n - i - 1) + (str(i + 1) + ' ') * (i + 1))

list = [1, 2, 6, 7]
list1 = [2, 3, 4, 7, 8, 9]
list2 = list + list1
print(sorted(list2))
total = sum(list2)
print(total)

# use_ip = input('enter p or q ')
# while use_ip != 'q':
#     if use_ip == 'p':
#         print('hello world')
#

numbers = [

    {'alpha': 'one', 'digit': 1},
    {'alpha': 'two', 'digit': 2},
    {'alpha': 'three', 'digit': 3},
    {'alpha': 'four', 'digit': 4},
]

for num in numbers:
    x = num['alpha']
    y = num['digit']
    print(f"{x} means {y}")

import random

lottery_number = set(random.sample(range(22), 6))

print(lottery_number)
player = [
    {'name': 'A',

     'number': {1, 3, 5, 7, 9, 11}
     },
    {
        'name': 'B',
        'number': {2, 7, 9, 22, 10, 5}
    },
    {
        'name': 'C',
        'number': {13, 14, 15, 16, 17, 18}
    },

    {
        'name': 'D',
        'number': {1, 0, 9, 99, 31, 51}

    },
]
winner = player[0]
for play in player:
    count = len(play['number'].intersection(lottery_number))
    print(count)
    if count > len(winner['number'].intersection(lottery_number)):
        winner = play
print(winner)
prize = 10 ** len(winner['number'].intersection(lottery_number))
print('{} won {}. '.format(winner['name'], prize))

s = 'the quick quick '
d = {}
for ch in s:
    d[ch] = d.get(ch, 0) + 1
print(d)
for k, v in d.items():
    print('{} is {}'.format(k, v))
print (d)
s=  'My name is kuldeep' 
print(s)

