### Vue3 中文文档
https://cn.vuejs.org/guide/introduction.html

### typescript 文档
https://jkchao.github.io/typescript-book-chinese/#why

### Vite 2.x 英文版（没找到中文文档）
https://v2.vitejs.dev/guide/why.html

### Vant ui 
https://vant-ui.github.io/vant/v4/#/zh-CN

### Ab-vue 源代码 最新版本 0.0.56 
https://github.com/tuolib/ab-vue

### 项目根目录文件命名规则 README.md


### 代码格式化工具 prettier

- Vscode 安装使用步骤
1 Volar插件 安装
2 prettier 插件 安装
3 如下json 配置 prettier 为默认格式化工具
4 格式化快捷键 option + shift + f

```json

{
    "editor.defaultFormatter": "esbenp.prettier-vscode", // 设置编辑器的默认格式化工具为 prettier
    "[javascript]": { // 根据语言设置其对应的默认格式化工具
        "editor.defaultFormatter": "esbenp.prettier-vscode", // 设置 javascript 的默认格式化工具为 prettier
        // "editor.formatOnSave": true, // 保存的时候自动格式化
    },
    "[typescript]": { // 根据语言设置其对应的默认格式化工具
        "editor.defaultFormatter": "esbenp.prettier-vscode", // 设置 javascript 的默认格式化工具为 prettier
        // "editor.formatOnSave": true, // 保存的时候自动格式化
    },
}
```


- webstorm 安装使用步骤

1 prettier 插件 安装 即可
2 格式化快捷键 command + option + shift + f