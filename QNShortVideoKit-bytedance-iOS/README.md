# 1 QNShortVideo with ByteDance
这个开源示例代码演示了 [七牛短视频](https://www.qiniu.com/products/plsv) 快速集成字节跳动检测、特效、贴纸等效果的集成姿势。

###注意：‎⁨由于字节跳动中的贴纸资源过大，demo 中压缩成 zip 方便管理，在运行前，请前往  QNShortVideo-ByteDance⁩ ▸ ⁨QNShortVideoKit-bytedance-iOS⁩ ▸ ⁨PLShortVideoKitDemo⁩ ▸ ⁨ByteEffects⁩ ▸ ⁨Resource⁩ 中解压 StickerResource.bundle.zip

# 2 功能点介绍

这个示例代码中，主要在视频录制的时候，演示了字节跳动检测、特效、贴纸等效果。详细功能展示如下：

七牛短视频

- 七牛短视频录制
- 摄像头切换

字节跳动

- 检测，包括人脸、手势、人体骨骼检测、人体染发分割，人体前后背景分割、人脸对比等
- 美颜，包括大眼、瘦脸、磨皮、美白、锐化等
- 美妆，包括腮红、口红、睫毛、美瞳、头发、眼睛、眉毛等
- 人脸动态2D/3D贴纸等


视频采集、预览、录制采用七牛短视频 SDK 完成。美颜、美型、贴纸、特效等采用的字节跳动 SDK。需要注意的是，为了更好的演示字节跳动的滤镜效果，Demo 中禁用了七牛自带的滤镜效果。

# 3 声明

- 七牛短视频 SDK 需要七牛授权方可使用，可通过 400-808-9176 转 2 号线联系七牛商务咨询，或者 [通过工单](https://support.qiniu.com/?ref=developer.qiniu.com) 联系七牛的技术支持。

- 字节跳动特效 SDK 需要字节跳动授权方可使用，同样可以通过 400-808-9176 转 2 号线联系七牛商务咨询，或者 [通过工单](https://support.qiniu.com/?ref=developer.qiniu.com) 联系七牛的技术支持，来获悉字节跳动特效的使用权限。

# 4 反馈及意见

当你遇到任何问题时，可以通过在 GitHub 的 repo 提交 issues 来反馈问题，请尽可能的描述清楚遇到的问题，如果有错误信息也一同附带，并且在 Labels 中指明类型为 bug 或者其他。

[通过这里查看已有的 issues 和提交 Bug](https://github.com/pili-engineering/QNShortVideo-ByteDance/issues)
