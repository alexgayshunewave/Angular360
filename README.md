# Angular360

360 degree panorama VR library for AngularJS. [Sample](http://ejeinc.github.io/Angular360/)

## How to use (view sample)

```
$ git clone https://github.com/ejeinc/Angular360.git
$ cd Angular360
$ bower install
```

and open `demo.html` in browser.


## Install

```
$ bower install angular360
```

or, simply download and include [angular360.css](https://github.com/ejeinc/Angular360/blob/master/angular360.css) and [angular360.js](https://github.com/ejeinc/Angular360/blob/master/angular360.js) to your HTML.

## Example HTML

```HTML
<!DOCTYPE html>
<html ng-app="myApp">
<head>
  <title>Angular360</title>
  <!-- Include CSS -->
  <link rel="stylesheet" type="text/css" href="bower_components/angular360/angular360.css">
</head>
<body>
  <!-- Put <vr-cube> element -->
  <vr-cube front="img/front.jpg" left="img/left.jpg" right="img/right.jpg" back="img/back.jpg" top="img/top.jpg" bottom="img/bottom.jpg"></vr-cube>

  <!-- Include dependencies -->
  <script src="bower_components/angular/angular.min.js"></script>

  <!-- Include JS -->
  <script src="bower_components/angular360/angular360.js"></script>
  <script type="text/javascript">
    // Add 'Angular360' to your module dependencies
    angular.module('myApp', ['Angular360']);
  </script>
</body>
</html>
```

## License

MIT
