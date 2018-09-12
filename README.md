# Notebook UI Theme for Atom

Notebook themed UI based on Atom One Light.

![One light UI](https://cloud.githubusercontent.com/assets/378023/26246819/0826f04e-3cd6-11e7-98eb-cd94bc48b090.png)

> The font used in the screenshot is [Fira Code iScript](https://github.com/kencrocken/FiraCodeiScript).

## Settings

In the theme settings you can:

- Change the __Font Size__ to scale the whole UI up or down.
- Choose between 3 __Tab Sizing__ modes.
- Hide the  __dock buttons__.

To make changes, go to `Settings > Themes > One Light UI > Settings` or the cog icon next to the theme picker.


### Customize

It's also possible to resize only certain areas by adding the following to your `styles.less` (Use DevTools to find the right selectors):

```css
.theme-one-light-ui {
  .tab-bar { font-size: 18px; }
  .tree-view { font-size: 14px; }
  .status-bar { font-size: 12px; }
}
```
