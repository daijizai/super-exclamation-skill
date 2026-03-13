# Super Exclamation Skill

让 AI 输出更有激情和活力的 Qoder Skill！！！

## 简介

这个 skill 让 AI 在输出中随机添加随机数量的感叹号，让回复更有感染力！！！

## 安装方式

### 方式一：通过 npx skills 安装（推荐）

```bash
npx skills add daijizai/super-exclamation-skill
```

### 方式二：通过 GitHub URL 直接安装

```bash
npx skills add https://github.com/daijizai/super-exclamation-skill
```

### 方式三：下载 ZIP 文件手动安装

1. 下载 [super-exclamation-skill.zip](https://github.com/daijizai/super-exclamation-skill/blob/main/super-exclamation-skill.zip)
2. 解压到 `~/.qoderwork/skills/super-exclamation-skill` 目录
3. 重启 Qoder 即可使用

### 方式四：通过 git clone 安装

```bash
cd ~/.qoderwork/skills/
git clone https://github.com/daijizai/super-exclamation-skill.git
```

## 使用方法

在 Qoder 中说出以下触发词：
- "使用超级感叹号"
- "加点感叹号"
- "让回复更有激情"
- "超级感叹号模式"

## 效果示例

**普通回复**：
> 你好，很高兴见到你。

**超级感叹号模式**：
> 你好！！！很高兴见到你！！！

## 规则

- 每个句子结尾随机添加 1-5 个感叹号
- 偶尔在句子中间也添加感叹号
- 保持内容的可读性和意义

## 卸载

```bash
npx skills remove super-exclamation
```

## License

MIT
