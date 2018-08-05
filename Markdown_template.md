---
layout: tutorial_hands_on
topic_name: training
tutorial_name: create-new-tutorial
---

# Les listes ordonnées

1. Item 1
2. Item 2
3. Item 3
  1. Item 3a
  2. Item 3b
    1. Item 1
    2. Item 2
    3. Item 3 
      1. Item 3a
      2. Item 3b


# Les emphases
###### le plus petit des titres

Emphasis, aka italics, with *asterisks* or _underscores_.
Strong emphasis, aka bold, with **asterisks** or __underscores__.
Combined emphasis with **asterisks and _underscores_**.
Strikethrough uses two tildes. ~~Scratch this.~~

# Les liens

[I'm an inline-style link](https://www.google.com)
[I'm an inline-style link with title](https://www.google.com "Google's Homepage")
[I'm a reference-style link][Arbitrary case-insensitive reference text]
[I'm a relative reference to a repository file](../blob/master/LICENSE)
[You can use numbers for reference-style link definitions][1]
Or leave it empty and use the [link text itself].
URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

# Les logos

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
Reference-style: 
![alt text][logo]
[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

#Les images avec légendes

![A textual description of the image](../images/image.png "This is my super caption")

# Les scripts

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
```python
s = "Python syntax highlighting"
print s
```
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

# Les tableaux

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

# Les émoticons

:+1:
:smile:

# Les Vidéos

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

# Horizontal rules

First option
---
Second option
___

# Les HANDS-ON Box

### {% icon hands_on %} Hands-on: Spliced mapping

1. **RNA STAR** {% icon tool %}: Map your reads on the reference genome with
  - *"Single-end or paired-end reads"*:  `Paired-end (as individual datasets)`
  - *"RNA-Seq FASTQ/FASTA file, forward reads"*: the generated `trimmed reads pair 1` files (multiple datasets)
  - *"RNA-Seq FASTQ/FASTA file, reverse reads"*: the generated `trimmed reads pair 2` files (multiple datasets)
  - *"Custom or built-in reference genome"*: `Use a built-in index`
  - *"Reference genome with or without an annotation"*: `use genome reference without builtin gene-model`
  - *"Select reference genome"*: `Drosophila Melanogaster (dm6)`
  - *"Gene model (gff3,gtf) file for splice junctions"*: the imported `Drosophila_melanogaster.BDGP6.87.gtf`
  - *"Length of the genomic sequence around annotated junctions"*: `36`

        This parameter should be length of reads - 1

2. **MultiQC** {% icon tool %}: Aggregate the STAR logs with
  - *"Which tool was used generate logs?"*: `STAR`
  - *"Type of FastQC output?"*: `Log`
  - *"STAR log output"*: the generated `log` files (multiple datasets)
{: .hands_on}

# Les ToDO List

- [x] this is a complete item 
- [ ] this is an incomplete item 
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported 
- [x] list syntax required (any unordered or ordered list supported)

