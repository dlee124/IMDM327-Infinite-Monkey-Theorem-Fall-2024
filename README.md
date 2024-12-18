### Infinite Monkey Theorem: 

*The infinite monkey theorem holds that a monkey given an infinite amount of time at a keyboard would ultimately type out every possible text, including the complete works of Shakespeare.*

https://github.com/user-attachments/assets/d40a3a0b-2b9a-4efe-96bc-27ee35b25a9c


To get this project to actually run in unity, will have to get the [LLMUnity](https://github.com/undreamai/LLMUnity?tab=readme-ov-file) plugin and add it to the project

## WRITEUP

If you’ve been on the internet for long enough you may have heard about a concept coined the “infinite monkey theorem”, a small theorem that states how, "A monkey hitting keys at random on a typewriter keyboard for an infinite amount of time will almost surely type or create a particular chosen text, such as the complete works of William Shakespeare." While this theorem is used mainly to explain how given an infinite amount of time, a nonzero chance of an event will eventually happen, I am more focused on the silliness of the thought of having a monkey sit at a keyboard and randomly type. The project aims to supplement the theorem, having a “monkey” randomly type keys, which can then be compared to the complete works of Shakespeare (Hamlet in this case).

In order to create a feeling of actually having some agency, I wanted to have any key the user typed be turned into a random key. I also wanted to have some small exceptions for accessibility, such as the space key, backspace, enter, and escape keys all being just their normal actions. What the monkey typed could then be entered into a large language model, which would then respond with what it believes to be an english translation of the monkey’s typing. Because the input is completely random, the responses from the model were also very unpredictable, creating a unique experience each time it is run. 

I learned mostly an implementation of llama into unity through a tutorial. It also was a small thought experiment visualized on what if complete gibberish were to be entered into a large language model, although it involved some prompt engineering because otherwise the model would respond with something along the lines of not understanding.

I hope the audience enjoyed seeing the small monkey type keys randomly, along with the silly 2 frame animations. I wanted to keep the project cohesive direction-wise, going for a somewhat absurdist cartoon feeling. 

For future improvements, I would like to add a small clicky sound whenever the user types something, or any sound at all. I also would have liked to make the original “gamification” elements more prominent, like adding a streak feature, but in practice, the occurrences of “hits” were so uncommon that I would have to find another way to implement it. I also could look more into the impossible probability aspect of the theorem, such as a small visualization of how long it would actually take to actually type a work accurately. The monkey would occasionally press a caps lock, which would turn all future keys capital until it presses it again, and a shift press does the same for just the next key, but it did just end up being unclear when it actually pressed it without something being displayed on the screen. 
