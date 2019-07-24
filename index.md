
## Markdown Notes 


***


# Heading1

## Heading2

### Heading3

#### Heading4

**Bold**

_Italic_

## Horizontal lines
----

***

## A code block
```js
const arrowFunc = (param1, param2)=>{
	// do something here
	console.log(`${param1}, ${param2}`)
}
```
***

## Inline Code Block

An inline code snippet `const hey = "ho"`

***

## Create your own code diff

```diff
var x = 100;
-- var y = 250;
++ var y = 350

or

var x = 100;
- var y = 99;
+ var y = 101

```

***

## 'Strike-Out' some words;
The following text will be struck out; ~~dont delete me~~

***

Link with explicit URL:  <https://www.davidodonovan.com/>

Link from some text: [my github account](https://github.com/DavidODonovan/)

Link with hover text: [davidodonovan.com](https://www.davidodonovan.com "Personal www pages of David O'Donovan")

***

## More advanced links using variables as your links;

[a cool site][amazing]

[amazing]: http://www.themostamazingwebsiteontheinternet.com

[incredible][amazing]

[this site is amazing!][amazing]

***

### Links to Anchors on Same Page:

[Take me to..](#abcd).

Here is the linked anchor text! <a name="abcd"></a>

## Images

Format for images is;

bang, square-brackets, parentheses;
```md
![]()

```
![this image retro-cool](legends.jpg)

***

## Unordered list with bullet points

+ an item
+ another item
+ yet another item

***

**Block Quotes**

start with a chevron:
 > This is a block quote and it will continue for quite some time. I can write like this forever and ever and I will be block quoted.

***

## Tables

Tables can be created quite easily, like so:

|Country | Population |
|:----------|:----------:|
|China|1415046000|
|India|1354052000|
|United States|326767000|
|Indonesia|266795000|
|Brazil|210868000|
|Pakistan|200814000|
|Nigeria|195875000|
|Bangladesh|166368000|
|Russia|143965000|
|Mexico|130759000|

Note you can change the location of the colons to change the justification of text in the columns

-----------------

## some mathjax notation;
\\[{c} = \lambda\nu\\]
\\[ {e}^{i\pi } 1=0 \\]

***
