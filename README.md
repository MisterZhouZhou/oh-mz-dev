# oh-mz-dev

## 使用方式

1、安装 Docker

2、git clone https://github.com/MisterZhouZhou/oh-mz-dev.git 将 oh-mz-dev 克隆到本地

3、打开 Windows/Mac 的终端，运行 `docker network create network1`创建网络

4、打开 VSCode 安装`Dev Containers` 插件， 将`oh-mz-dev`目录拖入VSCode
输入`Ctrl/Command + Shift + P`，然后输入 `Reopen`，回车，等待

5、等上一步启动完毕之后，新建终端, 验证环境
```shell
# nvm
nvm -v

# node
node -v

# yarn
yanr -v

# npm
npm -v

# pnpm
pnpm -v

# go
go version
```

### 重新构建
VSCode中 输入`Ctrl/Command + Shift + P`，然后输入 `Rebuild` -> Dev Containers Rebuild