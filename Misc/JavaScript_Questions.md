
* [What's the difference between call() and apply()?](http://stackoverflow.com/questions/1986896/what-is-the-difference-between-call-and-apply)
* [What's the difference between setTimeout() and setInterval()?](http://stackoverflow.com/questions/22825326/difference-between-settimeout-and-setinterval)
* Explain what a closure is and give examples of when to use them and why it makes sense (and sometimes I ask when it DOESN'T make sense).
* I usually ask some probing questions that are meant to lead to an answer along the lines of "because JavaScript is single-threaded". Tricky to ask without leading the candidate, usually I try for some sort of scenario involving a slow or locked up UI.
* Explain what prototypal inheritance is. I'm looking for an answer that indicates they generally understand how prototypes work and how inheritance with them works.
* I like to ask "if you have an object referenced by variable O, and you have another variable M that names a method of O, how do you call the method with no arguments?" The answer of course is simply O[M]() but you'd be surprised how many people don't seem to know you can do things like that (even though it's one of the things that makes JavaScript as powerful as it is).
* How do you make an AJAX call? Looking simply for XMLHttpRequest of course, bonus points if they mention anything about JSON-P or hidden iFrames or any other "hack" - some argue XMLHttpRequest is a hack itself of course :)
* What's the difference between undefined and null?
* What statement gets a reference to a DOM node by ID?
* How do you implement a Map? (all they have to say is an object is a map and I'm happy!)
* What are the implications of a large number of script tags on a page? (looking for something about performance and concurrent requests and that sort of thing)
* How do you create a multidimensional array?

**Taken from <https://www.reddit.com/r/javascript/comments/1jw96t/what_are_your_vanilla_javascript_knowledge/>**