
# What about

This is source code **beautiful QR code generator** served at "[おしゃれ！美しい QRコード作成ツール](https://tech-landlord.com/beautiful-qr-code-generator/)" on [tech-landlord.com](https://tech-landlord.com).

It's pure JavaScript (Vanilla.js) and able to deploy any WP site.

Only dependency is [qr-code-styling](https://github.com/kozakdenys/qr-code-styling) JS library on CDN.


# Develop

To run with the code, use VS code and __Live Server__ extension.

Start Live Server from the status bar on bottom of VS code screen, and then open browser at http://localhost:5500.

> [!NOTE]
> All URLs for images are hosted on [tech-landlord.com](https://tech-landlord.com) which disables CORS. That is, you may not properly run this code on other origin. 
> Change all Urls before running.

# Deploy

You can this code in your WordPress just to copy & paste.

## 1. Open index.html

Open __index.html__ in top directory of this repository.

## 2. Copy the code

Copy code from the line just after:

```html
    <!---
      これ以降をカスタムHTMLブロックにいれる
    -->
```

, to the line before:
```html
    <!---
    ここまで
    -->
```

## 3. Create 'Custom HTML' block in WordPress

Create __'Custom HTML'__ block on any page created in your WordPress, and then, paste the code above.

That's it!

# License

MIT
