# unlike-tweets

1. Go to your **Likes** page on X (e.g. `https://www.x.com/username/likes`).
2. Open **Developer Tools** (`F12` or `Ctrl+Shift+I`).
3. Paste the code (if you can't paste, type `allow pasting`).
```javascript
let d=3000,h=0,a=0,m=5;function s(){window.scrollTo(0,document.body.scrollHeight);}function c(){document.querySelectorAll('button[data-testid="unlike"]').forEach(b=>b.click());}function k(){c();s();if(window.scrollY>=h&&a<m){h=document.body.scrollHeight;a++;}else if(a>=m){console.log("done");}}setInterval(k,d);
```
4. Done.

---
Made with ❤️
