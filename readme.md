
## 初始化react项目
    npx create-react-app reactDemo --template typescript // 不能有大写
    npx create-react-app my-react-demo --template typescript

package.json
    项目入口文件
    项目依赖配置
tsconfig.json
    ts配置

## prettier 格式化工具使用
    yarn add --dev --exact prettier
    echo {}> .prettierrc.json
    vim .prettierignore
    向.prettierignore添加
            build
            coverage

    自动格式化
    npx mrm@2 lint-staged

    yarn add eslint-config-prettier -D

## commitlint git 使用规范