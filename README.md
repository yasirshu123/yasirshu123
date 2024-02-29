import json

i = input('enter your password\n')
while (i != 'abd'):
  i = input('try again\n')
  print(i)
correct_answers = 0
a = input(
    'if you wnat to play quiz print a or you want to play MCQs print b\n')


class name:

  def __init__(self, name, age, correct_answers, percentage, grade, result):
    self.name = name
    self.age = age
    self.correct_answers = correct_answers
    self.percentage = percentage
    self.grade = grade
    self.result = result

  def __str__(self):
    return f"{self.name}({self.age}{self.correct_answers}{self.percentage}{self.grade}{self.result})"


person = name(input('what is your name\n'), input('what is your age\n'),
              correct_answers, correct_answers / 9 * 100, 'grade_here',
              'result_here')
if (a == 'a'):
  print('Welcome in quiz')
