# Incorrect Element Selection in HTML

This repository demonstrates a common but subtle error in JavaScript when interacting with HTML elements using `document.getElementById`.  The example shows an attempt to directly select a nested `<p>` element within a `<div>` using the ID of the div.  This approach is incorrect and will result in a `null` value being assigned to the variable.