<!DOCTYPE html>
<html>
<head>
   <title>MyTemplate2</title>
   <!-- Link to external style sheet -->
   <link href="styles.css" rel="stylesheet" type="text/css" />
</head>
<body>
   <script>
   //Make older browsers aware of new HTML5 layout tags
   'header nav aside article footer section'.replace(/\w+/g, function (n) { document.createElement(n) })
   </script>
   <div id="wrapper">
   <header>
   <h1>Sample H1 Heading</h1>
   </header>
   <nav>
   <a href="#">Home</a>
   <a href="#">Products</a>
   <a href="#">Services</a>
   <a href="#">About</a>
   <a href="#">Contact Us</a> 
   </nav>
   <article>
   Top
   <p>Paragraph 1</p>
   <p>Paragraph 2</p>
   <p>Paragraph 3</p>
   <p>Paragraph 4</p>
   <p>Paragraph 5</p>
   <p>Paragraph 6</p>
   <p>Paragraph 7</p>
   <p>Paragraph 8</p>
   <p>Paragraph 9</p> 
   <p>Paragraph 10</p>
   <p>Paragraph 11</p>
   <p>Paragraph 12</p>
   <p>Paragraph 13</p> 
   Bottom
   </article>
   <footer>
   footer
   </footer>
   </div><!-- End wrapper -->
</body>
</html>
