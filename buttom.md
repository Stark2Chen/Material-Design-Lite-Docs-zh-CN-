# 按钮

## 材料设计中按钮的

彩色FAB 按钮

```html

<!-- Colored FAB button -->

<button class="mdl-button mdl-js-button mdl-button--fab mdl-button--colored">

<i class="material-icons">add</i>

</button>

```

有涟漪特效的FAB按钮

```html

<!-- Colored FAB button with ripple -->

<button class="mdl-button mdl-js-button mdl-button--fab mdl-js-ripple-effect mdl-button--colored">

<i class="material-icons">add</i>

</button>

```

普通的白色FAB按钮

```html

<!-- FAB button -->

<button class="mdl-button mdl-js-button mdl-button--fab">

 <i class="material-icons">add</i>

</button>

```

包含涟漪特效

```html

<!-- FAB button with ripple -->

<button class="mdl-button mdl-js-button mdl-button--fab mdl-js-ripple-effect">

 <i class="material-icons">add</i>

</button>

```

禁止按下

```html

<!-- Disabled FAB button -->

<button class="mdl-button mdl-js-button mdl-button--fab" disabled>

 <i class="material-icons">add</i>

</button>

```

悬浮按钮

```html

<!-- Raised button -->

<button class="mdl-button mdl-js-button mdl-button--raised">

 Buttonj

</button>

```

包含涟漪特效的悬浮按钮

```html

<!-- Raised button with ripple -->

<button class="mdl-button mdl-js-button mdl-button--raised mdl-js-ripple-effect">

 Button

</button>

```

禁止按下

```html

<!-- Raised disabled button -->

<button class="mdl-button mdl-js-button mdl-button--raised" disabled>

 Button

</button>

```

彩色悬浮按钮

```html

<!-- Colored raised button -->

<button class="mdl-button mdl-js-button mdl-button--raised mdl-button--colored">

 Button

</button>

```

使用强调色

```html

<!-- Accent-colored raised button -->

<button class="mdl-button mdl-js-button mdl-button--raised mdl-button--accent">

 Button

</button>

```

包含涟漪特效

```html

<!-- Accent-colored raised button with ripple -->

<button class="mdl-button mdl-js-button mdl-button--raised mdl-js-ripple-effect mdl-button--accent">

 Button

</button>

```

扁平按钮

```html

<!-- Flat button -->

<button class="mdl-button mdl-js-button">

 Button

</button>

```

包含涟漪特效

```html

<!-- Flat button with ripple -->

<button class="mdl-button mdl-js-button mdl-js-ripple-effect">

 Button

</button>

```

禁止按下

```html

<!-- Disabled flat button -->

<button class="mdl-button mdl-js-button" disabled>

 Button

</button>

```

主要色彩色扁平按钮

```html

<!-- Primary-colored flat button -->

<button class="mdl-button mdl-js-button mdl-button--primary">

 Button

</button>

```

强调色彩色扁平按钮

```html

<!-- Accent-colored flat button -->

<button class="mdl-button mdl-js-button mdl-button--accent">

 Button

</button>

```

图标按钮

```html

<!-- Icon button -->

<button class="mdl-button mdl-js-button mdl-button--icon">

 <i class="material-icons">mood</i>

</button>

```

彩色图标按钮

```

<!-- Colored icon button -->

<button class="mdl-button mdl-js-button mdl-button--icon mdl-button--colored">

 <i class="material-icons">mood</i>

</button>

```

小型FAB按钮

```html

<!-- Mini FAB button -->

<button class="mdl-button mdl-js-button mdl-button--fab mdl-button--mini-fab">

 <i class="material-icons">add</i>

</button>

```

彩色小型FAB按钮

```html

<!-- Colored mini FAB button -->

<button class="mdl-button mdl-js-button mdl-button--fab mdl-button--mini-fab mdl-button--colored">

 <i class="material-icons">add</i>

</button>

```

## 介绍

Material Design Lite中的按钮是对标准HTML中```<buttom>```元素的增强。按钮包括文本和图像。他能够清楚的告诉用户点击或是触摸他时将会发生什么动作。MDL按钮组件提供了很多按钮的类型，并且允许你自行添加显示和点击的效果。

无论网站的内容和功能如何，按钮在大多数用户界面都会存在。因此，按钮的设计和使用将会对整体用户体验产生重要的影响。这一点在材料[设计标准页面](http://www.google.com/design/spec/components/buttons.html)中有所涉及

可以使用的按钮显示类型分为平，突起，FAB（Google翻译为晶圆厂），小型FAB和图标。他们可以使用默认颜色（浅灰色），也可以着色。可以通过代码实现禁止点击的效果。FAB按钮和图标按钮通常使用图标而不是文字作为标题。

需要包括MDL的组件

1. 一个```<bottom>```元素，应当包含任何所需要的属性和值，例如id和事件处理程序，并根据西药添加文字说明或图片

   ```html
   <button>Save</button>
   ```

2. 添加一个或多个MDL类，在```<bottom>```标签中使用空格隔开，以使用该按钮的```class```属性

   ```html
   <button class="mdl-button mdl-js-button mdl-button--raised">Save</button>
   ```


