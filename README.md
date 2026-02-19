```
             __
   _________/ /______________
  / ___/ __  / ___/ ___/ ___/
 (__  ) /_/ / /__(__  |__  )
/____/\__,_/\___/____/____/

```

A simple, mostly classless, flexed CSS boilerplate. There's only 3 things to be aware of:
* Rows are custom tags: `<col-row>`. These must only contain columns. Usually direct chidlren of `body`, but can be nested in columns for more granular design.
* Columns are custom tags. They come in 13 flavors. Sizes 1 to 12 and `x` which has an automatic width. IE: `<col-1>`, `<col-12>`, `<col-x>`.
* Related content in columns are supposed to be put in a `<div>`. You can add more `div`-elements to the same column.

Use the CSS by adding this to your header:
```
<link href="https://superdupercybertechno.github.io/sdcss/sdcss.css" rel="stylesheet" type="text/css" media="all" />
```
