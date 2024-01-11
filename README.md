# ASK THE USER FOR THEIR NAME AND AGE. 
userName =input('Hello I\'m Chat Bot Bob, what is your name?\n')
userAge = int(input('Nice to meet you, '+userName +'. How old are you?\n'))

# ASK THE USER QUESTIONS ABOUT WHAT THEY ENJOY TO DO IN THEIR FREETIME
adultQuestions = input('What do you like to do in your free time '+userName+'?\n1. Watch TV\n2. Cook different meals\n3. Venture Outside\n4. LEAVE ME ALONE.\nEnter the number of choice: ')
if adultQuestions == '1':
  print('ooo!! Watching TV is a great way to relax after a long day! Or even just to be lazy haha!')
elif adultQuestions == '2':
  print('Yum! Cooking is a great way to get your mind off of the day and enjoy a delicious homemade meal.')
elif adultQuestions == '3':
  print('I love going outside! It\'s a great way to get some fresh air and exercise!')
else:
  print('Awe..okay, bye. :(')

