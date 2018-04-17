# 打包步骤
```
# 安装依赖
    $ npm install
# 本地调试
    $ npm start 
# 生成打包文件
    $ npm run package
```

### 备注：安装打包文件的依赖，不然报错
	打包完成需要去‘\resources\app‘ 下安装依赖包 $ npm install

# 打包成安装包.exe
- 新建目录two，并将lv6-win32-x64复制到其下面,再次需要去‘\resources\app‘ 下安装依赖包 $ npm install（有点问题,每次移动过文件夹都需要重新删除，并npm install getmac）只需要安装这一个就可以。

- 在build文件夹中(Gruntfile.js) npm install好

- 全局安装grunt，并运行 `$ grunt`

- 输出文件在dist处
