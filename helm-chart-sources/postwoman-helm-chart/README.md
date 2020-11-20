# PostWoman Chart
[PostWoman](https://www.github.com/hoppscotch/hoppscotch) 是一个用于替代Postman,免费开源、轻量级、快速且美观的API调试工具。能帮助程序员节省时间,提升工作效率。

## 安装 Chart

```
$ helm install hepeng/postwoman
```

## 配置信息

| 参数                                  | 描述                                                              | 默认值                                                      |
| ------------------------------------ | ----------------------------------------------------------------- | ---------------------------------------------------------- |
| `image`                              | PostWoman 镜像                                                     | `liyasthomas/postwoman`                                   |
| `tag`                                | PostWoman 镜像TAG                                                  | `v1.9.9`                                                  |
| `pullPolicy`                         | 镜像TAG拉取策略                                                     | `IfNotPresent`                                             |
| `resources`                          | Resource limits and requests                                      | `limits.memory=1024Mi, limits.cpu=100m`                    |
| `service.nodePort`                   | Service NodePort                                                  | `32110`                                                    |