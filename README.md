# Product Gallery

## Guide link: 
https://hexschool.github.io/THE_F2E_Design/week4-product%20gallery/

## Demo link: 
https://cocolin041.github.io/product-gallery/

## Finish with: 
CSS Grid Layout

## Grid Layout introduction:
Allowing you to divide viewport into grid-column, grid-row, and put each block in a neat way.<br>

Useful syntax there are:<br>
1. ```display: grid```<br>
2. ```grid-template-columns/rows```<br>
Set how many cols/rows you want to have and the size of it<br>
```
grid-template-columns: 100px 100px 100px; //set three columns with 100px
//or
grid-template-columns: repeat(3, 100px);
//or
grid-template-columns: repeat(3, 1fr); //fr is an unit that used for divide the remaining spaces, in this case, you distribute the remaining spaces to three columns evenly
```
3. ```grid-column/row```<br>
```
grid-column: 1/5; //means let an element position starts from column 1 to column 5
grid-row: 1/5; //means let an element position starts from row 1 to column 5
```

