# plain-orbit-mini

Systems programmer @aio-libs

处理日常小任务的工具

## 用法

```bash
cat data.txt | cargo run
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 备注

就是给自己省点事，没做太多抽象。

## 待办

- [ ] 支持从文件参数读入
- [ ] 加个输出格式选项
- [ ] 补点测试

## 安装

```bash
git clone https://github.com/USER/plain-orbit-mini.git
cd plain-orbit-mini
cargo build --release
```

## License

MIT
