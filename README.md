# toggleViewInput

Toggle input type with password for security values

## Examples

```code
toggleView.text(inputElement);
toggleView.color(inputElement);
toggleView.date(inputElement);
toggleView.datetime(inputElement);
toggleView.datetimelocal(inputElement);
toggleView.time(inputElement);
toggleView.week(inputElement);
toggleView.month(inputElement);
toggleView.tel(inputElement);
toggleView.number(inputElement);
toggleView.url(inputElement);
toggleView.email(inputElement);
toggleView.file(inputElement);
toggleView.range(inputElement);
toggleView.image(inputElement);
toggleView.hidden(inputElement);
toggleView.radio(inputElement);
toggleView.checkbox(inputElement);

/* Call Method with Event Listener */

document.getElementById("toggle").addEventListener("click", function () {
    toggleView.text("#name");
});
```