## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/AthanGriv/Test/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

<!DOCTYPE html>
<html>
<body>

<h3>A demonstration of how to access a Text Field</h3>

<input type="text" id="myText" value="Some text...">

<p>Click the "Try it" button to get the text in the text field.</p>

<button onclick="myFunction()">Try it</button>

<p id="demo"></p>

<script>
function myFunction() {
  var x = document.getElementById("myText").value;
  document.getElementById("demo").innerHTML = x;
}
</script>

</body>
</html>


### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
