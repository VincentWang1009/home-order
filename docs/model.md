# 模型设计

## dish model

- id 菜肴id
- name  菜肴名称
- tag_id   标签id
- type_id  类别id
- cookbook 菜谱
- pic   菜肴预览图

## dish record model

- id 记录id
- dishId 菜肴id
- taste 口味评分
- looks 外观评分
- date 时间
- pic 菜肴记录图片
- status 状态
- evaluate_id 评价人
- chef_if 厨师

## tag model
- id 标签id
- name  标签名称

## type model
- id 类别id
- name  类别名称

## status model
- id 状态id
- name  状态名称

## user model

- id 用户id
- name 用户名
- password 密码
- role_id 角色

## role model

- id 角色id
- name 角色名称

## permission model

- id 权限id
- name 权限名称

## permission_role model

- id 表id
- role_id 角色id
- permission_id 权限id

# ER图
[ER图](https://raw.githubusercontent.com/VincentWang1009/home-order/main/docs/er.png)