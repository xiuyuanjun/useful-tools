# 一些自用小工具

##  批量视频片头剪切/batch cut the opening of the video
```bash
下载video-clip.py到需要剪切的视频同级目录。
进入源码自行修改片头秒数。
仅写了mp4格式，需其它格式只需if加个条件即可。
------------------
git clone https://github.com/mashaz/useful-tools.git
copy video-clip.py to videos' directory or copy videos to useful-tools, you can change the second in code you want
python2 video-clip.py
```

## requirements
* ffmpeg

----

##  批量图片指定区域截取
```bash
把全部待截图片放入images文件夹
下载image-crop.py到images文件夹同级目录。
进入源码自行修改截取区域大小。
```

## requirements
* PIL

---

## 批量清除（保留）制定格式文件

~~keep-image.py~~

现在直接用shell比较舒服

```shell
find . -name '[a-z].txt' -maxdepth 1 -exec rm {} \;
```

---

## 批量重命名
```bash
rename.py
```