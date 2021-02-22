# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS 
![local storage](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f6/WebApp_Client_Server_classical.png/220px-WebApp_Client_Server_classical.png)

- Before HTML5, all attempts to achieve this were ultimately unsatisfactory in different ways.
one of these behaviors was called userData. (userData allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure)
- In 2002, Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading name of “Flash cookies.” Within the Flash environment, the feature is properly known as Local Shared Objects. Briefly, it allows Flash objects to store up to 100 KB of data per domain.
- By 2006, with the advent of ExternalInterface in Flash 8, accessing LSOs from JavaScript became an order of magnitude easier and faster. Brad rewrote AMASS and integrated it into the popular Dojo Toolkit under the moniker dojox.storage. Flash gives each domain 100 KB of storage “for free.
- in 2007, Google launched Gears, an open source browser plugin aimed at providing additional capabilities in browsers ears provides an API to an embedded SQL database based on SQLite. Gears can store unlimited amounts of data per domain in SQL database tables

## INTRODUCING HTML5 STORAGE
![html5 storage](https://scriptverse.academy/img/tutorials/html5-webstorage.png)
Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.” The naming situation is made even more complicated by some related, similarly-named, emerging standards
so **what is HTML5 Storage?** Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server
## USING HTML5 STORAGE
![using](https://techglimpse.com/wp-content/uploads/2013/05/Pass-LocalStorage-data-to-PHP-using-jQuery.jpeg)
HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScrip

***TRACKING CHANGES TO THE HTML5 STORAGE AREA***
If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever

***HTML5 STORAGE IN ACTION***
There’s a small problem with the game: if you close the browser window mid-game, you’ll lose your progress. But with HTML5 Storage, we can save the progress locally, within the browser itself. Here is a live demonstration. Make a few moves, then close the browser tab, then re-open it. If your browser supports HTML5 Storage, the demonstration page should magically remember your exact position within the game, including the number of moves you’ve made, the position of each of the pieces on the board, and even whether a particular piece is selected


