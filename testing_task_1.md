### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.
```ruby
### Testing task 2 code:

# Carry out dynamic testing on the code below.
# Correct the errors below that you spotted in task 1.

require_relative('card.rb')

class CardGame
# Error 1: Class CardGame does not match with the actual class name in the file "card.rb". We should change the class name for "Card".

  def checkforAce(card)
# Error 2: The Ruby convention for naming functions is to use underscores rather than camelcase. They should start with lowercase letter or underscores and can consist of letters, underscores and/or digits. Also, Ruby functions can end with ?, !, or =.
    if card.value = 1
      return true
    else
      return false
    end
  end

  dif highest_card(card1 card2)
  #Error 3: In Ruby, a function can be defined by starting with "def". So, we should replace "dif" in this piece of code for "def" instead.
  if card1.value > card2.value
    return card.name
  # Error 4: So, here there is an undefined method "name" (in card.name) for card. Ruby will not be able to return card.name because there has not been defined any method of name previously. In order to solve the problem, this function should return card1 instead.
  else
    card2
  end
end
end
# Error 5: The above end is closing the class Card but leaving outside of it a function that calls self.cards_total(cards). So, the end should be placed just after the last method defined for this class.


def self.cards_total(cards)
  total
# Error 6: Total is being used as variable in this function however it has not stored or set any value for it. So, at the moment, it does not have any functionality;
  for card in cards
    total += card.value
    return "You have a total of" + total
  end
end


```
