# 项目自动化的一个模板
前端自动化一直在用，但是没有完整的使用过，这次把前后的知识都整理了一遍，搞出这个模板来。

模板使用的是gulp工具，MVC三层分类的思想。后端的包管理使用npm，前端包管理使用bower。

# 运行方法

`npm run dev` 在工作环境中运行

`npm run dist` 在生产环境中运行

# 功能列表
+ ES6语法转换为ES5 -- gulp-babel gulp-preset-2015
+ JS压缩 -- gulp-uglify
+ 图片压缩 -- gulp-imagemin
+ css压缩 -- gulp-clean-css
+ html压缩 -- gulp-htmlmin
+ 给静态文件加上MD5后缀 -- gulp-rev
+ 替换dist文件夹的MD5名字 -- gulp-rev-collector
+ 文件复制 -- gulp-copy

