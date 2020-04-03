How to Style Images With Markdown
=====================================================

#### Normal format
```
![alt text](image/kitten.jpg "A cute kitten")
```
![alt text](image/kitten.jpg "A cute kitten")

<br>

#### HTML format
```
<img src="image/kitten.jpg" alt="Kitten"
	title="A cute kitten" width="150" height="100" />
```
<img src="image/kitten.jpg" alt="Kitten"
	title="A cute kitten" width="150" height="100" />

<br>

#### Reference-style:
```
![alt text][logo]

[logo]: image/kitten.jpg "A cute kitten"
```
![alt text][logo]
  
[logo]: image/kitten.jpg "A cute kitten"

<br>

#### CSS format
```
## tapi gak jalan
![Kitten](image/kitten.jpg?thumbnail)

img[src~="thumbnail"] {
   width:150px;
   height:100px;
}
img[src~="bordered"] {
   border: 1px solid black;
}
```
![Kitten](image/kitten.jpg?thumbnail)

img[src~="thumbnail"] {
   width:150px;
   height:100px;
}
img[src~="bordered"] {
   border: 1px solid black;
}

<br>

#### CSS2 format
```
## gak jalan juga
![Kitten](image/kitten.jpg){: width=150 height=100 style="float:right; padding:16px"}

img[alt="Kitten"] {
   width: 150px;
   height: 100px;
}
```
![Kitten](image/kitten.jpg){: width=150 height=100 style="float:right; padding:16px"}

img[alt="Kitten"] {
   width: 150px;
   height: 100px;
}
