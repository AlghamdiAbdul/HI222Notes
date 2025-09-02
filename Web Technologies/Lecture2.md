---
tags:
  - theory
  - webtech
  - HealthPolicy
Course:
  - Web Technologies
Date: 2025-09-02T08:40:00
---
---
### Intro to HTML Pt. 1
- Definition:
	- HTML is an acronym which stands for (H)yper (T)ext (M)ark-up (L)anguage
	- **Hyper**: is opposite of linear
	- **Text**: words/sentences/paragraph
	- **Language**: It is a language
		- It's a markup language that *structure and content* of a document that is displayed in a browser.
- HTML Tags:
	- An HTML document is comprised of one word commands enclosed between the less than (<) and greater than (>) sign
	- Empty HTML Document:
	- ```
	  <!DOCTYPE html>
	  <html>
		  <head>
			  <title>
				  
			  </title>
		  </head>
		  <body>
			  
		  </body>
	  </html>
	  ```
	- DOCTYPE Tag:
		- **DOC**ument **TYPE**
		- Should be placed at the start of each page
		- Show which standard the page complies with
	- HTML Tag:
		- Is a Root Element/Tag
		- Contains all tags that will be used in an HTML document
		- It is neccessry
		- Has an attribute "lang" which defines the language of the content
	- HEAD TAG:
		- Placeholder
	- BODY Tag:
		- Placeholder
- Comments in HTML:
	- Content wrapped within a comment will not be displayed on the web page
	- Comments help keep our files organized
	- Comments become especially useful when there are multiple people working on the same files
	- HTML comments start with <!-- and end with -->
		- ```
		  <!-- Comment -->
		  ```
- Text Based Elements in HTML
	- Heading Tags:
		- H1-6: With each number going up from 1-6 the headings gets smaller
		- H1: The biggest heading
		- H6: The smallest heading
	- Paragraph Tag:
		- Enclosed between the:
			- ```
			  <p> and </p> tags
			  ```
		- Bold Tag
			- Makes world **BOLD*** using **strong** tag
		- Italics Tag
			- Makes words *Italic* using the **em** tag
		- Delete Tag
			- Rendered as strike-through text using **del** tag
		- Sup and Sub Tags:
			- To **Superscript** text using **sup** tag
			- Or to **Subscript** text using **sub** tag
		- Horizontal Rule:
			- Rendered as a horizontal line using the **hr/** tag