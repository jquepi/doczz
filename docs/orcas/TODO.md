提供修改适配器的接口
用户配置可以从服务端拉取，也可以实时同步，用户配置可以修改，多端同步要存储配置版本号

加密路径支持配置，不配置加密路径不加密
加密的文件不提供预览功能，预览功能作为插件，以独立仓库方式提供，预览用户和清理任务一样，不设置权限访问管理器，可以访问所有桶，只能在服务端运行，支持被动通知和主动触发式两种生成方式

文件通知可以挂在协议层，单独实现一套Handler
预览word文档用libreoffice，图片用image magick，视频用ffmpeg
支持全文检索功能
照片视频可以引入智能相册方案

用户鉴权还是可以考虑使用RBAC