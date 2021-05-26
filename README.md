# JavaScript-copy-function

Please see Codepen:

https://codepen.io/K-SY/pen/poewxyQ

``` javascript
function copyEvent(id) {
  var str = document.getElementById(id);
  window.getSelection().selectAllChildren(str);
  document.execCommand("Copy");
}
```
