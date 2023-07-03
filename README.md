# cpanel-roundcube-webmail-mark-and-delete-with-javascript
Automatic mark and delete list of boring emails in roundcube cpanel webmail with a simple javascript

```javascript

let messagelist = document.querySelector("#messagelist");
let tbodydata = messagelist.querySelector("tbody").querySelectorAll("tr");
tbodydata.forEach((e, k) => {
    e.querySelector(".selection").click();
});
//delete
document.querySelector("#toolbar-menu").querySelector(".delete").click();

```
