# 插入支持乌克兰 Banner

#### 介绍
够了，Pink 真的是让我忍无可忍了。傻逼。

#### 使用说明

第一种方法：将 `/include/_section.html` 复制到你想添加的地方。

第二种方法：

`<link rel="import" href="./include/_section.html" is="ui-import">` 在想插入的地方导入

```
页脚
<script src="./safari-polyfill.js"></script>
<script src="./html-import.js"></script>
<script>
    let nowar_banner_infomation = document.querySelector(".nowar_banner_infomation");
    nowar_banner_infomation.addEventListener("wheel", (event) => {
        event.preventDefault();
        nowar_banner_infomation.scrollLeft += event.deltaY;
    });
</script>
```

原作：<a href="https://www.zhangxinxu.com/wordpress/?p=10009">https://www.zhangxinxu.com/wordpress/?p=10009</a>

#### 许可证

以 MIT 授权，可随意修改，请保留原作者信息。
