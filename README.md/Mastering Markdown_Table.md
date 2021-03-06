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


# tables with mixed bars

Header 1 | Header 2
| -------- | --------
Cell 1 | Cell 2 |
| Cell 3 | Cell 4 |


# tables with bars and leading spacing

 | Header 1 | Header 2 |
 | -------- | -------- |
 | Cell 1 | Cell 2 |
 | Cell 3 | Cell 4 |


# table with cuddled following content

| Header 1 | Header 2 |
| -------- | -------- |
| Cell 1 | Cell 2 |
| Cell 3 | Cell 4 |



# FAIL: table with cuddled leading content

before
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


# narrow col 2

| He |
| -- |
| 1 |
| 2 |


# narrow col 3

| He |
| --- |
| 1 |
| 2 |


# FAIL: no dash

| He |
| :: |
| 1 |
| 2 |


# table with markup in cells

| Header 1 | *Header* 2 |
| -------- | -------- |
| `Cell 1` | [Cell 2](http://example.com) link |
| Cell 3 | **Cell 4** |


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





| Header 1 | *Header* 2 |
  | -------- | -------- |
  | `Cell 1` | [Cell 2](http://example.com) link |
  | Cell 3   | **Cell 4** |
