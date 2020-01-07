# openssl-libs
    不断提供各平台可用的 openssl 各版本库文件，免去繁琐的编译步骤。

## 目录结构
```
openssl-libs
|-- v1.1.1d (openssl 相应版本库目录)
    |-- win32 (win 32位库目录)
        |-- bin (动态库目录, MD)
            |-- include (openssl 头文件)
            |-- Debug (带调试信息版本)
            |-- Release (生产版本)
        |-- libs (静态库目录, MT)
            |-- include (openssl 头文件)
            |-- Debug (带调试信息版本)
            |-- Release (生产版本)
    |-- win64 (win 64位库目录)
        |-- bin (动态库目录, MD)
            |-- include (openssl 头文件)
            |-- Debug (带调试信息版本)
            |-- Release (生产版本)
        |-- libs (静态库目录, MT)
            |-- include (openssl 头文件)
            |-- Debug (带调试信息版本)
            |-- Release (生产版本)
```