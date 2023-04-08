# Rime auto deploy

## 系统

⚠️ 支持：

* MacOS ✅
* Linux 发行版 ✅
* Windows ❌

![rime](./images/rime.jpeg)
![result](./images/result.png)
![working](./images/working.png)

## 依赖

安装 `Ruby 3`

* Mac OS `brew install ruby`
* Debian distro `sudo apt install ruby`

⚠️ MacOS脚本会自动帮助安装 Rime，Linux下由于发行版、Rime衍生方式太多，需要自行提前安装Rime。

```
For Fcitx5, install fcitx5-rime.
For Fcitx, install fcitx-rime.
For IBus, install ibus-rime.

more: https://wiki.archlinux.org/title/Rime
```

### 参考&感谢：

* 流程参考 Tiwtter： @lewangdev
* 配置来源(fork了一版本）：https://github.com/iDvel/rime-ice


# 使用方法

step1: 克隆到本地

`git clone --depth=1 https://github.com/Mark24Code/rime-auto-deploy.git --branch v2.0.0`

step2: 执行部署脚本

`./installer.rb`

# 自动部署内容：

## step1: 确认安装 Rime 输入法，自动安装

需要用户自行登出，重进系统，设置Rime输入法为系统输入法

## step2: 备份 Rime 默认配置

## step3: 自动安装 Rime-ice 配置

## step4: 自动追加自定义配置模板


