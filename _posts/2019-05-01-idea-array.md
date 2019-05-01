---
layout: post
title: join()을 이용한 반복
tags:
  - Idea
  - Array
---

```javascript
var megalomaniac = {
  mastermind : "Brain",
  henchman: "Pinky",
  battleCry: function (noOfBrains) {
    return "They are " + this.henchman + " and the" +
      Array(noOfBrains + 1).join(" " + this.mastermind);
  }
};
var battleCry = megalomaniac.battleCry(4);
// "They are Pinky and the Brain Brain Brain Brain Brain"
// 반복하고 싶은 만큼 빈 배열 만든 다음 join()으로 반복할 내용을 넣음
```

###### 참고
[Javascript Koans](https://github.com/mrdavidlaing/javascript-koans)
