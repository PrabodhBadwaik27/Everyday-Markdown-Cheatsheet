# Everyday Markdown Cheatsheet
A tiny notebook consisting syntax of general markdown features.  
**Pre-requisite:** None  
**Expertise:** Beginner  

## Index
- Lists  
    - [Ordered List](#ordered-list)    
    - [Unordered List](#unordered-list)  
    - [Nested Lists](#nested-lists)  
    - [Mixed Lists](#mixed-lists)  
- Tables
    - Basic Tables
    - Aligned Tables
- Mathematical Formulae

## Lists
### Ordered List
    Markup ::
    1. First Element
    2. Second Element
    3. Third Element

1. First Element
2. Second Element
3. Third Element  

### Unordered List
    Markup ::
    - First Element
    - Second Element
    - Third Element
    
- First Element
- Second Element
- Third Element

### Nested Lists
**1. Ordered Nested List**   

    Markup ::
    1. First Element
        1. Sub-element 1.1
        2. Sub-element 1.2
    2. Second Element
        1. Sub-element 2.1
        2. Sub-element 2.2  

1. First Element
    1. Sub-element 1.1
    2. Sub-element 1.2
2. Second Element
    1. Sub-element 2.1
    2. Sub-element 2.2

**2. Unordered Nested List**
    
    Markup ::
    - First Element
        - Sub-element 1.1
        - Sub-element 1.2
    - Second Element
        - Sub-element 2.1
        - Sub-element 2.2
    
- First Element
    - Sub-element 1.1
    - Sub-element 1.2
- Second Element
    - Sub-element 2.1
    - Sub-element 2.2

### Mixed Lists
**1. Ordered Mixed List**   

    Markup ::
    1. First Element
        - Sub-element 1.1
        - Sub-element 1.2
    2. Second Element
        - Sub-element 2.1
        - Sub-element 2.2  

1. First Element
    - Sub-element 1.1
    - Sub-element 1.2
2. Second Element
    - Sub-element 2.1
    - Sub-element 2.2

**2. Unordered Mixed List**
    
    Markup ::
    - First Element
        1. Sub-element 1.1
        2. Sub-element 1.2
    - Second Element
        1. Sub-element 2.1
        2. Sub-element 2.2
    
- First Element
    1. Sub-element 1.1
    2. Sub-element 1.2
- Second Element
    1. Sub-element 2.1
    2. Sub-element 2.2

## Tables
### Basic Tables
    Markup::
    First Header  | Second Header
    ------------- | -------------
    Content Cell  | Content Cell
    Content Cell  | Content Cell

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

**Adding a pipe | in a cell**

    Markup::
    First Header  | Second Header
    ------------- | -------------
    Content Cell  | Content Cell
    Content Cell  |  \|

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  |  \| 

### Aligned Tables
**Left, right and center aligned table**

    Markup::
    Left aligned Header | Right aligned Header | Center aligned Header
    | :--- | ---: | :---:
    Content Cell  | Content Cell | Content Cell
    Content Cell  | Content Cell | Content Cell

Left aligned Header | Right aligned Header | Center aligned Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell

## Mathematical Formulae
    Markup::
    <img src="https://render.githubusercontent.com/render/math?math=<!--insert-forumla-here-->">
    
    <img src="https://render.githubusercontent.com/render/math?math=s^{2} = \frac{\sum (x_{i} - \bar{x})^{2}}{N - 1}">
    
<img src="https://render.githubusercontent.com/render/math?math=s^{2} = \frac{\sum (x_{i} - \bar{x})^{2}}{N - 1}">

[Reference, to script formulae](https://rpruim.github.io/s341/S19/from-class/MathinRmd.html)
