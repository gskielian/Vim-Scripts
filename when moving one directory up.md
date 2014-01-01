When going one directory deeper try this


```vim

%s/\(href="\)\([^#]\)/\1..\/\2/g
%s/\(src="\)\([^#]\)/\1..\/\2/g

```
