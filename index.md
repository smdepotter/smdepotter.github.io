---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default

---
<style>
* {
    box-sizing: border-box;
}

.row {
    display: -ms-flexbox; /* IE10 */
    display: flex;
    -ms-flex-wrap: wrap; /* IE10 */
    flex-wrap: wrap;
    padding: 0 4px;
}

/* Create four equal columns that sits next to each other */
.column {
    -ms-flex: 33%; /* IE10 */
    flex: 33%;
    max-width: 33%;
    padding: 0 4px;
}

.column img {
    margin-top: 8px;
    vertical-align: middle;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 800px) {
    .column {
        -ms-flex: 50%;
        flex: 50%;
        max-width: 50%;
    }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
    .column {
        -ms-flex: 100%;
        flex: 100%;
        max-width: 100%;
    }
}
</style>
<body>

<!-- Photo Grid -->
<div class="row">
  <div class="column">
    <img src="assets\icons\csharp-plain.svg" style="width:70%">
    <img src="assets\icons\github-original.svg" style="width:70%">
  </div>
  <div class="column">
    <img src="assets\icons\illustrator-plain.svg" style="width:70%">
    <img src="assets\icons\photoshop-plain.svg" style="width:70%">

  </div>  
  <div class="column">
    <img src="assets\icons\java-plain.svg" style="width:70%">
    <img src="assets\icons\swift-plain.svg" style="width:70%">
  </div>
</div>
</body>


**Hello World!** *hello World* ***hello***


# Header1
Hello
> blockquotes are handy or not

## Header2
Hello 2
[I'm an inline-style link with title](https://www.google.com "Google's Homepage")
### Header3
Hello 3
[I'm an inline-style link](https://www.google.com)
#### Header4
```Lua
function(Hello)
end
```
