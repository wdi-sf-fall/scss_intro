#SCSS

##Learning Objectives

* Compare SCSS & Sass
* Articulate Sass's advantages
* Translate CSS into Sass

##SCSS, the Sassy CSS

SCSS stands for *Sassy CSS* was introduced as "the new main sytax" for Sass.

Rails is configured to understand SCSS.

CSS

```
#container {
    width:960px;
    margin:0 auto;
}
#container p {
    color: black;
}
```

SCSS

```
$black: #000000;
#container {
    width:960px;
    margin:0 auto;
    p {
        color :$black;
    }
}
```

##Core Advantages

* DRY
* Sustainable
* Semantic
* Modular


##Nesting
[Example](http://jsbin.com/jagaka/2/edit)
##Variables
[Example](http://jsbin.com/tadupo/3/edit)
##Mixins
[Example](http://jsbin.com/felapu/1/edit?html,css,output)
##Extend
[Example](http://jsbin.com/bomuqe/2/edit?html,css,output)


##Resources

* [Tuts](http://leveluptuts.com/tutorials/sass-tutorials)
* [Compass Best Practices](http://compass-style.org/help/tutorials/best_practices/)