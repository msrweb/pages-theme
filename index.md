---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/banner-gradient.jpg
  actions:
    - label: "Get Started"
      url: "#"
excerpt: >
  Description about this project uscipit, lorem sed sollicitudin tempus, libero diam dapibus dolor, semper semper.<br />
  <small><a href="#">Latest release v2.5.0</a></small>
feature_row:
  - image_path: assets/images/feature-image-1.jpg
    alt: "Feature One image description"
    title: "Feature One"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/images/feature-image-2.jpg
    alt: "Feature Two image description"
    title: "Feature Two"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/images/feature-image-3.jpg
    alt: "Feature Three image description"
    title: "Feature Three"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row %}

Nullam suscipit, lorem sed sollicitudin tempus, libero diam dapibus dolor, semper semper elit arcu sed justo. Sed molestie, ligula id lobortis cursus, lorem lacus fermentum odio, eu lacinia nunc nisi eget orci. Quisque ornare purus eget elit sodales interdum at id nisi. Morbi mollis ultrices venenatis. Cras et mauris lectus.

# Key Features

1. Nullam suscipit, lorem sed sollicitudin tempus, libero diam dapibus dolor, semper semper elit arcu sed justo.
2. Sed molestie, ligula id lobortis cursus, lorem lacus fermentum odio, eu lacinia nunc nisi eget orci. Quisque ornare purus eget elit sodales interdum at id nisi.
3. Morbi mollis ultrices venenatis.
4. Cras et mauris lectus. Vivamus velit risus, porttitor eget fringilla quis, laoreet in dui.
5. Maecenas eu molestie massa. Vestibulum nunc massa, consectetur ut fringilla vitae, eleifend et nisl.
6. Donec blandit est a nibh ornare dictum. Vestibulum vulputate viverra tellus, in pulvinar risus euismod eget.

Suspendisse vulputate blandit dui eu volutpat [here](#). Cras vitae risus ipsum. Nam lacinia porttitor mauris, et ullamcorper sem adipiscing ac. Aliquam id nisi eu lectus placerat tristique at at mauris. Fusce nibh ante, interdum sit amet ullamcorper sed, convallis sit amet ligula. Vivamus eu laoreet lorem. Curabitur sit amet metus eu nunc tincidunt eleifend a eu justo. Aenean non ante id ligula vestibulum venenatis vel at justo. Suspendisse rhoncus volutpat lacus sit amet luctus. Aliquam erat volutpat. Praesent vitae eros ac leo iaculis cursus. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Suspendisse vitae lorem sit amet turpis cursus fermentum. Nulla rhoncus hendrerit odio, vel cursus risus vulputate ut. Proin eros turpis, facilisis ut tincidunt et, mollis venenatis nisi. Phasellus in mi vel mi eleifend consectetur.

# News and Updates

* Version 2.5 nullam suscipit, lorem sed sollicitudin tempus, libero diam dapibus dolor, semper semper elit arcu sed justo. Sed molestie, ligula id lobortis cursus, lorem lacus fermentum odio.

* Version 2 lacinia nunc nisi eget orci. Quisque ornare purus eget elit sodales interdum at id nisi. Morbi mollis ultrices venenatis. Cras et mauris lectus. Vivamus velit risus, porttitor eget fringilla quis, laoreet in dui. Maecenas eu molestie massa. Vestibulum nunc massa, consectetur ut fringilla vitae, eleifend et nisl. Donec blandit est a nibh ornare dictum.

* Version 1.8 Vestibulum vulputate viverra tellus, in pulvinar risus euismod eget. Pellentesque magna nisl, placerat convallis viverra vel, tincidunt at felis. Ut auctor fringilla risus, sed luctus lectus ultricies vitae. Praesent purus est, feugiat eu molestie ut, condimentum ac augue. Nam elit leo, tincidunt eu tristique quis, posuere in odio. Quisque sollicitudin suscipit dolor vestibulum euismod.

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