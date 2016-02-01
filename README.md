# Image Sprite Packer v1.0.0
ImageSpritePacker is a jQuery plugin that converts all your images into a single spritesheet and then positioned correctly so it doesn't interferred with your own CSS styles.

## How to Use (this plugin requires jQuery):
1. Include the `imagespritepacker.js` after importing jQuery.
2. To run the process of converting all images and positioning all at once, call `ImageSpritePacker("*");` for example in the Ready function or when you're done loading everything.
3. The `ImageSpritePacker` function contains 1 parameter, the `Filter Tag`, this is what should be converted of elements, if it contains an background image. Usually you want to set this to `"*"` to convert every element on the page.

## Future plans and WIP's features
- Currently this plugin only takes images that's been set through CSS on the `background-image` property, I'm working on making it listen on any Image, whether it be through an `img` tag or anything else.
- More settings: How sizing is handled, max drawcalls etc.

## Contact
You can contact me through email kevinjp@outlook.com if you have any questions or concerns.
