---
layout: spec_mobile
permalink: /specs/tabbar-item.html
spec_id: tabbar-item
---

## 属性

### `active` **bool**

当前项是否处于激活状态；

### `href` **string**

当前项被点击时页面跳转的地址；

### `label` **string**

当前项的文字描述；

### `icon` **string**

当前项的图标类型；

### `iconPos` **string**

当前项的图标位置；默认值为 `top`

可选值：

 * top
 * left
 * bottom
 * right

```html
<!DOCYPE html>
<html>
    <body>
        <w-tabbar>
            <w-tabbar-item icon="home" label="Home" href="#home" active/>
            <w-tabbar-item icon="person" label="Profile" href="#profile"/>
            <w-tabbar-item icon="star" label="Favorites" href="#favorites"/>
            <w-tabbar-item icon="search" label="Search" href="#search"/>
            <w-tabbar-item icon="gear" label="Settings" href="#settings"/>
        </w-slider>
    </body>
</html>
```

## 方法

无

## 事件

无