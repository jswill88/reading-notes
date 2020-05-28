# Local Storage

## The Past, Present, and Future of Local Storage for Web Applications
* What we want with local storage is storage is space on the client end that persist beyond page refreshes and the storgae isn't transmitted to the server
* HTML5 storage became the solution to these problems after many years of new ideas
* HTML5 storage is a way for pages to store key value pairs in the browser, even after leaving the site
* Access storage through the `localStorage` object in JS
* You store and retrieve data with a named key
* Save an item with `setItem()` and retreive an item with `getItem()`
* You can you squarebracket notation instead, putting the keyword in the square brackets
* Remove a key with `removeItem()`
* Trapping a storage event works the same as trapping other events.
* The `handle_storage` callback function is called with a `StorageEvent` object
* Each origin has 5MB of default storage space
* Data is stored as strings
* IndexedDB exposes an object store, but it is unavailable to work with at the moment


