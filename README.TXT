27. Yes

28. The fill method resets the state array to zero

29. Yes, different patterns will emerge. The patterns are deterministic and the same starting state will always produce the same pattern.

31. Using nextState makes sure all cells update based on the old state.

32. You can keep the values left, center, and right in variables rather than using a second array. 
However, using nextState is much clearer and easier to use, as it separates the different states explicitly.

35. State depends on the three binary values: left, center, and right. Each combination can produce 0 or 1
 as the next state, so there are 2^8 possibilities, which equals 256.