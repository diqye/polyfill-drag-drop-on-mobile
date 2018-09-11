# polyfill-drag-drop-on-mobile

手机上的拖拽事件体验太差，在网上找了个基于touch事件做的polyfill(在感谢里面),使用过程中有一些严重的Bug(主要是setData报错).

但polyfill没有github，无法提交pull request。故在此建立个

## 使用
```
npm i polyfill-drag-drop-on-mobile --save
```
```
import 'polyfill-drag-drop-on-mobile'
```

## 感谢

https://www.npmjs.com/package/drag-drop-touch
