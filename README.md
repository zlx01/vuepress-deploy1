# vuepress-deploy1

`deploy.sh` 脚本作用：打包，并push到当前仓库的gh-pages，进而自动触发GitHub Pages部署。

1. 在 docs/.vuepress/config.js 中设置 base 为 '/vuepress-deploy1/'

2. 在持续集成的设置中，设置在每次 push 代码时自动运行 `deploy.sh` 脚本。

3. Windows本地的话，可以在git bash中运行测试。
