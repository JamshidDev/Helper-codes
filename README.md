
# Helper-codes


- Yordamchi kodlar bu sizni loyihanizda as qotishi mumkin bo'lgan kodlar to'plami

JAVASCRIPT
==========

####Javascriptã€€

```javascript

// Date funksiyasi

new Date()
new Date(year, month, day, hours, minutes, seconds, milliseconds)      // new Date(2018, 11, 24, 10, 33, 30, 0);
new Date(milliseconds)
new Date(date string)
 
(function(){
    var box = function(){
        return box.fn.init();
    };

    box.prototype = box.fn = {
        init : function(){
            console.log('box.init()');

			return this;
        },

		add : function(str){
			alert("add", str);

			return this;
		},

		remove : function(str){
			alert("remove", str);

			return this;
		}
    };
    
    box.fn.init.prototype = box.fn;
    
    window.box =box;
})();

var testBox = box();
testBox.add("jQuery").remove("jQuery");
```
VUEjs 3
=======

#### Vue@3 uchun maska 

`$ npm install maska`

EXPRESSJS 
========
#### Expressjs static folder
```javascript 

app.use(express.json())
app.use(express.static(path.join(__dirname, 'public')))

```

