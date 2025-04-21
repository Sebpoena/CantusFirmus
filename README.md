# CantusFirmus
An attempt to generate some cantus firmi, not sure whether or not it will work just yet.
The need:
-> I want to do some tests on future counterpoint solvers, and to generate music in general, but I cannot find
  resources online for digitalised cantus firmi. 

The method:
-> I will try a few different methods, first one I have already tried but yet to upload, it failed it was:
  -> using recursion algorithm, with some rules baked in, and a cadence nailed on the end.
    -> i didn't even get to the cadence part, just the rules had to be so convoluted to have it conform to 
      cantus firmus tradition, and then it would get caught in loops constantly. One would need to do a whole
      other set layers to make it less dull, and that just seems like so much work, that one may as well make
      that the whole idea, and skip the recursive middle man
  -> using overarching structure, generating a layout, then generating within that layout.
    -> haven't tried this yet, but I'm hopeful. The idea would be to have some contours, like: ascending, 
      descending, interrupted ascension/descension, wave, zigzag. On top of these, one would have a length 
      aspect, that would be pseudorandom. The other half of this, is the jumps, one could organise it so that
      after every length x a jump is aproppriate, or even to have a contour including small or large jumps.
    -> I will brainstorm some contours, and then think of how to convert them to code. I have a bit more hope 
      this idea, but I am still trying not to fully emotionally commit myself.
