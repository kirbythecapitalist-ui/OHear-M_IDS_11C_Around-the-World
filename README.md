The rubric said "While a test problem may have 4 travel trips to calculate distances travelled, your app only needs to go from one point to another, 
and then be reset for the next leg of the journey. Screen(s) will need to accept multiple inputs and output a numeric distance." 
However, my "app" waits until the coordinates of all 3 destinations are given, and then calculates them all at once. Typing in a new set of coordinates will automatically clear the old ones.
All 3 buttons do the exact same thing, but there's three of them because I'm cool like that.
Music was oriinally supposed to autoplay, but browsers block autoplay without user interaction. So then I tried to use mouse movement as the user interaction
(so that it would essentially function as an autoplay) but apparently that method was blocked by browsers too. 
So now there's a button you click to play the audio. Yay. It really hurts the atmosphere, but oh well :[
If you use DMS make sure to use the proper symbols, and include a zero with the appropriate symbol in the absence of any degree, minute, or second value.
And the direcion; (N,S,E,W) the four diaganols should work too. If it detects a W it'll add a negative to the the longitude, and S does the same thing for latitude.
There is code to check for commas instead of the symbols, but it don't work and I'm feeling lazy today.
The bounds of both latitude and longitude are negative to positive 180. 
If a higher/lower value is entered, the distance will still be calculated properly, but you'll fly off the edge of the world.

Sincerly,
Michael O'Hear
