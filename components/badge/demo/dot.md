---
order: 3
title:
  zh-CN: 讨嫌的小红点
  en-US: Red dot
---

## zh-CN

没有具体的数字。

## en-US

Just Red dot without specific count.

````jsx
import { Badge, Icon } from 'antd';

ReactDOM.render(<div>
  <Badge dot>
    <Icon type="notification" />
  </Badge>
  <Badge dot>
    <a href="#">一个链接</a>
  </Badge>
</div>, mountNode);
````

<style>
.anticon-notification {
  width: 16px;
  height: 16px;
  line-height: 16px;
  font-size: 16px;
}
</style>
