## go mod引用包超过三级目录无法访问到正确包路径问题
* issue地址：https://github.com/golang/go/issues/34094
* 建议在根目录下配置.netrc目录做git权限认证可以规避包引用异常问题
* 格式：machine {host} login {username} password {accecc_token}
* 样例：machine gitlab.uniontech.com login yyyy password xxxx