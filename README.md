# Responsive_HTML-CSS_only

###Youtube tutorial from Daily Tuition 

https://www.youtube.com/watch?v=R8IDaR05DC4

## To add colomn 

```
.container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  overflow: hidden;

}
```

## Responsive screen

```
@media only screen and (max-width: 990px) { 
  .view {
    display: none;
  }
  .tablet-view {
    display: block;
  }

}
```