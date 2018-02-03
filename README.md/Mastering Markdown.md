## Sometimes you want numbered lists:
1. One
2. Two
3. Three 

## Sometimes you want bullet points:

* Start a line with a star
* Profit!

I think you should use an
`<addr>` element here instead.

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

1. First list item
     - First nested list item
       - Second nested list item
       
octocat :+1: This PR looks great - it's ready to merge! :metal: :two_women_holding_hands:


1. Item 1
1. Item 2
1. Item 3
1. Item 4
1. Item 5
   1. Item 3a
   1. Item 3b
   1. Item 3b
   1. Item 3b
   
# table no pipes

Header 1 | Header 2
-------- | --------
  Cell 1 | Cell 2
  Cell 3 | Cell 4
   
# tables with leading pipe

| Header 1 | Header 2
| -------- | --------
| Cell 1 | Cell 2
| Cell 3 | Cell 4


# tables with full bars

| Header 1 | Header 2 |
| -------- | -------- |
| Cell 1 | Cell 2 |
| Cell 3 | Cell 4 |

# single column single leading bar

| Header 1
| --------
| Cell 1
| Cell 3

# single column single trailing bar

Header 1 |
-------- |
Cell 1 |
Cell 3 |

# single column full bars

| Header 1 |
| -------- |
| Cell 1 |
| Cell 3 |


# narrow col 1

| H |
| - |
| 1 |
| 2 |

# table in blockquote

> | One | Two | Three |
> | --- | --- | --- |
> |grinch|stole|xmas|
> |green|**eggs**|ham|
>
> -- Dr. Seuss

# table with blank cells

 | Header 1 |  |
 | -------- | -------- |
 | Cell 1 |          |
 |  | Cell 4 |
 
 
 # table in blockquote with empty cells

> |  | Two | Three |
> | --- | --- | --- |
> |grinch|stole||
> |green|**eggs**|ham|
>
> -- Dr. Seuss

# escaping of pipes

| A  | \| | C \| C |
|--- |--- | ------ |
|\|\|| BB | C |


