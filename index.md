---
layout: home-page
title: Home
order: 1
---
{% include author-box.html %}
<style></style>
.box {
  display: flex;
  align-items: flex-start;
  height: 200px;
}
.box>*:first-child {
  align-self: stretch;
}
.box .selected {
  align-self: center;
}
</style>

<body>

<div class="box">
  <div>One</div>
  <div>Two</div>
  <div class="selected">Three</div>
  <div>Four</div>
</div>  
</body>
