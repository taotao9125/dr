debug react source code


## 一: 构建 react
1. `cd react`
2. `yarn`
3. `yarn build`


## 二: shell copy react 到 debugreact 目录
1. `cp -r ./react/build/node_modules/react-dom ./debugreact/public`
2. `cp -r ./react/build/node_modules/react ./debugreact/public`


## 三: 跑 demo
1. `cd debugreact`
2. `yarn`
3. `yarn start`



<br >
<br >
<br >
<br >
<br >
<br >
react github verson -> 80f3d88190c07c2da11b5cac58a44c3b90fbc296