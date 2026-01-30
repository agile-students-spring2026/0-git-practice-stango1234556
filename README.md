
## Article

[**Write code that is easy to delete, not easy to extend.**](https://programmingisterrible.com/post/139222674273/write-code-that-is-easy-to-delete-not-easy-to)  
*Programming is Terrible*

## Why it stood out to me

A lot of engineering advice encourages developers to design flexible, reusable systems from the start, often emphasizing clean abstractions and code that might support future features. This article argues for almost the opposite mindset: most code doesn’t live forever, requirements change, and the best thing you can do for your future self (and your team) is write code that is **easy to remove** when it stops being useful. 

What I found most useful is how the article reframes the tradeoff between “Don’t Repeat Yourself” and code duplication. DRY encourages reusing logic through shared abstractions, while duplication means intentionally repeating similar code in different places. The article argues that the real cost isn’t repetition itself, but the dependencies that shared abstractions create. In some cases, duplicating code is actually the better choice if it keeps parts of the system independent and easier to remove later.

