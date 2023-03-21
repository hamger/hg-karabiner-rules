# hg-karabiner-rules
my rules for Karabiner-Elements complex_modifications

### Usage
1. 安装[Karabiner-Elements](https://pqrs.org/osx/karabiner/index.html)
2. 拷贝 josn 文件到 `~/.config/karabiner/assets/complex_modifications` 目录下
3. 打开 `Karabiner-Elements Preferences` > `Complex Modifications` > `Add rules`引入规则

### rules
> 使用以下规则前需先引入 Karabiner-Elements 自带的`Change caps_lock to command+control+option+shift`规则（`caps_lock`转化为`left_shift`+`left_command`+`left_control`+`left_option`）。
> 如果你希望保留大写锁定，在开启上述规则**之前**，开启`Change caps_lock2 + backslash to caps_lock`（`caps_lock` + `\` 转化为大写锁定）

文件名 | 说明
-- | --
arrow.josn | `caps_lock` + `j`/`i`/`k`/`l` 转化为`←`/`↑`/`↓`/`→`
arrow2.josn | `right_command` + `a`/`w`/`s`/`d` 转化为`←`/`↑`/`↓`/`→`
arrow3.josn | `right_option` + `a`/`w`/`s`/`d` 转化为`←`/`↑`/`↓`/`→`
caps.josn | `caps_lock` + `backslash` 转化为 `caps_lock`
