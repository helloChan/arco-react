# Arco Design Pro

## 快速开始

```
// 初始化项目
npm install

// 开发模式
npm run dev

// 构建
npm run build

1. /public/index.html
2. index.tsx
    - store
        - createStore(rootReducer)
    - index compoment
        - useStorege
        - useEffect
            checkLogin(没登录去登录页，登录了去默认页面, 登录了则去拿用户信息)
            i18n
            theme
        - render
            - Route Login
            - Route PageLayout

3. PageLayout
    - <Route exact path="/">
        <Redirect to={`/${defaultRoute}`} />
      </Route>

```
