# Scrolly
The very basic smooth scroll to element

```html
<a class="nav" to="div1">Menu 1</a>
<a class="nav" to="div2">Menu 2</a>
<a class="nav" to="div3">Menu 3</a>
<a class="nav" to="div4">Menu 4</a>

<div id="div1" style="height:500px;background:red">1</div>
<div id="div2" style="height:400px;background:blue">2</div>
<div id="div3" style="height:600px;background:yellow">3</div>
<div id="div4" style="height:300px;background:brown">4</div>

<button id="top">Top</button>
```
```html
<script src="Scrolly.js"></script>
```
```javascript
Scrolly.init({
  class:"nav",
  duration:1000,
  offset:100 //optional
});
document.getElementById("top").onclick=Scrolly.top;
```
