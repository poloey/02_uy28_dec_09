# class 2 uy-27


# Essential tag and attribute in html

* [id, class]
* a [href, target, title]
* form [action, method] {get, post}
* label[for]{<input_id>}
* input [type, required, name, value, placeholder] {text, email, password, submit, checkbox, radio}
* select [name]
* option [value]
* textarea [name]
* img [src, alt, title]
* div
* span

# id and class Attribute

All html tag has `id` and `class` attribute. `id` use for uniquely select a html element in entire document. So there will be only one id in entire document. Id can be selected by `#` sign. Class can be used for selecting group of element. In css, class is selected by `.` sign

## a

~~~html
In `href` attribute you will give your desired path. To open link in different tag use `target=_blank"`
<!-- absolute path with http/https -->
<a href="https://google.com" target="_blank" title="google link">visit google</a>
<!-- relative path -->
<a href="about.html">visit google</a>
<!-- id -->
<a href="#home">Home section</a>
~~~

## form 

~~~html
<form action="somepage.php" method="get"></form>
~~~

## label  and input

~~~html
<label for="name">Name</label>
<input id='name' type="text" name="name" value="some value" placeholder="Enter your name" required>
~~~

## select and option 
Select create a droption selection 

~~~html
<select name="city">
  <option value="1">Dhaka</option>
  <option value="2">Chittagong</option>
  <option value="3">Feni</option>
  <option value="4">Comilla</option>
</select>
~

##  textarea 

~~~html
<textarea name="contet" ></textarea>
~~~


## img 

~~~html
<img src="google.png" alt="some alternative text about google">
~~~

# div 
div is a block level element. It takes whole width of parent width. used for non semantic content 
~~~html
<div></div>
~~~

# span 

~~~html
<span></span>
~~~
span is a inline element. Use for non semantic content


## How to install live-server in your pc globally

~~~bash

npm install live-server -g

~~~







