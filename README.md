
# Swaroop and Dexter's Markdown CheatSheet 


![swaroop-and-dex-tahoe](https://i.imgur.com/XO8h0c8.jpg)


## Text Formatting
- _Italicize_  - Wrap text with (_) underscore symbol.  

- **Bold**  - Wrap text with set of two *s.

- **_Bold AND Italicize_**  - Wrap text with (**_).  

- ~~Strikeout~~ - Use ~~ Wrap text with (~~) symbols around the text for strikeout.  

- Single line Code formatting `<span id="mySpan">Test</span>` - Surround desired text with (`) uptick symbols to format code style

- Underline - Tough Luck, apparently markdown doesn't have a definte syntax to underline. :(
```
   _Italicize_  

   **Bold**  

   **_Bold AND Italicize_** 

   ~~Strikeout~~ 

   Single line code formatting: `<span id="mySpan">Test</span>`

   Underline (lol)
```


|
## Block Quotes
   > Block Quotes - Create block quotes by using the ">" symbol at the beginnign of sentences. It will add a block as 
   > such this. The  text will keep wrapping in the block, until there's an empty line is added. 
``` 
   > Block Quotes - Create block quotes by using the ">" symbol at the beginnign of sentences. It will add a block as 
   > such this. The  text will keep wrapping in the block, until there's an empty line is added. 
```
|
## Creating Lists

Unordered Lists (Using the '-' hyphen symbol, and indentation to create sub lists)
   - This is how
      - Sublist 1
      - Sublist 2
   - you create
   - an unordered list

Ordered Lists (Use the number 1 to create ordered lists. You can use unordered sublists within ordered lists)
   1. This is how
      - unordered list
      - within an ordered list
   1. you create
   1. an ordered list



\
Code Format:
 ```
   Unordered Lists
      - List 1
         - Sublist 1
         - Sublist 2
      - List 2
      - List 3

   Ordered Lists
      1. This is how
         - unordered list
         - within ordered list
      1. you create
      1. a numbered list
```
 
|
## Linking URLs or Images 
You can create links to navigate to URLs. For eg: Go to [Reddit-Reddevils](https://https://www.reddit.com/r/reddevils/), which is formatted as below: 

You can also show Images like the one above using the format below:
```
Normal Text:
[Reddit-Reddevils](https://https://www.reddit.com/r/reddevils/)

Images: (Use ! at the beginning)
![swaroop-and-dex-tahoe](https://i.imgur.com/XO8h0c8.jpg)

```


|
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

|
## Code Block
Use (```) (three uptick symbols) to start and end a code block 

Code Format:

![test](https://i.imgur.com/KnF3OLA.png)


Output:
```
function myFunction(name){
   console.log(name + " is just messing around with markdown syntax");
} 

```

|










