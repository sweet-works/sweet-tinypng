
## 初衷
[tinypng](https://tinypng.com/) 网页版，其实是挺方便的。但是他有上传图片数量的限制，比如每天只能上传 20 张，如果超过这个数量，就会断断续续的出现 `Too many files uploaded at once` 错误 。所以才决定使用 Node 来开发一个绕过数量限制的 npm 包。


## 使用方法
安装：
```bash
npm i sweet-tinypng -g # or yarn global add sweet-tinypng
```

然后，在命令行进入到你想要压缩图片的目录，执行：
```bash
sweet-tinypng
```
想要压缩并修改图片名中不想要的字符，执行：
```bash
sweet-tinypng @2x
```

## 版本更新
- 1.0.4 更新API
- 1.0.5 新增替换名字功能

## 免责声明

该仓库仅用于学习，如有商业用途，请购买官方的 pro 版：https://tinify.com/checkout/web-pro

This Repo is only for study. 
