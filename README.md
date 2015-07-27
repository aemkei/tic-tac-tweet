# Tic-Tac-Tweet
## Tic Tac Toe in a Tweet

A simplified version of the classic game in exactly 140 characters of HTML and JavaScript. The playfield is represented by 3x3 text-input fields. Instead of using `x` and `o`, this version uses binary representations `0` and `1`.

### Instructions

Click a field to set the next mark. The game will only allow a new placement if the field was empty. Once the player marked three fields (horizontal, vertical, or diagonal) and alert will show the winner.

### Demo

[PLAY THE DEMO](http://rawgit.com/tic-tac-tweet/ping/master/tweet.html)!

### Tweet Sized HTML (140 characters)

```html
<svg onload=eval(unescape(escape('𩡯𬠨𨐽𦱝𛁩🐱𜠻𛐭𪐻𨑛𪑝🐹𛁒🐯𚀰𯀱𚐨𧀱𯀮𛠨𧀱𯀮𧀱𛡼𛠮𧀱𛠮𚐮𛠩𧀱𛰩𩁯𨱵𫑥𫡴𛡷𬡩𭁥𚁩𙐴🰢🁩𫡰𭑴𘁯𫡣𫁩𨱫👶𨑬𭑥𯁼𚁡𦰢𚱩𚰢𧐽𭡡𫁵𩐽𪑞🐱𚐻𤠮𭁥𬱴𚁡𛡪𫱩𫠨𙰧𚐩𙠦𨑬𩑲𭀨𪐩🠢𞠢🁢𬠾𘠩').replace(/uD./g,'')))>
```

### Uncompressed Source (163 bytes)

```js
for(a=[i=12];i;a[i]=9,R=/(0|1)(\1|..(\1|.\1.
|..\1..)..)\1/)document.write(--i%4?"<input
onclick=value||(a["+i+"]=value=i^=1);R.test(
a.join(''))&&alert(i)>":"<br>")
```

### Gameplay Video

![Tic-Tac-Tweet](https://raw.githubusercontent.com/aemkei/tic-tac-tweet/master/tic-tac-tweet.gif)

### Thanks

RegEx by https://gist.github.com/Davidebyzero/9090628, compressed using http://xem.github.io/obfuscatweet.
