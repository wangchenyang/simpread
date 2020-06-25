>  此功能最低要求 1.1.4.6022 版本，如低于此版本，[请升级](http://ksria.com/simpread/) 到最新版本。

位置
---

> 阅读模式 → 控制栏 → 动作 → 保存

![lzcLOe.png](https://s2.ax1x.com/2020/02/01/18otu8.md.png)

说明
---

导出到 `Notion` 的内容为 **Markdown** 格式


授权
---

> 由于  **Notion** 并未提供 API 方式，所以需要使用 下面几个步骤才能授权成功。

- 选项页 → 高级设定 → 授权管理
  ![NeHUaQ.png](https://s1.ax1x.com/2020/06/18/NeHUaQ.png)
- 用户需要手动登录到 [Notion](https://www.notion.so/) _Notion 暂不支持 API 所以需要手动登录_
- 选择授权
- 授权成功后，可选择保存的文件夹_**注意：与其它授权不同，简悦无法自动建立对应的文件夹**_
- Notion Page 支持层级文件夹 _**注意：需要 1.1.4.6016 版本才可支持**_

![lzgEwj.png](https://s1.ax1x.com/2020/06/16/NFU1k8.png)

- 导出到 Notion 支持 **database** 和 **page** 方式 _**注意：需要 1.1.4.6016 版本（以上）才可支持**_

- 导出到 Notion 支持 **支持源网址**   _**注意：需要 1.1.4.6022 版本（以上）才可支持**_

[![NFwLu9.png](https://s1.ax1x.com/2020/06/22/NGcYdO.png)](https://s1.ax1x.com/2020/06/22/NGcYdO.png)

图床
---

> [1.1.4.6022](http://ksria.com/simpread/changelog.html#1.1.4.6022) 增加了 Notion.so 图传功能，导入到 Notion 的内容可自动上传为 Notion 本身，避免源页面 404 等问题

> 注意：由于使用了 Notion 私有 API 所以在上传图片时较慢 

- 选项页 → 高级设定 → 授权管理，开启图床功能 _**默认为关闭状态**_

  ![NGBOWq.png](https://s1.ax1x.com/2020/06/22/NGBOWq.png)

  ![NGcqkF.gif](https://s1.ax1x.com/2020/06/22/NGcqkF.gif)

注意
---

> A. 如何更改授权后的文件夹？

1. 选项页 → 高级设定 → 授权管理
2. 点击 **重新获取 Notion Page** 即可看到下拉列表

> B. 暂时不支持 Notion Web Clipper 的图床功能

接下来就会推出

> C. 1.1.4.6016 版存在 **有小机率** 的授权错误

前提是你有上万个 Page 或其它人共享给你的 Page ，如存在这种问题，可以手动解决，[请提 Issues](http://github.com/kenshin/simpread/issues/new)

> 导出到 Notion database 的内容 **不含有链接** 的话，请参照下面的方式设定

![NNWyDJ.png](https://s1.ax1x.com/2020/06/23/NNWyDJ.png)

>  导出到 Notion database 的内容也可以显示导入的œ时间，请参照下面的方式设定

![NNWsu4.png](https://s1.ax1x.com/2020/06/23/NNWsu4.png)


授权异常
---

> 受影响的版本，包括 **1.1.4** · **1.1.4.6016** · **1.1.4.6022** 
>
> 在使用 Notion 授权时（个别情况下）会出现无法授权的情况，为避免这种问题，因此发布了 **1.1.4.6025** 版。

> 此版本唯一的用处就是：确保用户可以授权成功，**即便在发生错误的情况下，也会成功授权你的第一个 Page**