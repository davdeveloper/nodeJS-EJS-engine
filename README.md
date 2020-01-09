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
