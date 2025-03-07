# base on vscode-mybatisx

修复问题:
1. Mapper类中, 如果存在两个方法名为test123, test, 则`Go to Mapper xml`会在test123方法上生成两个
2. 在1的情况下, 跳转Mapper.xml时, 都会跳转到test123方法上.

This is porting version of [MybatisX](https://gitee.com/baomidou/MybatisX)

**Go to Mapper xml**

![](https://raw.githubusercontent.com/leftstick/vscode-mybatisx/master/images/gotoxml.gif)

**Create in Mapper xml**

![](https://raw.githubusercontent.com/leftstick/vscode-mybatisx/master/images/create.gif)

**Go to Mapper java**

![](https://raw.githubusercontent.com/leftstick/vscode-mybatisx/master/images/gotojava.gif)

## Install

Launch VS Code Quick Open (`cmd`/`ctrl` + `p`), paste the following command, and press enter.

```
ext install vscode-mybatisx
```

## LICENSE

[GPL v3 License](https://raw.githubusercontent.com/leftstick/vscode-mybatisx/master/LICENSE)

# release note

## version 1.2.0

### New Features

1. support multi workspaces

---

## version 1.1.0

### bug fixs

1. Stuck on plugin initializing

### New Features

1. Support low version of vscode
2. Determine the class name whether a Mapper or not by using namespace
