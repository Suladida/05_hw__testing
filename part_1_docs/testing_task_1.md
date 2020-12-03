### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:

# No def __init__()? 

  def check_for_ace(self, card):
    if card.value = 1: #should be ==?
      return True
    else # Missing colon
      return False
   
# dif should be def
  dif highest_card(self, card1 card2): # missing comma between cards
  if card1.value > card2.value: # incorrect indents
    return card # what is card
  else:
    return card2
  


def cards_total(self, cards):
  total # this isn't doing anything. Have to define it.
  for card in cards:
    total += card.value
    return "You have a total of" + total #won't work. return needs to unindented to be in line with "for". Total isn't anything. No spacing in string that would allow string and total to join up together properly. 
  
``` 