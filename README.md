<div align = "center">

# Frontend-Development-Learning

Blog 1 :  <a herf = "#"> Learn Flexbox in CSS </a>

</div>





# Responsive Webdevelopment

### Use of px

- px is fixed size pixel doesn't change with screen size

### Use of %

-  % is used to make the website responsive based on its parent

```
<div id = "box">
    <div id = "inner"> </div>
</div>

#box{
    width: 500px;
    height: 500px;
}

#inner{
    width: 50%;
    height: 50%;
}
```

Box is parent of Inner div. If box gets 500px of overall screen. Here the inner div is 50% of the box div


### Use of vw and vh

- donot depend on parent depend on screen size
- reponse with screen size high and low


### Use of vmax and vmin

- Swap betwwen vw and vh based on screen size
- reponse with screen size high and low

### Use of em and rem

- em is relative to its parent
- instead of changing all just change the parent and rest will change automatically based on parent size

```
<div id = "box">
    <h1> Test </h1>
    <h2> Test </h2>
    <h3> Test </h3>
</div>

#box{
    width: 500px;
    height: 500px;
    font-size: 20px;
}

h1{
    font-size: 2em;    // parent box font-size * 2 = 40px
}

h2{
    font-size: 1em;    // parent box font-size * 1 = 20px
}

h3{
    font-size: 1.5em;    // parent box font-size * 1.5 = 30px
}
```

- rem is relative to its root/whole screen instead of parent
- 1 rem = 16px


Time : 28.30