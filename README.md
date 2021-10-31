# iOS9固定g值

#### 使用方法

1、赋予0775权限，并运行cl0ver工具，安装ios-kern-utils插件

2、终端输入:nvpatch com.apple.System.boot-nonce

3、再输入:nvram com.apple.System.boot-nonce=0x1111111111111111
(备注：0x1111111111111111改为需要固定的值)

4、最后输入:nvram auto-boot=false

5、如需查询G值是否固定成功可输入:nvram -p
# pangu-ios9
