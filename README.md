# beerz

## Example usage:

```ruby
the_bartender = Bartender.new("Joe")
captain_jack = Customer.new("Cpt. Jack")

the_bartender.greet(captain_jack)
the_bartender.serve(captain_jack)

# Captain Jack can drink while he has beer
while captain_jack.has_beer?
  captain_jack.drink!
  sleep 1
end

captain_jack.drink!
the_bartender.serve(captain_jack)
```

## Disclaimer:
@foxycoder said it works!

## collaborators:
 - @foxycoder
 - @yopefonic
