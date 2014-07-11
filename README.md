# sidetip.js

### A jQuery plugin for displaying tooltip off the the side
# When doing the position it will do the opposite if there is not enough room. IE if set to left it will go on the right.

## Options
- delay			: The delay on hover the sidetip fades in (default 400)
- sideOffset	: The distance offset (default 10)
- url			: The url of the content that will be sidetipped
- ele			: The id of a hidden element with the content to be sidetipped
- html			: The html of the content to be sidetipped
- pos			: The position the side tip will go (default right. Other options top, left, bottom)

## Usage

```javascript
$('elementToTrigger').sidetip(options);
```