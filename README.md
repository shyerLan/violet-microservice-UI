## 开发

```bash
# 克隆项目
git clone https://gitee.com/y_project/RuoYi-Vue

# 进入项目目录
cd ruoyi-ui

# 安装依赖
npm install

# 建议不要直接使用 cnpm 安装依赖，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```

## 发布

```bash
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
```

## 项目进程（前端篇）
+ 2021.5.1 项目创建
+ 2021.5.2 目前想不出做什么内容暂停项目（后期应该是以影视资源，漫画，小说，音乐一体的服务平台）
+ 2021.5.10 最终确定创建服务平台 目前业务支持私人云盘
+ 2021.5.11 私人云盘桌面开始
    - 需求分析

    | 要求功能   | 状态   | 完成时间 |
    | ------ | ------ | ------ |
    | 文件树与文件内容的显示 |
    | 窗口拖拽 |
    | 窗口小化 |
    | 回到桌面 |
    | 回收站 |
    | 文件的浏览 |
    | 文件位置移动 |
    | 小化后的快速打开集成在任务栏 |
    | 个人的操作日志 |
    | 关机退出动画回到登录页面 |
    | 个人拥有的菜单列表 |
    | 文件搜索 |
    | 个人信息的修改 |
    | 分享文件 |
    | 管理分享链接 |
    | 右键的操作 |
    | 当前时间 |
    | 窗口的大小改变 |

+ 2021.5.11 主页面画出，底部工具栏大致
+ 2021.5.12 桌面文件夹布局完成
+ 2021.5.13 文件夹打开内容布局完成
+ 2021.5.14 文件关闭打开动画 文件夹打开关闭交互完成