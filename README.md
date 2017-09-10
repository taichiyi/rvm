
# rvm(Ruby Version Manager)

[list](#list) [install](#install) [use](#use) [remove](#remove) 


## list

列出已知的 Ruby 版本

### 语法
```Bash
rvm list known
```

### 实例

列出已知的 Ruby 版本
```
rvm list known
```

查询已经安装的 Ruby 版本
```
rvm list
```


## install

安装一个 Ruby 版本

### 语法
```Bash
rvm install <version>
```

### 实例

安装`2.2.0`版本
```
rvm install 2.2.0
```


## use

切换 Ruby 版本

### 语法
```Bash
rvm use <version>
```

### 实例

切换`2.2.0`版本
```
rvm use 2.2.0
```

如果想设置为默认版本，这样一来以后新打开的控制台默认的 Ruby 就是这个版本
```
rvm use 2.2.0 --default 
```


## remove

切换 Ruby 版本

### 语法
```Bash
rvm remove <version>
```

### 实例

切换`1.8.7`版本
```
rvm remove 1.8.7
```


## 参考链接

[https://ruby-china.org/wiki/rvm-guide](https://ruby-china.org/wiki/rvm-guide)  
