# Read Write Code Book

This github repository is the companion site to the book.

https://readwritecodebook.com


## How to deploy

To deploy to github

    git push origin master

To deploy to the web server

    git push web master


Script I use to create git repo on server that checks out latest update on push using this workflow

https://gist.github.com/jkeesh/b19058c6c52f35fb88397037f451a27d


## Running locally

- You can just open the index.html pages in a web browser
- Since some of the chapter pages fetch other pages you can run a python server

To run the server, in the terminal:

    python -m http.server 8080

Then visit

    http://localhost:8080/


## Other notes

- To keep this web page simple, it is just HTML, CSS, JS, no build system
- To handle template includes just for repeated navigation on chapter pages, I use this html trick:

https://www.filamentgroup.com/lab/html-includes/

https://css-tricks.com/the-simplest-ways-to-handle-html-includes/


