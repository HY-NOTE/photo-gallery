# photo-gallery
。。。
<!DOCTYPE html>

<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8" />
    <title>Image Gallery</title>
    <link rel="stylesheet" href="styles/layout.css" media="screen" />
</head>
<body>
 <h1>Snapshots</h1>
 <ul>
  <li>
   <a href="images/firworks.JPG" onclick="showpic(this);
    return false;" title="This 1">Fireworks</a>
  </li>
  <li>
   <a href="images/coffee.JPG"onclick="showpic(this);
    return false;" title="2 and 3">coffee</a>
  </li>
  <li>
   <a href="images/rose.JPG" onclick="showpic(this);
    return false;" title="This is a photo three woman">rose</a>
  </li>
   <a href="images/bigben.JPG" onclick="showpic(this);
    return false;" title="4">big ben</a>
   <li>
  </ul>
 <img id="placeholder" src="images/placholider.gif" alt="my image gallery"/>  <!--插入一个占位-->
 <p id="description">Choose an image.</p> <!--插入说明-->
 <script src="javascript/showPic.js"></script>
 </body>
</html>
