# 深深桌宠（手机版）远程动画素材

这个仓库只是**素材存放点**，不是应用本体。应用仓库：
[Jcnet-9527/dsh-Jpet-phone](https://github.com/Jcnet-9527/dsh-Jpet-phone)

APK 里只打包了 7 段核心动画（约 30 MB 安装包），完整 106 段逐帧素材放在这里，
由 App 在需要时按段下载并缓存在手机里（设置 → 动画素材 可一键全下 / 清除 / 换源）。

## 目录

```
clips/<clip id>.zip        每一段动画一个包，里面是 f_0001.webp …（ZIP_STORED，未二次压缩）
manifest.json              全部 106 段的描述（裁剪框 / 帧率 / 分类名 / 身体锚点 / 是否随包）
source/shenshen/videos/    源动画（106 个 webm），供重新导出逐帧素材使用
```

## 默认下载源

```
https://cdn.jsdelivr.net/gh/Jcnet-9527/dsh-Jpet-phone-assets@main/clips/<clip id>.zip
```

备用源（App 会依次尝试）：

```
https://raw.githubusercontent.com/Jcnet-9527/dsh-Jpet-phone-assets/main/clips/<clip id>.zip
https://ghfast.top/raw.githubusercontent.com/Jcnet-9527/dsh-Jpet-phone-assets/main/clips/<clip id>.zip
```

自建镜像只要保持 `clips/<clip id>.zip` 结构，然后在 App 设置里把「下载源」改成自己的根目录即可。

## 素材版权

角色动画为个人非商业用途素材，这里仅作自用存档与远程分发，请勿二次分发或商用。
