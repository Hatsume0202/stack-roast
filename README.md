# 🎭 Stack Roast - 程序猿错误堆栈吐槽机

把你的程序错误堆栈变成戏精风格的吐槽文本！让枯燥的 debug 过程多一些欢乐~

## ✨ 功能

- 📋 **粘贴堆栈** → 自动解析 Python / JavaScript / Node.js 堆栈
- 🎤 **戏精吐槽** → 将错误类型、文件名、行号、变量名转换成幽默搞笑的中文吐槽
- 🎲 **再来一版** → 不满意？点一下换一种吐槽风格
- 📋 **一键复制** → 复制吐槽结果发给同事，一起乐一乐
- 📱 **响应式设计** → 手机上也能愉快使用
- ⌨️ **快捷键** → `Ctrl+Enter` / `Cmd+Enter` 快速吐槽

## 🚀 使用方式

1. 打开 `index.html`（直接双击即可，无需服务器）
2. 把终端里的报错堆栈粘贴到左边的大框框里
3. 点击 **「🔥 开始吐槽！」** 按钮
4. 享受戏精为你带来的幽默吐槽！

或者直接访问 GitHub Pages 部署版本。

## 🛠️ 支持的堆栈格式

| 语言/运行时 | 示例格式 |
|------------|---------|
| Python | `File "app.py", line 42, in <module>` + `ErrorType: msg` |
| JavaScript | `at funcName (file.js:15:22)` + `TypeError: msg` |
| Node.js | 同上 |
| 通用格式 | 包含文件名 + 行号 + 错误类型 |

## 🎯 示例

**输入（Python）：**
```
Traceback (most recent call last):
  File "app.py", line 42, in <module>
    print(user.name)
AttributeError: 'NoneType' object has no attribute 'name'
```

**输出：**
```
🎭 戏精吐槽报告 🎭
━━━━━━━━━━━━━━━━━━━━
啊哈！AttributeError！「这个对象没有这个属性」
——翻译成人话就是：你问一个哑巴要电话号码！📞

出事儿的地方在 app.py 的第 42 行！
这一行代码现在肯定很慌，因为它知道自己闯祸了！😱

「print(user.name)」——就这一行，就这！
一个程序员的尊严碎了一地！💔

那个叫 user 的变量又出问题了！
我就知道！它一直都不太靠谱！😒

总结：求求你了，用之前先判空好吗！
这种低级错误下次不要再犯了！！🔨💢
```

## 📂 项目结构

```
stack-roast/
├── index.html    # 主文件（内嵌 CSS + JS，可直接打开）
└── README.md     # 本文件
```

## 📄 许可

MIT License — 随便玩、随便改、随便吐槽！
