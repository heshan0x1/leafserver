Leaf server
===========
A game server based on [Leaf framework](https://github.com/name5566/leaf).

Licensing
---------

Leaf server is licensed under the Apache License, Version 2.0. See [LICENSE](https://github.com/name5566/leafleafserver/src/server/blob/master/LICENSE) for the full license text.

设置gopath
```
leafserver/
```

server 目录下执行
```shell
go mod init leafserver   
go mod tidy 
go get github.com/name5566/leaf
```

编译
```shell
go install .
```

运行
```shell
cd bin
./server
```
