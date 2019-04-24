# vue-cli

这里是 vue-cli 的文档 👉See [vue-cli 文档](https://cli.vuejs.org/zh/).


### 开发环境

1. node.js >= 8 (推荐8.11.0+) (可以使用 [nvm](https://github.com/creationix/nvm) 管理node版本)
    
    * 关于nvm
    推荐一篇博客  [使用nvm管理node版本](http://bubkoo.com/2017/01/08/quick-tip-multiple-versions-node-nvm/).

    ```
    

    * 说明：
    安装完成之后需执行

    export NVM_DIR="$HOME/.nvm"
    [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
    [ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"

    * 查看nvm   =>   nvm ls
    * 切换nvm   =>   nvm use node版本

    ```

    
## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve 或者 yarn serve
```

### Compiles and minifies for production
```
yarn run build
```

### Run your tests
```
yarn run test
```

### Lints and fixes files
```
yarn run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


```
👉2019-4-24
* 使用新版的vue-cli生成了这个项目.新版的vue-cli要求node版本在8以上.所以顺便搞了一个node版本的管理工具nvm.
```


