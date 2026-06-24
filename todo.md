1. 数据库修改
  - install.sh install-alpine.sh install-openwrt.sh去掉这两个多余字段上报
  - 注意不要引入bug
2. 加入一个版本号字段 -- 后期逻辑再理一下
3. 前端支持多apiBase, 并且同时调用并输出，如果多个，/admin前端关闭入口
