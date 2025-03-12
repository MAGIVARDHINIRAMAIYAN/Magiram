<!DOCTYPE html>
<html>
<head>
	<title>My Web Page</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<h1 class="heading">Welcome to My Web Page</h1>
	<p class="paragraph">This is a paragraph of text.</p>
	<a class="link" href="https://www.example.com">Visit Example.com</a>
	<img class="image" src="image.jpg" alt="An image on the page">
</body>
</html>
```

CSS (in style.css file):

```
.heading {
	color: #00698f;
	font-size: 36px;
	text-align: center;
}

.paragraph {
	color: #666666;
	font-size: 18px;
	margin-bottom: 20px;
}

.link {
	color: #0099cc;
	text-decoration: none;
}

.link:hover {
	color: #00698f;
}

.image {
	width: 100%;
	height: auto;
	margin-top: 20px;
}
