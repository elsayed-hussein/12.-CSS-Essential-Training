# CSS

## Import Css

### External Css With <link>

<link rel="stylesheet" href="style.css">

### External Css With @import

@import url('style.css');

### Inline

<h1 style="color:red;"> </h1>

### Internal

<style>
    h1{
        color:red;
    }
</style>

## Css Selectors

### Type

h1{
color:red;
}

### Universal

\*{
color:red;
}

### Class

.className{
color:red;
}

### ID

\#idName{
color:red;
}

### Descendant

h1 p{
color:red;
}

### Grouping

h1,h2{
color:red;
}
.or.
element.className{
color:red;
}

## Specificity

1. universal (\*)
2. type (element)
3. class (.className)
4. id (\#idName)
5. important keyword (!important)

## pseudo

element:link{
color:red;
}
element:visited{
color:red;
}
element:focus{
color:red;
}
element:hover{
color:red;
}
element:active{
color:red;
}

## HTML Elements

### inLine

1. a
2. span
3. strong

### Block

1. p
2. h1
3. article
4. section

## font face

@font-face {
font-family:"My Font";
src: url(my-font.woff);
src:url(<http://example.com/font/my-font.woff>);
}

## font size

### px

absolute value

### em

relative unit to the parent

### rem

root em , relative uint to the HTML

## position

### static

not positioned

### relative

relative to current position
.relative{
position:relative;
top:10px;
right:10px;
}

### absolute

relative to containing element
.absolute{
position:absolute;
top:10px;
right:10px;
}

### fixed

relative to the viewport even on scrolling
.fixed{
position:fixed;
top:10px;
right:10px;
}

### sticky

relative to containing element and viewport even on scrolling
.sticky{
position:sticky;
top:10px;
right:10px;
}

## flex

flex: grow shrink basis;
