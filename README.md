# md1
pirmais patstavigais darbs



> Blockquotes

Mēs neesam šeit, lai visu saprastu.
                    
> "Blockquotes Blockquotes", [Link](https://www.fenikssfun.com/pardomam/35-jegpilni-jura-rubena-citati-7402)。

####Javascript　

```javascript
function test(){
	console.log("Hello world!");
}
 
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

![](https://www.pressgazette.co.uk/wp-content/uploads/2020/11/shutterstock.jpg)
> Follow your dreams.

####Unordered list (-)

- Item A
- Item B
- Item C
     
####Unordered list (plus sign and nested)
                
+ Item A
+ Item B
    + Item B 1
    + Item B 2
    + Item B 3
+ Item C
    * Item C 1
    * Item C 2
    * Item C 3
    
    
###Tables
                    
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell 

——————————————————————————————
###Emoji mixed :smiley:

> Blockquotes :star:

###End
