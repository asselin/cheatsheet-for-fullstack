# cheatsheet-for-fullstack

## Javascript

Description | jQuery
--- | ---
Create a variable `elem1` | `var elem1;`
Create an empty array | `var arr = [];`
Create an empty object | `var obj = {};`


## jQuery

Description | jQuery
--- | ---
Get a reference to an element | `$("#someid")`
Create a new div | `$("<div>")`
Set the inner text | `elem.text("hello")`
Set an attribute on an element | `elem.attr("src", "http://example.com")`
Append `elem1` as the last child inside `parentElem` | `parentElem.append(elem1);`
Append `elem1` as the first child inside `parentElem` | `parentElem.prepend(elem1);`
Send a request to a server | ` $.ajax({ url: "http://example.com", method: "GET" }).then(function(response) { console.log(response); });`
Set a click handler on elements with class `button` | `$(".button").on("click", function(event) { console.log("Event:", event); console.log("DOM node:", this); });`
