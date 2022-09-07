import random

print("Welcome to rock/paper/scissors/lizard/spock, Human!\n")

comp = random.choice(['rock','paper','scissors','lizard','spock'])
user = input(" CHOOSE WISELY: ")

print(" You chose: ", user)
print(" I chose: ", comp)
print()

if user == comp:
  print("It's a TIE >_<")

if user == 'rock':
  if comp == 'paper':
    print(" paper covers rock, I Win! ")
  elif comp == 'scissors':
    print(" rock crushes scissors, You Win!")
  elif comp == 'spock':
    print(" spock vaporizes rock, I Win! ")
  elif comp == 'lizard':
    print(" rock crushes lizard, You Win!")

if user == 'paper':
  if comp == 'rock':
    print(" paper covers rock, You Win! ")
  elif comp == 'scissors':
    print(" scissors cut paper, I Win!")
  elif comp == 'spock':
    print(" paper disproves spock, You Win! ")
  elif comp == 'lizard':
    print(" lizard eats paper, I Win!")

if user == 'scissors':
  if comp == 'rock':
    print(" rock smashes scissors, I Win! ")
  elif comp == 'paper':
    print(" scissors cut paper, You Win!")
  elif comp == 'spock':
    print(" spock smashes scissors, I Win! ")
  elif comp == 'lizard':
    print(" scissors decapitates lizard, You Win!")

if user == 'lizard':
  if comp == 'rock':
    print(" rock crushes lizard, I Win! ")
  elif comp == 'paper':
    print(" lizard eats paper, You Win!")
  elif comp == 'spock':
    print(" lizard poisons spock, You Win! ")
  elif comp == 'scissors':
    print(" scissors decapitates lizard, I Win!")

if user == 'spock':
  if comp == 'rock':
    print(" spock vaporizes rock, You Win! ")
  elif comp == 'paper':
    print(" paper disproves spock, I Win!")
  elif comp == 'lizard':
    print(" lizard poisons spock, I Win! ")
  elif comp == 'scissors':
    print(" spock smashes scissors, You Win!")

