# css-oriented-attributes
> 1. A easy-to-use css-oriented-attributes code.
>> 2. Oriented attributes - high repeatability.
>>> 3. Do not recommend adding too many classes in HTML tags, NOT!
>>>> 4. Remember the 3rd

### Download
[https://crlang.github.io/attributes.css/attributes.css](https://crlang.github.io/attributes.css/attributes.css)


## Code preview
### z-index - visibilities
```css
.zi--1 { z-index: -1; }

.zi-0 { z-index: 0; }
.zi-1 { z-index: 1; }
...
.zi-4 { z-index: 4; }
.zi-5 { z-index: 5; }

.zi-97  { z-index:  97; }
.zi-98  { z-index:  98; }
...
.zi-102 { z-index: 102; }
.zi-103 { z-index: 103; }

.zi-997  { z-index:  997; }
.zi-998  { z-index:  998; }
...
.zi-1002 { z-index: 1002; }
.zi-1003 { z-index: 1003; }

.zi-king { z-index: 2147483647; }
```
### Alignment - direction
```css
.ta-l { text-align: left; }
.ta-c { text-align: center; }
.ta-r { text-align: right; }
.ta-j { text-align: justify; }
```

### Alignment - Position
```css
.fl-l { float: left; }
.fl-r { float: right; }
.fl-n { float: none; }

.cl-l { clear: left; }
.cl-r { clear: right; }
.cl-b { clear: both; }
.cl-n { clear: none; }

.va-m { vertical-align: middle; }
.va-t { vertical-align: top; }
.va-b { vertical-align: bottom; }
.va-tt { vertical-align: text-top; }
.va-tb { vertical-align: text-bottom; }
.va-sub { vertical-align: sub; }
.va-sup { vertical-align: super; }

.va-0  { vertical-align:  0%; }
.va-5  { vertical-align:  5%; }
...
.va-90 { vertical-align: 90%; }
.va-95 { vertical-align: 95%; }
.va-100 { vertical-align: 100%; }

.va--5  { vertical-align:  -5%; }
.va--10 { vertical-align: -10%; }
...
.va--95 { vertical-align: -95%; }
.va--100 { vertical-align: -100%; }
```

### Padding - box inside
```css
.pd-a { padding: auto; }

.pdt-5  { padding-top:  5px; }
.pdt-10 { padding-top: 10px; }
...
.pdt-45 { padding-top: 45px; }
.pdt-50 { padding-top: 50px; }

.pdb-5  { padding-bottom:  5px; }
.pdb-10 { padding-bottom: 10px; }
...
.pdb-45 { padding-bottom: 45px; }
.pdb-50 { padding-bottom: 50px; }

.pdl-5  { padding-left:  5px; }
.pdl-10 { padding-left: 10px; }
...
.pdl-45 { padding-left: 45px; }
.pdl-50 { padding-left: 50px; }

.pdr-5  { padding-right:  5px; }
.pdr-10 { padding-right: 10px; }
...
.pdr-45 { padding-right: 45px; }
.pdr-50 { padding-right: 50px; }
```

### Margin - box outside
```css
.mg-t { margin: auto; }

.mgt-5  { margin-top:  5px; }
.mgt-10 { margin-top: 10px; }
...
.mgt-45 { margin-top: 45px; }
.mgt-50 { margin-top: 50px; }

.mgb-5  { margin-bottom:  5px; }
.mgb-10 { margin-bottom: 10px; }
...
.mgb-45 { margin-bottom: 45px; }
.mgb-50 { margin-bottom: 50px; }

.mgl-5  { margin-left:  5px; }
.mgl-10 { margin-left: 10px; }
...
.mgl-45 { margin-left: 45px; }
.mgl-50 { margin-left: 50px; }

.mgr-5  { margin-right:  5px; }
.mgr-10 { margin-right: 10px; }
...
.mgr-45 { margin-right: 45px; }
.mgr-50 { margin-right: 50px; }
```

### List - style
```css
.lst-n { list-style-type: none; }
.lst-c { list-style-type: circle; }
.lst-d { list-style-type: decimal; }
.lst-dlz { list-style-type: decimal-leading-zero; }
.lst-lr { list-style-type: lower-roman; }
.lst-ur { list-style-type: upper-roman; }
.lst-la { list-style-type: lower-alpha; }
.lst-ua { list-style-type: upper-alpha; }
```

### Display - area
```css
.dp-n { display: none; }
.dp-b { display: block; }
.dp-i { display: inline; }
.dp-t { display: table; }
.dp-f {
  display: -moz-flex;
  display: -ms-flex;
  display: -o-flex;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
}
.dp-g {
  display: -ms-grid;
  display: grid;
}
.dp-li { display: list-item; }
.dp-ib { display: inline-block; }
.dp-i { display: inline-table; }
.dp-i {
  display: -ms-inline-grid;
  display: inline-grid;
}
.dp-i {
  display: -moz-inline-flex;
  display: -ms-inline-flex;
  display: -o-inline-flex;
  display: -webkit-inline-box;
  display: -ms-inline-flexbox;
  display: inline-flex;
}
.dp-tc { display: table-cell; }
.dp-tfg { display: table-footer-group; }
.dp-thg { display: table-header-group;}
.dp-tr { display: table-row; }
.dp-trg { display: table-row-group; }
```

### Multi-column - area
```css
.cc-a {
  -webkit-column-count: auto;
  -o-column-count: auto;
  column-count: auto;
}

.cc-1 {
  -webkit-column-count: 1;
  -o-column-count: 1;
  column-count: 1;
}
...
.cc-4 {
  -webkit-column-count: 4;
  -o-column-count: 4;
  column-count: 4;
}
.cc-5 {
  -webkit-column-count: 5;
  -o-column-count: 5;
  column-count: 5;
}
```

### opcaity - appearance
```css
.op-0 { opacity:   0; }
.op-1 { opacity: 0.1; }
...
.op-9 { opacity: 0.9; }
.op-10 { opacity: 1.0; }
```

***\*\*\*more\*\*\****
