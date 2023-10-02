# SimpleToTP

一个简易的ToTP（基于时间的一次性验证码）模块，仅有一个文件，不依赖任何第三方库运行。

函数功能表：

| 函数名称 | 用途 |
| --- | --- |
| generate_key() | 生成一串随机字符串，可用作密钥 |
| generate_key_plus() | 生成一串随机字符串，可用作密钥 |
| generate_totp() | 根据传入的密钥和时间戳生成ToTP验证码 | 
| generate_totp_plus() | 根据传入的密钥和时间戳生成ToTP验证码 | 
| generate_totp_now() | 根据传入的密钥和当前时间生成ToTP验证码 | 
| generate_totp_plus_now() | 根据传入的密钥和当前时间生成ToTP验证码 | 
| generate_totp_easy() | 根据传入的密钥和当前时间生成ToTP验证码 | 
| generate_totp_easy_now() | 根据传入的密钥和当前时间生成ToTP验证码 | 
