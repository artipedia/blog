---
title: Mulai Menulis Artikel
description: Mulai menulis artikel di artipedia, pertama pelajari format penulisan, mendaftar di github, dan fork repository.
permalink: /docs/mulai-menulis-artikel/
---
* TOC
{:toc}
## Contoh Cara Penulisan
```
---
layout: news_item
title: "Judul Artikel"
date: "2018-02-19"
author: artipedia
categories: [referensi]
---
## SubJudul
lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum 
lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum 
lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum
lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum 
 lorem ipsum lorem ipsum lorem ipsum.

lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum 
lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum 
lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum
lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum 
 lorem ipsum lorem ipsum lorem ipsum.


```


### Keterangan :
1. title : "Isi dengan Judul Artikel Anda".
2. date : "Isi dengan tanggal dengan format Tahun-bulan-tanggal".
3. author : "Isi dengan username github anda".
4. categories: "isi dengan kategori artikel".

## Format Penulisan 

### Paragraf
Paragraf ditulis dan dipisahkan dengan enter

### Header
Penulisan sub judul 

{% raw %}
```liquid
# Judul <h1> tag
## Sub Judul <h2> tag
### Sub Judul <h3> tag
#### Sub Judul <h4> tag
##### Sub Judul <h5> tag
###### This is an <h6> tag
```
{% endraw %}

Hasilnya
# Judul h1 
## Sub Judul h2 
### Sub Judul h3 
#### Sub Judul h4 
##### Sub Judul h5 
###### Sub Judul h6

## Bold
Menebalkan huruf terdapat dua cara
```
1. **Contoh**
2. __Contoh__.
```
Hasilnya
**Contoh**

## Italic
```
1. *Contoh*
2. _Contoh_.
```
Hasilnya
*Contoh*

## Link
Untuk menyisipkan link
```
1. [ArtiPedia](http://artipedia.id/)
2. [ArtiPedia](http://artipedia.id/ "Link dengan Atribut Title")
```
Hasilnya 
1. [ArtiPedia](http://artipedia.id/)
2. [ArtiPedia](http://artipedia.id/ "Link dengan Atribut Title")

## Image
```
1. Inline-style: 
![alt text](https://artipedia.id/img/logo-2x.png "Logo Title Text 1")

2. Reference-style: 
![alt text][logo]
[logo]: https://artipedia.id/img/logo-2x.png "Logo Title Text 2"
```

Hasilnya
1. Inline-style: 

![alt text](https://artipedia.id/img/logo-2x.png "Logo Title Text 1")

2. Reference-style: 

![alt text][logo]

[logo]: https://artipedia.id/img/logo-2x.png "Logo Title Text 2"

## Blockquote
Untuk menambahkan <code>blockquote</code> tambahkan <code>></code> sebelum/pada awal paragraf
```
> Tes penulisan blockquote
```
Hasilnya
> Tes penulisan blockquote

<nav class='main-nav'><ul>
<li class="current">
    <a href="https://github.com/ArtiPedia/blog/new/master/docs/_posts/">Mulai</a>
  </li></ul></nav>

