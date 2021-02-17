
# Welcome to Swaroop's Markdown CheatSheet 


![swaroop-and-dex-tahoe](https://i.imgur.com/XO8h0c8.jpg)


## Text Formatting
- *Italicize*  - by using one a set of one *s around the text.  

- **Bold**  - by using set of two *s around the text.

- Underline - Tough Luck, apparently markdown doesn't have a definte syntax to underline. :(

- ~~Strikeout~~ - Use ~~ symbols around the text for strikeout.  

- > Block Quotes - Create block quotes by using the ">" symbol at the beginnign of sentesces.
   It will add a block as such this. The  text will keep wrapping in the block, until there's an empty line is added. 

- Bulleted Lists (Using the '-' hyphen symbol, and indentation to create sub lists)
   - List 1
      - Sublist 1
      - Sublist 2
   - List 2
   - List 3

- Numbered Lists (Use the number 1 to create numbered lists. You can use bulleted sublists within numbered lists)
   1. This is how
      - bulleted list
      - within numbered list
   1. you create
   1. a numbered list

- Single line Code formatting `<span id="mySpan">Test</span>` - Surround desired text with (`) uptick symbols to format code style

\
Code Format:
 ```
*Italicize*  

**Bold**  

Underline (lol)

~~Strikeout~~ 

> Block Quotes - Create block quotes by using the ">" symbol at the beginnign of sentesces.
   It will add a block as such this. The  text will keep wrapping in the block, until there's an empty line is added. 

Bulleted Lists
   - List 1
      - Sublist 1
      - Sublist 2
   - List 2
   - List 3

Numbered Lists
   1. This is how
      - bulleted list
      - within numbered list
   1. you create
   1. a numbered list
```
 

## Linking URLs or Images 
You can create links to navigate to URLs. For eg: Go to [Reddit-Reddevils](https://https://www.reddit.com/r/reddevils/), which is formatted as below: 

You can also show Images like the one above using the format below:
```
Normal Text:
[Reddit-Reddevils](https://https://www.reddit.com/r/reddevils/)

Images: (Use ! at the beginning)
![swaroop-and-dex-tahoe](https://i.imgur.com/XO8h0c8.jpg)

```



## Creating a table
Code Format:
```
**Number**|**Player Name**|**Position**|
|-------------|-------------|-------------|
|9|Anthony Martial|Striker
|23|Luke Shaw|Left Back
|10|Marcus Rashford| Left Winger
|18|Bruno Fernandes|Attacking Midfielder
|7|Edinson Cavani|Striker
|6|Paul Pogba|Defensive Midfielder
```
Output:
**Number**|**Player Name**|**Position**|
|-------------|-------------|-------------|
|9|Anthony Martial|Striker
|23|Luke Shaw|Left Back
|10|Marcus Rashford| Left Winger
|18|Bruno Fernandes|Attacking Midfielder
|7|Edinson Cavani|Striker
|6|Paul Pogba|Defensive Midfielder


## Code Block
Use (```) (three uptick symbols) to start and end a code block 

Code Format:

![test](https://i.imgur.com/KnF3OLA.png)


Output
```
function myFunction(name){
   console.log(name + " is just messing around with markdown syntax");
} 

```












