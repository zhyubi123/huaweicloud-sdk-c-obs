# huaweicloud-sdk-c-obs
Version 3.19.7

新特效：
1. 添加set_object_metadata接口，提供设置对象元数据功能；
2. 支持设置bbr加速

修复问题：
1. 【功能】修复服务端开启http2.0协议导致请求失败的问题；
2. 【功能】修复错误返回后重试导致请求异常的问题；

三方依赖:
1. curl升级为7.64.1
2. libssh2升级为1.9.0
3. libxml2升级为2.9.9
4. openssl升级为1.0.2r
