<!-- HERE -->
<!-- 1. Open the preview -->
<!-- 2. Define elements we would like to customize alignment (or any other style) -->
<!--    * ALIGN IMAGE to the center -->
<!-- 3. Create a snippet which contains the HTML code needed -->
<!--    * HTML should be clean by scaping characters and adding tabs as \t -->
- [Elements we would like to align](#elements-we-would-like-to-align)
- [Options:](#options)
	- [1. MD and HTML](#1-md-and-html)
	- [2. Simply HTML](#2-simply-html)
- [Solution](#solution)

# Elements we would like to align

* Image

<div align="center">
	<img src="../resources/imgs/1-good-docs.jpg" alt="[ALT_TEXT]">
</div>


# Options: 

## 1. MD and HTML

```html
<div align="right">

MD CODE

</div>
```

## 2. Simply HTML 

<!-- HERE: Please note after we insert the snippet we have to change the [PATH] and [ALT_TEXT]  -->

* **Image**
```html
<div align="center">
    <img src="[PATH]" alt="[ALT_TEXT]">
</div>
``` 

# Solution

```json
{
	"Insert Image align center": {
		"scope": "markdown",
		"prefix": "img_center",
		"body": [
			"<div align=\"center\">",
			"\t<img  src=\"[PATH]\" alt=\"[ALT_TEXT]\">",
			"</div>",
		],
		"description": "Image Center"
	}
}
```