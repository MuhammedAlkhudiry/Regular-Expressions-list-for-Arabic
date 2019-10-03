# Regular-Expressions-list-for-Arabic
Regular expressions that helps for processing Arabic text.  
Note: this repo uses JavaScript syntax for regular expressions.

## All Arabic Characters

| Description  | Regular Expression |
| ------------- | ------------- |
| All Arabic characters (1)  | [ء-ي] |
| All Arabic characters (2)  | [\u0600-\u06FF]   |
| Arabic & Persian characters  | [گچپژیلفقهمو ء-ي] |
| Arabic & Persian characters & Hindu–Arabic numbers | [؀-ۿ] |


## Some Arabic Characters

| Description  | Regular Expression |
| ------------- | ------------- |
| All harakat (1)  | [ؐ-ًؚٟ]  |
| All harakat (2)  | [\u0617-\u061A\u064B-\u0652] |
| Arabic & Persian characters  | [گچپژیلفقهمو ء-ي] |
| Hindu–Arabic numbers only  |[\u0660-\u0669]  |

## Sentences

| Description  | Regular Expression |
| ------------- | ------------- |
| Arabic word | \b(\w*[ء-ي]\w*)\b  |


