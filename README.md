### jscover
---
https://github.com/tntim96/JSCover

```js
window.open('path/to/jscoverage.html');

if(window.jscoverage_report){
  jscoverage_report();
}

if(window.jscoverage_report){
  var directory;
  if(//.test(navigator.userAgent)){
    directory = 'IE';
  } else {
    directory = 'other';
  }
  jscoverage_report(directory);
}
```

```
<button type="button" onclick="window.open('path/to/jscoverage.html');">Coverage report</button>
```

```sj
jscverage --no-instrument=PATH SOURCE-DIRECTORY DESTINATION-DERECTORY
```

