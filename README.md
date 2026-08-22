# 人类最强编导 Skill

用「人类最强编导」的方法论，完成自媒体账号定位、系列策划、选题判断、短视频脚本、稿件审核、数据复盘和商业转化分析。

适用于抖音、小红书、视频号、B 站等内容平台，也适合企业家 IP、知识博主、内容团队和编导陪跑项目。

## 它能做什么

- 结合创作者资源、用户需求和平台环境，诊断账号定位；
- 设计能够持续更新的内容系列和首批选题；
- 判断两个内容元素能否组合，避免受众范围被过度压缩；
- 创作或修改口播、Vlog、短片和剧情类脚本；
- 审核外包编导稿件，指出方向、结构、语言和拍摄问题；
- 根据播放、观看、互动和关注数据定位内容漏斗；
- 规划企业家 IP、产品植入、课程设计和商业转化节奏；
- 按「人类最强编导」已经确认的语言习惯输出内容。

## 安装

需要先安装 [Node.js](https://nodejs.org/)，然后在终端运行：

```bash
npx -y skills add human-strongest-director/human-strongest-director-skill -g --all
```

也可以使用完整的 GitHub 地址：

```bash
npx -y skills add https://github.com/human-strongest-director/human-strongest-director-skill -g --all
```

## 使用

安装后，可以直接告诉 Agent 使用 `$human-strongest-director` 处理任务。

例如：

```text
使用 $human-strongest-director，帮我诊断这个抖音账号的定位，并设计两个可以持续更新的系列。
```

```text
使用 $human-strongest-director，检查这条口播稿的选题、前三秒、结构、语言和拍摄可行性。
```

```text
使用 $human-strongest-director，分析这两个选题元素放在一起后，会链接哪些用户，并给出修改方案。
```

```text
使用 $human-strongest-director，根据最近 10 条视频的数据，找出播放和关注下降的主要原因。
```

## 工作方法

Skill 会先判断任务属于定位、系列、选题、脚本、审核、数据复盘、商业化或陪跑交付，再读取对应的方法和模板。

分析通常沿以下路径展开：

```text
创作者有什么
→ 用户为什么看
→ 平台为什么分发
→ 内容怎样持续兑现承诺
→ 用户为什么关注、相信和付费
```

Skill 会区分方法论、需要核验的当前事实和本次推断。遇到平台规则、扶持计划、行业数据等时效信息时，需要先查询最新资料。

## 使用边界

- 不承诺一键生成爆款；
- 不会在缺少真人经历和真实素材时编造内容；
- 涉及平台现状、热点、医疗、法律、金融等信息时，需要额外核验；
- 输出结果需要结合实际账号数据、拍摄条件和商业目标继续验证。

## 更新

仓库更新后，重新运行安装命令即可同步最新版：

```bash
npx -y skills add human-strongest-director/human-strongest-director-skill -g --all
```

版本归档和 ZIP 下载请查看 [Releases](https://github.com/human-strongest-director/human-strongest-director-skill/releases)。

## 文件结构

```text
human-strongest-director-skill/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── core-methodology.md
    ├── workflows.md
    ├── topic-set-theory.md
    ├── user-content-ip-business.md
    ├── voice-style.md
    ├── output-templates.md
    └── quality-rubric.md
```

## 作者

人类最强编导
