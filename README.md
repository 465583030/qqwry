# qqwry
纯真IP，golang 内存版


## 1.依赖
> * 参照了 https://github.com/yinheli/qqwry 的代码，虽然文件操作也比较快，还是习惯用内存。所以算法不变，把ip搜索从文件改为内存
> * 依赖 https://github.com/yinheli/mahonia

## 2.使用
> * 请参照 HttpServer.go的代码来使用
> * 编译需要 go build  qqwrylib.go HttpServer.go 
## 3.注意
> 线程安全，缓存操作。方便做服务器来查询。
