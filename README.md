## 欢迎来到我的GitHub主页
- 这是一首诗
  > 青青园中葵，朝露待日晞。
  > > 阳春布德泽，万物生光辉。
  > > > 常恐秋节至，焜黄华叶衰。
  > 
  > 百川东到海，何时复西归？
  > > 少壮不努力，老大徒伤悲！
- [ ] 不选中
- [x] 选中
---
**这个是加粗**
*斜体*
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
first|second
-----|-----
吃饭 | 喝茶
唱歌

```flow
st=>start: Start
e=>end: End
接收用户名和密码=>operation: 接收用户名和密码
使用用户名查询数据库=>operation: 使用用户名查询数据库
数据库中是否有数据=>condition: 数据库中是否有数据?
走登录逻辑=>operation: 走登录逻辑
走注册逻辑=>operation: 走注册逻辑
密码是否正确=>condition: 密码是否正确?
把用户名和密码写入数据库=>inputoutput: 把用户名和密码写入数据库 

st->接收用户名和密码->使用用户名查询数据库->数据库中是否有数据
数据库中是否有数据(yes)->走登录逻辑->密码是否正确
数据库中是否有数据(no)->走注册逻辑->把用户名和密码写入数据库->e
密码是否正确(yes)->e
密码是否正确(no,down)->接收用户名和密码
```

