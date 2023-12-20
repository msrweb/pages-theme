---
title: "Quick-Start Guide"
permalink: /docs/quick-start-guide/
excerpt: "Get started nullam suscipit dolor."
last_modified_at: 2023-12-01
toc: true
classes: wide
---

Nullam suscipit, lorem sed sollicitudin tempus, libero diam dapibus dolor, semper semper elit arcu sed justo. Sed molestie, ligula id lobortis cursus, lorem lacus fermentum odio, eu lacinia nunc nisi eget orci. Quisque ornare purus eget elit sodales interdum at id nisi. Morbi mollis ultrices venenatis. Cras et mauris lectus.

# Installation Steps

1. Nullam suscipit, lorem sed sollicitudin tempus, libero diam dapibus dolor, semper semper elit arcu sed justo.
2. Sed molestie, ligula id lobortis cursus, lorem lacus fermentum odio, eu lacinia nunc nisi eget orci. Quisque ornare purus eget elit sodales interdum at id nisi.
3. Morbi mollis ultrices venenatis.
4. Cras et mauris lectus. Vivamus velit risus, porttitor eget fringilla quis, laoreet in dui.
5. Maecenas eu molestie massa. Vestibulum nunc massa, consectetur ut fringilla vitae, eleifend et nisl.
6. Donec blandit est a nibh ornare dictum. Vestibulum vulputate viverra tellus, in pulvinar risus euismod eget.

Suspendisse vulputate blandit dui eu volutpat [here](#). Cras vitae risus ipsum. Nam lacinia porttitor mauris, et ullamcorper sem adipiscing ac. Aliquam id nisi eu lectus placerat tristique at at mauris. Fusce nibh ante, interdum sit amet ullamcorper sed, convallis sit amet ligula. Vivamus eu laoreet lorem. Curabitur sit amet metus eu nunc tincidunt eleifend a eu justo. Aenean non ante id ligula vestibulum venenatis vel at justo. Suspendisse rhoncus volutpat lacus sit amet luctus. Aliquam erat volutpat. Praesent vitae eros ac leo iaculis cursus. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Suspendisse vitae lorem sit amet turpis cursus fermentum. Nulla rhoncus hendrerit odio, vel cursus risus vulputate ut. Proin eros turpis, facilisis ut tincidunt et, mollis venenatis nisi. Phasellus in mi vel mi eleifend consectetur.

# Code Example

```cs
const hashValue = val =>
  crypto.subtle
    .digest('SHA-256', new TextEncoder('utf-8').encode(val))
    .then(h => {
      let hexes = [],
        view = new DataView(h);
      for (let i = 0; i < view.byteLength; i += 4)
        hexes.push(('00000000' + view.getUint32(i).toString(16)).slice(-8));
      return hexes.join('');
    });

hashValue(
  JSON.stringify({ a: 'a', b: [1, 2, 3, 4], foo: { c: 'bar' } })
).then(console.log);
// '04aa106279f5977f59f9067fa9712afc4aedc6f5862a8defc34552d8c7206393'
```
