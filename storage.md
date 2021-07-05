# Local storage

> localStorage is a type of web storage that allows JavaScript sites and apps to store and access data right in the browser with no expiration date. This means the data stored in the browser will persist even after the browser window has been closed.

Historically, native applications have had an advantage because they can store data locally in a number of ways.

Web applications have used cookies for storage, which can store a small amount of information, but are innefficient because you need to transfer them frequently.

There have been advances over the years with a variety of technoologies that allows web apps to store data locally on the clientside, with varying degrees of success.

One of HTML5's goals was to create a uniform API to address clientside storage issues in a consistent user experience.

## HTML5 storage

`window.localstorage` will allow JS access to storage on the browser.

Storage is in the form of key-value paits, where the key is a string, and the value can be of any type. However the value is typically stored as a string so you will need to parse it back into the correct data format.

You can use bracket notation or the `setItem()` method to store data:

```js
window.localStorage.setItem("key", value);

window.localStorage["key"] = value;
```

Similarly, to retrieve data:

```js

var value = window.localStorage.getItem("key");

value = window.localStorage["key"];
```

### userDate
The userData behavior, according to microsoft, persists information across sessions by writing to a UserData store. This provides a data structure that is more dynamic and has a greater capacity than cookies.