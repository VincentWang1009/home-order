## dish model

id 菜肴id
name  菜肴名称
tag   标签 如 猪肉，牛肉，煎
type  菜肴所属类别
cookbook 菜谱
pic   菜肴预览图

## dish record model

id 记录id
dishId 菜肴id
taste 口味评分
looks 外观评分
date 时间
pic 菜肴记录图片

## user model

id 用户id
name 用户名
password 密码
roleId 角色

## role model

id 角色id
name 角色名称

## permission model

id 权限id
name 权限名称

## permission_role model

id 表id
role_id 角色id
permission_id 权限id