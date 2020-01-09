# nodeJS-EJS-engine
Basic files for nodeJS with the EJS engine and express

Dynamic Template Managment 
```
// Home  
app.get('/', function(req, res) {
    res.render('pages/index', {
    	template: '../pages/home' // add path to body of (home)
    });
});
```
Create your file in views/pages/ ... example.ejs

views/pages/index.ejs file which include the header, footer and the content
```
<header>
    <%- include('../partials/header') -%>
</header>

<%- include(template) -%>

<footer>
    <%- include('../partials/footer') -%>
</footer>
```
