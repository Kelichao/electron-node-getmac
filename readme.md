# 打包一步骤（master分支）
```
# 全局安装electron
$ npm install electron -g
# 安装依赖
    $ npm install
# 本地调试
    $ npm start 
# 生成打包文件
    $ npm run package
```
- 最终生成名为`lv6-win32-x64`的文件

### 备注：安装打包文件的依赖，不然报错
	打包完成需要去‘\resources\app‘ 下安装依赖包 $ npm install

# 打包二步骤-生成exe文件（second分支）

- 切换到second分支，并将lv6-win32-x64复制到其下面,再次需要去‘\resources\app‘ 下安装依赖包 $ npm install（有点问题,每次移动过文件夹都需要重新删除，并npm install getmac）只需要安装这一个就可以（不然就会报路径或者文件名过长的错误）。

- 在build文件夹中(Gruntfile.js) npm install好

- 全局安装grunt，并运行 `$ grunt`

- 输出文件在dist处
