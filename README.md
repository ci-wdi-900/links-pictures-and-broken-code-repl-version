# Links, Pictures, and Broken Things

There are 5 tags that are wrong in some way in this page. They're written incorrectly, or only half there, or missing entirely, or just the wrong tag. Let's see if you can fix them!

### Setup And Workflow

1. Log into REPL.it if you aren't already.
2.

### "Serving" Your Page

"Serving" on the web means telling a computer called a "server" to send certain files on request. In this case, we inform the server to make our REPL's HTML file (and all the files it links to) the default file when the browser checks the result. Then, when the REPL app loads the result, it starts loading them from the current `index.html` file, and puts the result next to your code.

How do you do this? Just hit the "Run" button, or, **better yet**, hit Command-Enter (Control-Enter on Windows and Linux).

### So Why Isn't REPL Serving My Code?

**The top-most bug in this code is producing fully invalid HTML**, breaking the entire page. It's in the `title` tag, and if you don't see it, look at some examples of `title` tag usage online!

Fortunately, once you fix this one, none of the other bugs should give you that issue. They'll only breeak their own tag, not the whole page. Which is good, because fixing system-breaking bugs like this is awfully hard if nothing tells you where it is!

### Good Luck

And happy bug hunting!
