# **colab_stable_diffusion_webui**
-[![](https://img.shields.io/static/v1?message=Open%20in%20Colab&logo=googlecolab&labelColor=5c5c5c&color=0f80c1&label=%20&style=flat)](https://colab.research.google.com/github/YoungerKayn/colab_stable_diffusion/blob/main/stable_diffusion.ipynb)<br>


### 关于谷歌colab
- 请确认有可以魔法上网的工具，工具用于谷歌colab的机器学习，属于合法范畴。 
- 优势：不需要显卡，手机也能用，且云端运行速度快。
- 此项目为免费开源项目，并将持续维护更新。如果有任何广告动机请举报
- 由于人数较多，谷歌colab每个号的时间大概为4-6小时左右，多弄几个号在云盘里主号的json给其他号添加编辑权限就实现了所有号共用
- 一天内第一次启动过程约7分钟左右下载插件模型依赖，请耐心等待。之后如果再启动就非常快。 
- 你也可以电脑魔法上网colab，手机直接打开代码运行后给出的域名就行。
- 谷歌运行环境为12G 内存15G显存，大显存小内存所以推荐使用半精度进行计算
- 教程可以点击链接:https://www.bilibili.com/video/BV17h4y1J79g/?spm_id_from=333.788.top_right_bar_window_history.content.click
- mod管理单元中lora和checkpoint只需填下载地址即可，你也可以添加一些信息方便管理。
- 笔记本为单线程，请保证4、单元格处于未运行状态再管理mod。
- mod管理时建议mod名以"c站mod名（自定义中文名）"的形式进行命名，这样既可以方便搜索c站的sd图，又方便在使用时在lora列表进行搜索
- 新人不知道下哪些模型可以去推荐模型文档单元下载json文件。
- 自定义的vae与插件请在云盘新建文件夹VAE与extensions并自行管理。
- 晚高峰人数较多，提示连接出错或断线为正常情况，可以尝试使用ngrok管道进行加速。
 
 ## 关于sd
 - 如果图片信息读取图片“不是一张stable diffusion图片”说明作者上传的图片经过了压缩处理，请选择其他图片或者复制文字与种子手动输入
 - 采样方法推荐 DDIM 与DPM++ 2M 高清放大推荐 潜变量(bicubic)与潜变量最邻近
 - 图片可以选择输出在云盘的outputs文件夹里
 - 生成图的速度与执行代码的速度与网速无关，你就算断网几分钟他也在执行
 - 如果要使用手机进行局部绘图请使用Edge浏览器，谷歌浏览器不兼容
 - there's not enough precision to represent the picture的解决方式是切换其他VAE，或者4、运行时勾选全精度，但生成图的速度会下降一半
