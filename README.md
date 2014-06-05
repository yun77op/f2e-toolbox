f2e-toolbox
===========


组件
---

 - 文件上传: 推荐使用以HTML5为主，FLASH为辅的现代文件上传组件的[Webuploader](http://fex.baidu.com/webuploader/)
 - 富文本编辑器: [UEditor](http://ueditor.baidu.com/website/)
 - Tooltip: Bootstrap Tooltip
 - Datepicker: jQuery UI Datepicker
 - 图表：[Highcharts](http://www.highcharts.com/)
 - 音视频播放器: Videoplayer
 - 复制到剪切板：[ZeroClipboard](http://zeroclipboard.org/)


图片
---

### 图片占位服务：

 - [img.la](http://img.la)
 - [placehold.it](http://placehold.it)
 - [placekitten.com](http://placekitten.com)

### Photoshop plugins：

 - [Ink](http://ink.chrometaphore.com/) 图层尺寸丈量、字体信息和颜色等

Photoshop CC 有复制CSS功能

### 其他

 - [Glue](http://glue.readthedocs.org/en/latest/) sprite生成工具


CSS
---

### Sprite

基类`.ui-icon`，每个sprite一个CSS文件

examples: 

    // ui-icon.css
    .ui-icon {
      display: inline-block;
      vertical-align: top;
    }

    .ui-icon.sprite-apps {
      width: 14px;
      height: 14px;
    }

    // sprite-apps.css
    .apps-dash {
      background-position: -20px -20px;
    }

    // html
    <i class="ui-icon-view.apps-dash.sprite-apps"></i>


前端构建流程
----------

### 前后端分离

如果使用Java + Freemarker

 - 模拟服务器 [grunt-fmpp](https://github.com/yun77op/grunt-fmpp)
 - [配置完整的后端环境](http://yun77op.gitcafe.com/2014/05/09/setup-local-java-webapp-environment-using-maven-for-f2e/)