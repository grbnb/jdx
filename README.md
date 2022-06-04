# 版本主分支[点击跳转]

| 版本号 |
| - |
| [0.2.4](https://github.com/grbnb/jdx/tree/0.2.4) |
| [0.2.3](https://github.com/grbnb/jdx/tree/0.2.3) |
| [0.2.2](https://github.com/grbnb/jdx/tree/0.2.2) |
| [0.1.9](https://github.com/grbnb/jdx/tree/0.1.9) |

# 当前为同步分支
# 通过reposync方式进行代码同步到主分支


### 申请PAT

[点此来生成一个 token](https://github.com/settings/tokens/new) ，把 `repo`和`workflow` 两部分勾上，然后点击最下面的创建按钮。

### 填写PAT到Secrets

申请完毕后，在分支中点击`Settings`-`Secrets`-`New secret`

`name`填`PAT`，`Value`填入上方申请到的PAT,保存即可

### 手动触发一次代码同步

等待两分钟左右,能够发现代码全部同步过来
