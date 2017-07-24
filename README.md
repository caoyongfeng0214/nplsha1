# nplsha1

示例：

```
local sha1 = NPL.load('sha1');

local str = 'Hello Sha1';
local out1 = sha1(str); -- 输出加密后的二进制
local out2 = sha1(str, 'hex'); -- 输出加密后的16进制表示形式
local out3 = sha1(str, 'base64'); -- 输出加密后的base64表示形式
```
