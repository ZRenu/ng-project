# [鹿途](https://github.com/ZhouRenYou/ng-deerway)后台管理系统基础框架

# [Live](https://angular6-project.netlify.com)


##  项目说明

Angular6基础框架。

## 版本说明

```ts
"@delon/acl": "^1.5.1",
"@delon/auth": "^1.5.1",
"@delon/theme": "^1.5.1",
"ng-zorro-antd": "^1.8.1"
```

### 用户认证

[@delon/auth](https://ng-alain.com/auth/getting-started)


```ts

constructor( @Inject(DA_SERVICE_TOKEN) private tokenService: TokenService) {
    // 设置认证信息
    tokenService.set({token:'token'})
    // 获取认证信息
    tokenService.get().token; // token
    // 清除认证信息
    tokenService.clear()
}
```

## 项目资源


地图：[maps](http://lbsyun.baidu.com/)

图表：[echarts](http://echarts.baidu.com/index.html)

用户认证：[@delon/auth](https://ng-alain.com/auth/getting-started)

项目框架：[ng-zorro](https://ng.ant.design/version/1.8.x/)

