# LockableStorage

Concurrency and locking for HTML5 localStorage.

# Install

    bower install lockablestorage
    
# Use

    LockableStorage.lock('key', function () {
        // exclusive access to localStorage['key']
    });

# Author

This code was written by [Benjamin Dumke-von der Ehe](http://balpha.de/) and described in this post: [http://balpha.de/2012/03/javascript-concurrency-and-locking-the-html5-localstorage/](http://balpha.de/2012/03/javascript-concurrency-and-locking-the-html5-localstorage/).

All I did was wrap it in AMD stuff and make it available as a Bower package.
