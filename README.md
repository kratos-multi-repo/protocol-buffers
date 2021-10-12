# protocol-buffers

## install

```shell
go mod download

```

增加新的协议

```shell
kratos proto add helloworld/v1/greeter.proto

```

生成 pb 文件

```shell
make generate

```

## 生成 SDK

将所有生成的 `.go` 文件全部迁移到 sdk 目录即可（后续将通过工具实现自动化）

## IDE 设置

[常见问题](https://go-kratos.dev/docs/intro/faq)

[IDE中import "google/api/annotations.proto";等proto文件有错误提示（被画波浪线）](https://go-kratos.dev/docs/intro/faq#ide%E4%B8%ADimport-googleapiannotationsproto%E7%AD%89proto%E6%96%87%E4%BB%B6%E6%9C%89%E9%94%99%E8%AF%AF%E6%8F%90%E7%A4%BA%EF%BC%88%E8%A2%AB%E7%94%BB%E6%B3%A2%E6%B5%AA%E7%BA%BF%EF%BC%89)
