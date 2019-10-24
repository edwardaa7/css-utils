# css-utils
General CSS utility class<br />
<br />

Inspired by [tachyons-css](https://github.com/tachyons-css/tachyons/). This is a SCSS version of a subset of tacyhons' features, things that I mostly use in my front-end projects.<br />
<br />

## Functionality

**Margin**<br />
```
ma-* for all margins
mt-*, mb-*, ml-*, mr-* classes for directional margin
mh-* for horizontal margins
mv-* for vertical margins

* can take the value of 0 to 100, for example:

.ma-10 {
    margin: 10px;
}

.mt-10 {
    margin-top: 10px;
}

.mh-10 {
    margin-left: 10px;
    margin-right: 10px;
}
```

**Padding**<br />
```
pa-* for all padding
pt-*, pb-*, pl-*, pr-* classes for directional margin
ph-* for horizontal margins
pv-* for vertical margins

* can take the value of 0 to 100, for example:

.pa-10 {
    padding: 10px;
}

.pt-10 {
    padding-top: 10px;
}

.ph-10 {
    padding-left: 10px;
    padding-right: 10px;
}
```


**Border width**<br />
```
bw-* for all borders
bw-t-*, bw-b-*, bw-l-*, bw-r-* for directional borders

* can take the value of 0 to 20, for example:

.bw-10 {
    border-width: 10px;
}

.bw-t-10 {
    border-top-width: 10px;
}
```

**Border radius**<br />
```
br-* for all borders
br-tl-*, br-tr-*, br-bl-*, br-br-* for corner borders

* can take the value of 0 to 20, for example:
tl = top-left
tr = top-right
bl = bottom-left
br = bottom-right

.br-10 {
    border-radius: 10px;
}

.br-tl-10 {
    border-top-left-radius: 10px;
}
```

**Border style**<br />
```
.bs-solid {
    border-style: solid;
}
.bs-dotted {
    border-style: dotted;
}
```

**No border**<br />
```
nb for all borders
nb-t, nb-b, nb-l, nb-r for directional borders

.nb {
    border: none;
}

.nb-t {
    border-top: none;
}
```

**Font size**<br />
```
fs-*

* can take the value of 0 to 36, for example:

.fs-12 {
    font-size: 12pt;
}
```

**Font weight**<br />
```
fw-*

* can take the value of 100 to 900 (increments of 100), and text values
lighter, normal, bold, bolder


Example:
.fw-100 {
    font-weight: 100;
}

.fw-500 {
    font-weight: 500;
}

.fw-bold {
    font-weight: bold;
}
```

**Line height**<br />
```
lh-*

* can take the value of 0 to 36, for example:

.lh-12 {
    line-height: 12pt;
}
```

**Width classes**<br />
```
.w1 { width: 1rem; }
.w2 { width: 2rem; }
.w3 { width: 4rem; }
.w4 { width: 8rem; }
.w5 { width: 16rem; }

Also, w-*

* can take the value of 1 to 100 (in percentage), for example:

.w-50 {
    width: 50%;
}
```

**Height classes**<br />
```
.h1 { height: 1rem; }
.h2 { height: 2rem; }
.h3 { height: 4rem; }
.h4 { height: 8rem; }
.h5 { height: 16rem; }

Also, h-*

* can take the value of 1 to 100 (in percentage), for example:

.h-50 {
    height: 50%;
}
```
