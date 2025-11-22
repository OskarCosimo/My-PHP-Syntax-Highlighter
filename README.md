# Getting Started - My PHP Syntax Highlighter

## How to Use

### Automatic Features (No Configuration Required)

The extension works automatically on all `.php` files:

1. **PHP Tag Highlighting**
   - Open any `.php` file
   - Tags `<?php`, `<?`, and `?>` are automatically highlighted in **goldenrod bold**

2. **Bracket Matching**
   - Position your cursor on any `(`, `)`, `{`, `}`, `[`, or `]`
   - The matching bracket is highlighted with a **goldenrod background**

3. **Control Structure Highlighting**
   - Place your cursor on any PHP control keyword:
     - `if`, `elseif`, `else`, `endif`
     - `foreach`, `endforeach`
     - `for`, `endfor`
     - `while`, `endwhile`
     - `switch`, `endswitch`
   - The **entire chain** is highlighted with a **lime-yellow background**

4. **Quote Matching**
   - Click on a `"` or `'` quote
   - The matching opening/closing quote is highlighted with a **light blue background**

5. **Syntax Error Detection**
   - Red squiggles appear automatically for:
     - Missing semicolons at end of statements
     - Unbalanced brackets/braces
     - Variables without `$` prefix
   - Hover over the red squiggle to see the error message

## Color Scheme

| Element | Background Color | Text Color |
|---------|------------------|------------|
| PHP Tags | - | Goldenrod (bold) |
| Brackets | Goldenrod dark | Blue |
| Control Structures | Lime-yellow | Blue |
| Quotes | Light blue | - |
| Syntax Errors | - | Red (squiggle) |

## Performance

The extension is optimized for large files:
- Syntax checks run only 500ms after you stop typing
- No impact on editor responsiveness

## Supported Syntax

Works with both PHP syntaxes:

```php
// Standard syntax
if ($condition) {
    echo "test";
}

// Alternative syntax
if ($condition):
    echo "test";
endif;
```

## Troubleshooting

### Extension not working?
1. Restart Visual Studio
2. Verify the file has `.php` extension
3. Check that the file is recognized as PHP in the bottom status bar

### Performance issues?
- The extension automatically adds a 500ms delay before checking syntax
- If you experience slowness with very large files (>500KB), consider splitting them

## Feedback & Support

- Report bugs: [https://github.com/OskarCosimo/My-PHP-Syntax-Highlighter/issues](https://github.com/OskarCosimo/My-PHP-Syntax-Highlighter/issues)
- Feature requests: [https://github.com/OskarCosimo/My-PHP-Syntax-Highlighter/discussions](https://github.com/OskarCosimo/My-PHP-Syntax-Highlighter/discussions)
- Developers official blog: [https://blog.myetv.tv/2025/11/21/my-php-syntax-highlighter-for-visual-studio/](https://blog.myetv.tv/2025/11/21/my-php-syntax-highlighter-for-visual-studio/)

  ## Official Visual Studio Market Extension
  You can find it here: [https://marketplace.visualstudio.com/items?itemName=MYETV.mpsh
](https://marketplace.visualstudio.com/items?itemName=MYETV.mpsh)
Thank you for using My PHP Syntax Highlighter! 💙
