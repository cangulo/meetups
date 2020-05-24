<!-- HERE -->
<!-- 1. Define areas we need to have in command along all the articles -->
<!--    * Contact Information -->
<!--    * Link to the top of the document -->
<!--    * Go to Index -->
<!-- 2. Create a snippet which contains that area -->

- [Header 1](#header-1)
- [Header 2](#header-2)
- [Header 3](#header-3)
- [Contact Information](#contact-information)
- [Solution](#solution)

# Header 1

Etiam non massa id tortor fermentum accumsan et sit amet justo. Nam eu risus quis massa iaculis rutrum. Pellentesque facilisis tempor ligula eu lacinia. Vivamus lacinia mi eu lacus egestas rutrum.

# Header 2

Etiam non massa id tortor fermentum accumsan et sit amet justo. Nam eu risus quis massa iaculis rutrum. Pellentesque facilisis tempor ligula eu lacinia. Vivamus lacinia mi eu lacus egestas rutrum.

# Header 3

Nam lectus ipsum, blandit et aliquam ut, tempor aliquam lacus. Nullam eget dictum ante. Aliquam id risus turpis. Nam eu justo ut massa tincidunt volutpat. Proin vel hendrerit magna. Vestibulum a interdum ligula.


# Contact Information

I'm a software engineer with experience in .NET Framework, .NET Core and Angular, I love 
challenges, learning and share knowledge. Feel free to contact me via LinkedIn.

![Profile Picture](https://media-exp1.licdn.com/dms/image/C5612AQFBFdJt_exE8Q/article-inline_image-shrink_1000_1488/0?e=1590624000&v=beta&t=l3VTNfq9iN0bCFuXh_2bQr1xrd06yZoFGkm1w3DWRDQ)

*Per aspera ad astra.*

LinkedIn   - [Carlos Angulo Mascarell](https://www.linkedin.com/in/angulomascarell)  
Twitter   - [@AnguloMascarell](https://twitter.com/angulomascarell)


[Come back to top](#)
[Go to Index](../Index.md)

# Solution

* md-code.json

```json
{
	"Link: Come Back to Top ": {
		"scope": "markdown",
		"prefix": "come_back_top",
		"body": [
			"[Come back to top](#)"
		],
		"description": "Insert a link to navigate to the top of the page"
	}
}
```

* md-articles.json

```json
{
    "Go to Index": {
		"scope": "markdown",
		"prefix": "go_to_index",
		"body": [
			"[Go to Index](../Index.md)"
		],
		"description": "Insert a link to navigate to the top of the page"
	},
	"Contact_Area": {
		"scope": "markdown",
		"prefix": "contact_area",
		"body": [
			"# Contact Information",
			"",
			"I'm a software engineer with experience in .NET Framework, .NET Core and Angular, I love ",
			"challenges, learning and share knowledge. Feel free to contact me via LinkedIn.",
			"",
			"![Profile Picture](https://media-exp1.licdn.com/dms/image/C5612AQFBFdJt_exE8Q/article-inline_image-shrink_1000_1488/0?e=1590624000&v=beta&t=l3VTNfq9iN0bCFuXh_2bQr1xrd06yZoFGkm1w3DWRDQ)",
			"",
			"*Per aspera ad astra.*",
			"",
			"LinkedIn   - [Carlos Angulo Mascarell](https://www.linkedin.com/in/angulomascarell)  ",
			"Twitter   - [@AnguloMascarell](https://twitter.com/angulomascarell)",
			"",
			"[Come back to top](#)  ",
			"[Go to Index](../Index.md)",
		],
		"description": "Insert the contact area"
	}
}
```