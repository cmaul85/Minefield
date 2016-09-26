# BUG LOG

##Field::isSafe
 
- Does not throw and exception if location is out of bounds or invalid unless Field::get function is called on the location.

##Field::revealAdjacent

- Needs to have inBounds result inverted with !

