# 100 Days Of Code - Log

### Day 1: March 28, 2019

**Today's Progress**: Updated some issues on my portfolio, completed CSS Grid on FCC, started a tribute page based on the Drifter from Destiny, and started making plans for a twitter bot.

**Thoughts:** CSS is a challenge for me. After going through the Grid course on FCC, I realized I've always made it hard for myself. I'm going to study some more css grid usage in my spare time. I also put together the boilerplate for my tribute page project on FCC. I put together some images and I'm in the process of writing out all of the info. As much as I hate to admit it, programming and web development doesn't mean just lots of hacking, it also means I'll have to actually write things which is why I've decided to do the 100 Days of Code Challenge again. 

My goal is to code at least an hour, but I want to shoot for more than an hour. I just hope I don't burn myself out.

**Links to work:** 
    *[Drifter Tribute Project](https://github.com/TwiggyTwixter/drifter-tribute) (Not live yet)
    *[Portfolio](https://jazzjones.io)(live)

### Day 2: March 29, 2019

**Today's Progress**: At work, (a non coding job) I created Excel macros to improve efficiency in my workflow.

**Thoughts**: I created some macros that save files, formats file names, and close and open Microsoft applications. I'm counting this as my day of code because it was still problem solving and code, even if it was just VBA. No working on webpages because the CSS burned me out and I was pretty burned out from working on VBA code.

### Day 3: March 30, 2019

**Today's Progress**: At work, (a non coding job) I documented the new macros I made for the coworkers to integrate into their own workflow as well.

**Thoughts**: Documenting is just as important (or even more important) as actually writing out code and solving the problem. Without good documentation, you could come back to it months from now and have to decipher some esoteric looking functions, or someone else might be interested in the code but won't be able to decipher what it actually does. I found this little exercise pretty fun actually. It allowed me to fully gather my thoughts on what the code does and how to explain it to someone else.

When I got home I coded for another couple of hours, this time on my gw2 app. State management is a beast and I wanted to refactor the code. I want to clear up the functions that are collecting the state to update the top level application state. The more complex this is growing I can see that this isn't the best pattern as some components are now needing state from other components to function.This (pun intended) has in fact turned into an anti-pattern. I finally get why people say manual state management is a pain in React. Using a state management library like redux would clear up this mess, but the prospect of adding a whole other library doesn't sound exciting for me. 

I know nothing of redux outside of the fact that it is used for state, and that the owner is part of the Facebook React development team. Guess I'm going to start learning this this library before the end of the night lol.

**Links to Work:**
    [gw2 project](https://github.com/TwiggyTwixter/gw2-app/tree/react commit: 324523b783f7d948599ba40cde7e64a3c3adff38)

### Day 4: March 31, 2019

**Today's Progress**: Reviewed Redux docs and watched Dan Abramov's tutorials while taking detailed notes, set up redux in my GW2 app.

**Thoughts**: The more I read about redux, the more I realized I was thinking about state management in a complex way. Yeah no wonder my code looks like spaghetti. I took some pretty good notes and thought about the different pieces of state my application was needing. Right now my current setup has different functions that grab component state to set the application level state. The code is too long, there is a lot of repeating and it's just not working. Redux will help me make it a lot easier and cut down on a lot of repeating code. I've been reading articles and blog posts all day while digesting redux docs, so for my act of code today I set up the boilerplate redux code. Tonight I'll drift off to sleep thinking about the different components I have and what state will be needed in my app.

**Update**: I ended up doing more than just adding boilerplate. I refactored the app so it was no longer a class, added redux and redux devtools (which was a pain to tool correctly because of literally a single character out of place (eye roll)). I was able to hook up the redux store to the token component and update the state after a click event. I started refactoring the toons component but I was having trouble wrapping my head around conditional rendering using redux. I'm too tired to think more on it as it is 10:15 PM. So all in all I ended up coding for about 3 hours tonight give or take.

**Links to Work**:
    [gw2 project](https://github.com/TwiggyTwixter/gw2-app/tree/react commit: f4ed983fa47959c00e6fa4e01c6fd03c31ae2505)