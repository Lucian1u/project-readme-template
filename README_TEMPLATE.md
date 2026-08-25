<!--
使用方法：
1. 复制本文件到项目根目录并改名为 README.md。
2. 替换所有 {{...}} 占位符。
3. 删除不适用的可选章节，不要留下空标题。
4. 只写已经实现、可以核验的事实。
5. 发布前按 STANDARD.md 验收，并删除本注释。
-->

<!-- 可选：只有确实有清晰、可读的演示图时才保留。不要拿装饰图代替产品证据。 -->
<p align="center">
  <img src="{{HERO_PATH}}" alt="{{HERO_ALT}}" width="100%">
</p>

# {{PROJECT_NAME}}

{{ONE_SENTENCE_PROMISE}}

<!-- 主按钮最多两个。优先顺序：直接使用 / 安装 / 查看演示 / 下载。 -->
**[{{PRIMARY_ACTION_LABEL}}]({{PRIMARY_ACTION_URL}})** · [{{SECONDARY_ACTION_LABEL}}]({{SECONDARY_ACTION_URL}})

**状态：** {{PROJECT_STATUS}}

{{PROJECT_NAME}} 是一个面向 {{TARGET_USER}} 的 {{PROJECT_TYPE}}。当 {{USER_SITUATION}} 时，它会 {{CORE_OUTCOME}}。

## 演示

<!-- 可选。优先放 30–90 秒短视频、动图或一张能证明核心结果的截图。 -->

{{DEMO}}

## 为什么做这个项目

{{PROBLEM_CONTEXT}}

这个项目只解决一件事：{{SINGLE_PROBLEM}}。

## 核心能力

<!-- 每一条都必须已经实现；避免“强大、智能、无缝”等无法核验的形容词。 -->

- **{{FEATURE_1_NAME}}** — {{FEATURE_1_RESULT}}
- **{{FEATURE_2_NAME}}** — {{FEATURE_2_RESULT}}
- **{{FEATURE_3_NAME}}** — {{FEATURE_3_RESULT}}

## 快速开始

### {{INSTALL_OR_OPEN_METHOD}}

```bash
{{TESTED_INSTALL_COMMAND}}
```

然后：

1. {{FIRST_STEP}}
2. {{SECOND_STEP}}
3. {{VISIBLE_RESULT}}

<!-- 如果项目无需安装，直接写打开链接或下载文件的步骤，不要硬塞命令行。 -->

## 使用示例

### {{USE_CASE_1}}

```text
{{COPYABLE_EXAMPLE_1}}
```

预期结果：{{EXPECTED_RESULT_1}}

### {{USE_CASE_2}}

```text
{{COPYABLE_EXAMPLE_2}}
```

预期结果：{{EXPECTED_RESULT_2}}

## 工作原理

```text
{{INPUT}}
  ↓
{{PROCESS_STEP_1}}
  ↓
{{PROCESS_STEP_2}}
  ↓
{{OUTPUT}}
```

{{HOW_IT_WORKS_EXPLANATION}}

## 交付内容

| 内容 | 作用 |
|---|---|
| `{{OUTPUT_PATH_1}}` | {{OUTPUT_PURPOSE_1}} |
| `{{OUTPUT_PATH_2}}` | {{OUTPUT_PURPOSE_2}} |

## 边界与限制

这个项目不会：

- {{NON_GOAL_1}}
- {{NON_GOAL_2}}
- {{NON_GOAL_3}}

{{IMPORTANT_LIMITATION}}

## 隐私与安全

<!-- 如果项目接触用户文件、账号、网络或密钥，本节必填；完全不涉及也要用一句话说明。 -->

- {{DATA_HANDLING_RULE}}
- {{NETWORK_RULE}}
- {{SECRET_HANDLING_RULE}}

如需报告安全问题，请查看 [`SECURITY.md`](SECURITY.md)。

## 兼容性

| 环境 | 状态 | 说明 |
|---|---|---|
| {{ENVIRONMENT_1}} | {{VERIFIED_OR_NOT}} | {{COMPATIBILITY_NOTE_1}} |
| {{ENVIRONMENT_2}} | {{VERIFIED_OR_NOT}} | {{COMPATIBILITY_NOTE_2}} |

没有实际验证的环境应写“未验证”，不要写成“支持”。

## 仓库结构

```text
{{PROJECT_NAME}}/
├── {{PATH_1}}        # {{PATH_1_PURPOSE}}
├── {{PATH_2}}        # {{PATH_2_PURPOSE}}
├── README.md
└── LICENSE
```

## 开发与验收

```bash
{{TESTED_VERIFICATION_COMMAND}}
```

当前已经核验：

- {{VERIFIED_FACT_1}}
- {{VERIFIED_FACT_2}}

这不表示：{{UNVERIFIED_BOUNDARY}}。

## 项目状态

- 当前版本：{{CURRENT_VERSION_OR_STAGE}}
- 已完成：{{COMPLETED_SCOPE}}
- 尚未完成：{{REMAINING_SCOPE_OR_NONE}}
- 版本记录：[`CHANGELOG.md`](CHANGELOG.md)

## 参与项目

提交问题或改动前，请阅读 [`CONTRIBUTING.md`](CONTRIBUTING.md)。

## License

{{LICENSE_NAME}} — 见 [`LICENSE`](LICENSE)。
