# docsie-script-starter-style
######  Getting the Docsie style starter kit

To jump-start with the custom styling simply clone the [docsie-script-starter-style](https://github.com/LikaloLLC/docsie-script-starter-style) project from our [github repository](https://github.com/LikaloLLC/docsie-script-starter-style).

```
git clone https://github.com/LikaloLLC/docsie-script-starter-style.git
cd docsie-script-starter-style
```

The style starter is written is SCSS format, which needs to be converted to standard CSS before it can be used on your Docsie pages:
```
npm i
```

followed by:
```
npm run build
```

This command will generate a build/ folder with style.css

Then you simply add the style css onto the page where Docsie script is running and give your documentation the visual UMPH it deserves.

For more information about the structure of the Docsie style please [read-on the styling guide](?version=1.4.5&language=EN&article=base-style#section-page-header).
