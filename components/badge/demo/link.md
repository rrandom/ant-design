---
order: 2
title:
  zh-CN: 可点击
  en-US: Clickable
---

## zh-CN

用 a 标签进行包裹即可。

## en-US

Badge could be wrapped by tag `a`.

````jsx
import { Badge } from 'antd';

ReactDOM.render(
  <a href="#">
    <Badge count={5}>
      <span className="head-example"></span>
    </Badge>
  </a>
, mountNode);
````
