Anatomi / struktur css :
selector {property: value;}

Contoh
h1 {
  color: blue;
}

Embed html : <style> </style>
Inline : <p style="color: lightblue;"> ... </p>
External : <link rel="stylesheet" href="style.css">

Font :
font-family, font-size, font-weight(Ketebalan), font-variant, line-height

font-family : nama font, generic family

font-weight : lighter, normal, 100-900, bold, bolder

font-variant : normal, small-caps

font-style : normal, italic, oblique

line-height : normal, px, em

CSS font shorthand :
body {
  font-style : italic;
  font-variant : normal;
  font-weight : bold;
  font-size : 16px;
  line-height : 18px;
  font-family : helvetica, arial, sans-serif;
}
==>
body {
  font : italic, normal, bold, 16px, 18px, helvetica, arial, sans-serif;
}
<!-- Wajib urut -->

text : color, text-align, text-indent, text-decoration, text-transform, letter-spacing, word-spacing