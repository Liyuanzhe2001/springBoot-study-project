# springBoot-study-project

视频链接：https://www.bilibili.com/video/BV1PE411i7CV



### 1.首页配置：

1. 注意，所有页面的静态资源都需要使用thymeleaf接管；
2. url：@{}

### 2.页面国际化:

1. 我们需要配置i18n文件
2. 我们如果需要在项目中进行按钮切换，我们需要自定义一个组件LocaleResolver
3. 记得将自己写的组件配置到spring容器汇总@Bean

### 3.登录+拦截器：

### 4.员工列表展示：

1. 提取公共页面
    1. `th:fragment="sidebar"`
    2. `<div th:replace="~{/commons/commons.html::topbar}"></div>`
    3. 如果要传递参数，可以直接使用（）传参，接收判断即可
2. 列表循环展示

### 5.添加员工

1. 按钮提交
2. 跳转到添加页面
3. 添加员工成功
4. 返回首页

### 6.CRUD

### 7.404
