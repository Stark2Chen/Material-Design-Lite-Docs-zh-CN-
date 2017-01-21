# 现在开始

## 包含内容

    包含主要的CSS和JavaScript框架

    使用零部件

    通用的规则

    在动态的网站上使用MDL

    MDL的职责在于什么？

    接下来呢？

    许可证

# 包含的主要CSS和JavaScript框架

想要在你的每一个HTML页面中使用MDL，我们提供文件的hosted在我们对CDN服务器上，你也可以下载并且定制他们，通过npm/bower的方式获取项目的源代码并且安装他们

>Include the Material Lite CSS and JavaScript files in each HTML page in your project. We recommend that you use the files hosted on our CDN. You can also customize and download them to host them yourself, build them from our source code or install them in your npm/Bower project.

#### hosted

在你的HTML文档中插入这些代码，他们包含了Material的图标字体，这些代码将会提供一个27kB大小的压缩包

    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
    <link rel="stylesheet" href="https://code.getmdl.io/1.3.0/material.indigo-pink.min.css">
    <script defer src="https://code.getmdl.io/1.3.0/material.min.js"></script>

#### 下载

下载一个Javascript的包：https://code.getmdl.io/1.3.0/mdl.zip

在你的HTML文档中插入这些代码，他们包含了Material的图标字体

    <link rel="stylesheet" href="./material.min.css">
    <script src="./material.min.js"></script>
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">

#### Build 

在MDL的[Github](https://github.com/google/material-design-lite)上下载源代码并且build它。

在控制台运行这些命令

    # Clone/copy the Material Design lite source code.
    git clone https://github.com/google/material-design-lite.git
    # Go into the newly created folder containing the source code.
    cd material-design-lite
    # Install necessary dependencies.
    npm install && npm install -g gulp
    # Build a production version of the components.
    gulp

你可以在dist文件夹找到MDL的目录，然后把他们复制到你的项目当中

在你的HTML文档中插入这些代码，他们包含了Material的图标字体

#### Bower

Bower提供了一个简易的方式去安装MDL，并且使用他们

在控制台运行这些命令

    bower install material-design-lite --save

MDL的文件夹江会被安装在你的项目中的bower_components文件夹中。

你需要在HTML文档中插入这些代码，他们包含了MDL的图标字体

    <link rel="stylesheet" href="/bower_components/material-design-lite/material.min.css">
    <script src="/bower_components/material-design-lite/material.min.js"></script>
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">

#### NPM 

另一个简单的安装方式是NPM，你可以在控制台运行这些命令

    npm install material-design-lite --save

MDL的文件将会被安装在你的项目中的node_modules文件夹里

在你的HTML文档中插入这些代码，他们包含了Material的图标字体

    <link rel="stylesheet" href="/node_modules/material-design-lite/material.min.css">
    <script src="/node_modules/material-design-lite/material.min.js"></script>
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">

##### 备注：选择颜色方案

颜色方案在MD中极为重要，HOSDED提供的是默认的indigo-pink颜色，同时，我们的CDN主机也提供了一些常见的配色方案。如果你想定义个性的颜色，我们也提供了定制和预览的工具

>Color schemes used in Material Design are based on a primary and an accent colors which you may want to personalize. These colors are specified in the CSS file name by following this pattern: material.{primary}-{accent}.min.css (e.g. material.indigo-pink.min.css). Our CDN hosts a number of color combinations based on common Material Design colors. To discover and preview available color combinations use our Customize and Preview tool.

就这样了！你已经准备好在你的网站上使用Material Design LIte！

# 使用零部件

