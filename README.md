# Command line #
$ npm install --global gulp-cli
$ npm init
$ npm install --save-dev gulp
Create a gulpfile.js at the root of your project
$ npm install --save-dev gulp-watch
$ npm install gulp-less

Markdown syntax guide
# Heading 1 #
## Heading 2 ##
### Heading 3 ###
#### Heading 4 ####
*Emphasized text*
~~Strikethrough text~~
**Strong text**
***Strong emphasized text***
[Named Link](http://www.google.fr/)
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
* Item 1
* Item 2
* Item 3
  * Item 3a
  * Item 3b
1. Step 1
2. Step 2
3. Step 3
    1. Step 3.1
    2. Step 3.2
> Quotes or citations
`Inline code: function()`
```
This is a code block
var oldUnload = window.onbeforeunload;
window.onbeforeunload = function() {
    saveCoverage();
    if (oldUnload) {
        return oldUnload.apply(this, arguments);
    }
};
```
![Alt text](http://monosnap.com/image/bOcxxxxLGF.png)