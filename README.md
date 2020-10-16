## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/crystal-mullins/mypages.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/crystal-mullins/mypages.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

<!DOCTYPE html>
<html>
<head>
<style> 
main{
    background-color: aquamarine;
}
div {
  width: 50px;
  height: 50px;
  border: 5px solid black;
  background-color: red;
  position: relative;
  animation-name: example;
  animation-duration: 3s;
  animation-iteration-count: infinite;
  /* animation-direction: reverse; */
  animation-direction: alternate-reverse;
}

@keyframes example {
  0%   {background-color:red; left:0px; top:0px;}
  25%  {background-color:yellow; left:200px; top:0px;}
  50%  {background-color:blue; left:200px; top:200px;}
  75%  {background-color:green; left:0px; top:200px;}
  100% {background-color:red; left:0px; top:0px;}
}
h2 {
  width: 400px;
  height: 25px;
  border: 5px solid lightcoral;
  background-color: red;
  position: relative;
  animation-name: example;
  animation-duration: 7s;
  animation-iteration-count: infinite;
  animation: banner 5s linear 2s infinite alternate;
  /* animation-direction: reverse; */
  /* animation-direction: alternate-reverse; */
}

@keyframes banner {
    0%   {background-color:red; left:0px; top:0px;}
  25%  {background-color:yellow; left:300px; top:0px;}
  50%  {background-color:blue; right:10px; top:0px;}
  75%  {background-color:green; left:300px; top:0px;}
  100% {background-color:red; right:10px; top:0px;}
  /* 0%   {background-color:red; left:0px; top:0px;}
  20%  {background-color:yellow; left:5px; top:0px;}
  40%  {background-color:blue; left:5px; top:50px;}
  80%  {background-color:green; left:0px; top:50px;}
  100% {background-color:red; left:0px; top:0px;}  */
}
h1 {
  width: 400px;
  height: 255px;
  border: 10px solid black;
  background-color: red;
  position: relative;
  animation-name: example;
  animation-duration: 10s;
  animation-iteration-count: infinite;
  animation-direction: alternate;
 
}

@keyframes example {
  0%   {background-color:red; left:0px; top:0px;}
  25%  {background-color:yellow; left:400px; top:0px;}
  50%  {background-color:blue; left:400px; top:400px;}
  75%  {background-color:green; left:0px; top:400px;}
  100% {background-color:red; left:0px; top:0px;}
}
</style>
</head>
<body>
    <main>
        <h2>HAPPY BIRTHDAY JOHN MAYER</h2>

        <h1> <b>I can see you in the ASTRAL PLANE.</b> <b> Souls cascading throuh existance. </b> <b>  We collided, we merged, we parted. </b>  <b> Seeking that quench, a QUERY for data of the UNKNOWN </b></h1>

        <div> <b>JOHN </b> <b>Mayer </b> </div>
        <p>Large box = (Fans), Small box = (John Mayer), 'We catch up every once in a while....'</p>
    </main>


</body>
</html>
