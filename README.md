# Euler-Project


## What is the goal of completing these problems?

My goal with undertaking this task is to improve my programming skills, problem-solving abilities, knowledge base of algorithms and mathematical concepts, and, most importantly, have fun.


## What is the point of uploading these problems to GitHub?

My primary reason for uploading these solutions is to document my progress with the first one-hundred Euler Project problems. While I realize a lot of these solutions are far from the most efficient, I think that it is much more important that I showcase progress in my skills and not perfection. It's easy to retrospectively change the code to be better, but as long as the code is sufficient (runs in under a minute on moderate hardware), I think that it's better to keep it as is (unless it's just egregiously bad in hindsight).


## Why are all the solutions more complicated than strictly necessary?

I figured just solving the problems was somewhat limiting and I noticed my solutions would break if just one part of the problem was tweaked, so I opted to instead put [generalizing](https://wiki.c2.com/?WhatIsGeneralization) at the forefront once I can get the answer. Most solutions to these problems are very specific and only work within the context of the respective problem, with the code needing to be manually edited and perhaps changed entirely if a single variable in the question changes, so my solutions are differentiated from the rest because of this.



## Is this allowed?

*Project Euler's Response:*
  "It appears that you have answered your own question. There is nothing quite like that "Aha!" moment when you finally beat a problem which you have been working on for some time. It is often through the best of intentions in wishing to share our insights so that others can enjoy that moment too. Sadly, that will rarely be the case for your readers. Real learning is an active process and seeing how it is done is a long way from experiencing that epiphany of discovery. Please do not deny others what you have so richly valued yourself.

  However, the rule about sharing solutions outside of Project Euler does not apply to the first one-hundred problems, as long as any discussion clearly aims to instruct methods, not just provide answers, and does not directly threaten to undermine the enjoyment of solving later problems. Problems 1 to 100 provide a wealth of helpful introductory teaching material and if you are able to respect our requirements, then we give permission for those problems and their solutions to be discussed elsewhere."



## Sieve of Eratosthenes
"Problem 010 - Summation of Primes.py", "Problem 037 - Truncatable Primes", and "Problem 046 - Goldbach's Other Conjecture.py" all utilize a Sieve of Eratosthenes implementation that very closely mirrors [this implementation](https://gist.github.com/jermenkoo/3728135) by [Jaromir Latal](https://gist.github.com/jermenkoo), as this implementation was magnitudes more efficient than the ones I originally made. The implementations also differ between the problems to increase efficiency for that particular task and vary in similarity.
