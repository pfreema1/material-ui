---
filename: /src/BottomNavigation/BottomNavigation.js
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# BottomNavigation



## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span style="color: #31a148">children *</span> | node |  | The content of the component. |
| classes | object |  | Useful to extend the style applied to components. |
| onChange | func |  | Callback fired when the value changes.<br><br>**Signature:**<br>`function(event: object, value: any) => void`<br>*event:* The event source of the callback<br>*value:* We default to the index of the child |
| showLabels | bool | false | If `true`, all `BottomNavigationAction`s will show their labels. By default, only the selected `BottomNavigationAction` will show its label. |
| value | any |  | The value of the currently selected `BottomNavigationAction`. |

Any other properties supplied will be [spread to the root element](/guides/api#spread).

## CSS API

You can override all the class names injected by Material-UI thanks to the `classes` property.
This property accepts the following keys:
- `root`

Have a look at [overriding with classes](/customization/overrides#overriding-with-classes) section
and the [implementation of the component](https://github.com/mui-org/material-ui/tree/v1-beta/src/BottomNavigation/BottomNavigation.js)
for more detail.

If using the `overrides` key of the theme as documented
[here](/customization/themes#customizing-all-instances-of-a-component-type),
you need to use the following style sheet name: `MuiBottomNavigation`.

## Demos

- [Bottom Navigation](/demos/bottom-navigation)

