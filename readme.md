#SCSS

##Learning Objectives

* Compare SCSS & Sass
* Translate CSS into Sass
* Articulate Sass's advantages

##SCSS, the Sassy CSS

[Difference between Sass & SCSS](http://www.sitepoint.com/whats-difference-sass-scss/)

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

**GOAL**
Now you try:

Convert the below CSS to SCSS on [jsbin](http://jsbin.com/?html,css,output)

```
#container {
    width: 100%;
    background: pink;
}

#container ul {
    list-style-type: none;
}

#container ul li {
    color: blue;
}

#container ul li:hover {
    text-decoration: underline;
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
