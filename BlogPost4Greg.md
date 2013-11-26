# Things I wish someone had told be about scientific computing

Brains, brains, my kingdom is full of brains. Or at least their data. When I set out on my path into neuroscience, the idea of scientific computing was not even something that came up in passing. However, with little warning, I started spending my days at the computer writing code to analyse brain data. 

 Cleaning neuroimaging data is a multi-step process and I wanted to bring out the most from the data. To do that, I thought, would require using the best bits from a slew of neuroimaging preprocessing tools. Some were better at removing extraneous noise, while others were better at image morphing. But entering the commands one-by-one was tedious and error-prone and the formats for the different functions were not always compatible. There had to be a better way. So, writing some kind of code became my only option.

Don't get me wrong, I wasn't scared by the algorithmic nature of computing. My other passion is developing statistical methods. But doing math and writing code are different beasts. Just using '=' as an assignment operator felt foreign and strange. 

I'm still slow and I might not know every trick in the book, but I can now do matrix programming in several languages in addition to stringing existing code together. Yet, I wish I had talked to someone more knowledgeable when I started my programming journey. Ultimately, it would have saved me a lot of time and struggle. So, here are a few things I learned along the way that I thought would be helpful to someone brand-new to programming:

## Good code takes good planning
When I started, I thought that automating my data preprocessing would solve all my data problems. "Just find some way to automatically run the commands", I thought, "then everything will be just right". But, in the world of neuroimaging, _just right_ is a matter of opinion. Why use tools that weren't expressly built to go together? What makes that better than sticking with one software suite? What is better? I couldn't answer these questions using my code.

Oh no, I thought. Writing code is just as tough as designing the whole study, only I have to design a new study every day! That's when I found something that really helped--*unit testing*. Writing the tests before writing my code really helped me operationalize the problem.  It made sure that my code ran without breaking, and, more importantly, forced me to think about what did I mean by better and how was I going to test betterness. It not only made me a faster programmer, it helped me to be able to explain what I was doing to my colleagues. Wasn't it Einstein who said, "If I had only one hour to save the world, I would spend fifty-five minutes defining the problem, and only five minutes finding the solution"?


## Keep it simple
When I first started, I tried to write everything into one big block of code. This got to be a big problem fast. First, I was repeatedly writing the same bits of code over and over (which was what I wanted to avoid by automating the process in the first place). My code was hard to read and hard to debug. Learning to put my code into small reusable chunks was one of my biggest breakthroughs--*one job, one function*. This made my code easier to debug because, together with my tests, I could find exactly where my code wasn't working and I only needed to fix the problem in one place.

## Nobody gets it right the first time
As a part-time coder and full-time perfectionist, I soon got really frustrated that my code didn't work off the bat. What was wrong with me that I couldn't write anything that even ran, let alone worked! 


## Get it to work, then get it to work better
As a part-time coder and full-time perfectionist, I thought that good code always looked like the code that a professional developer with 20 years experience produces. Given that, I wasted hours trying to beautify perfectly good code, with no real gains in speed or functionality. It was then that one of my colleagues pointed out that if I was running the batches at night and they had finished running in the morning, did it really matter if they finished running in 2 1/2 hours instead of 3? Perhaps in some cases it does, but for my purposes it made no difference. I was wasting my time.

Now, with more experience, when I review that same code, I can easily see where I can improve performance or memory usage in a meaningful way. I'm also sure that when I revisit that code in several years, I can make it even better. That may be so, but it works and it works well.    




