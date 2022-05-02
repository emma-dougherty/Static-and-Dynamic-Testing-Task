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


  def check_for_ace(self, card):
    if card.value = 1:
      return True
    else
      return False
   
# On line 21 it should be '=='. There is a semicolon missing after else. Also, it does not appear that 'card' has been initialised as a constructor of the class CardGame.


  dif highest_card(self, card1 card2):
  if card1.value > card2.value:
    return card
  else:
    return card2

#'dif' instead of 'def'. A comma missing after 'card1' on line 29. Lines 30-33 are not indented correctly. It should state 'return card1', not 'card', on line 31.  


def cards_total(self, cards):
  total
  for card in cards:
    total += card.value
    return "You have a total of" + total
# The indentation is not correct, it should all be one space to the right. 'total' has not been defined. Assuing that it would be defined as total = 0, the return line would have to be changed as it is not possible to concatenate a string and integer in that way. It should be changed to f"You have a total of {total}". Lastly, line 42 should be indented back one space to the left, i.e. out of the loop, otherwise it will only count the total of a single card.
```
