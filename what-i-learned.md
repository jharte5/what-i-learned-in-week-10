### What I Learned in Week 10

# Responsive Portfolio
    - took our portfolios from week 2, put it on a webpage and made it responsive.
    - used media queries 
        ```@media (min-width: 501px) && (max-width: 801px) {
    #section-2 {
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
    }
    .pic {
        width: 75%;
    }
    #name {
        width: 20vw;
        height: 70vh;
    }
}```

# Code Wars
    * Return of the day
    * Abbreviate a Two word name
    * Players contact Manager


# Japanese Grid
    - used `grid-template-column` and `grid-template-row` to make img's fit in the grid spots 
    - ```#app {
    display: grid;
    height: 1100px;
    width: 900px;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(5, 1fr);
}```

# Japanese Grid Big
    -same thing but bigger 

# Holy Grid Area
    - started using `grid-template-area` to make img's go to their designated areas
    - ```grid-template-areas: "header header header"
                        "nav article-1 ad-area"
                        "nav article-2 ad-area"
                        "footer footer footer";```

# Holy Responsive Grid
    - making the grid area responsive using media queries 
    - @media (max-width: 801px) and (min-width: 451px) {
  ```#app {
    display: grid;
    text-align: center;
    width: 100vw;
    grid-template-rows: 1fr 1fr 2fr 2fr 1fr;
    grid-template-columns: 5fr 4fr;
    grid-template-areas:  "header     header" 
                          "nav        nav"
                          "article-1  ad-area"
                          "article-2  ad-area"
                          "footer     footer";
  }```

# Thing a Gram
    - see next presentation 

