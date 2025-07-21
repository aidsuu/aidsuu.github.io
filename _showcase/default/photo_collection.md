---
show: true
width: 4
date: 2021-09-12 00:01:00 +0800
height: 295px
images:
- src: assets/images/etc/catmew.jpg
  #title: Photo 1
  #desc: Description 1.
  #link: https://picsum.photos/
- src: assets/images/etc/cating.jpg
  #title: Photo 2
  #desc: Description 2
- src: assets/images/etc/catbrow.jpg
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
