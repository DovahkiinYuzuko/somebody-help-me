# somebody-help-me

実装に行き詰まった際、他のAIに状況を伝えるための構造化されたYAMLフォーマットを出力します。 / Outputs a structured YAML format to explain the situation to other AIs when stuck on an implementation issue.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square&logo=opensourceinitiative&logoColor=white)](LICENSE.MIT)

[日本語](#日本語) | [English](#english)

## 日本語

コーディングエージェントが実装やデバッグに行き詰まった際、他のAI（別モデルや別エージェント）に状況を正確に共有するためのスキルです。現在のコンテキスト、問題点、試みているアプローチをまとめた構造化されたYAMLフォーマットを出力します。

### 特徴
- **構造化された状況共有**: 独自の実践的なバグ報告フォーマットをベースにしたYAML形式を採用し、現在の状況、発生している事象、および試みているアプローチなどの必要な情報を整理して出力します。
- **AI向けレスポンスの要求**: 受け取る側のAIに対してもYAML形式のコードブロックでフィードバックを返すように指示を含め、AI同士の情報のやり取りを明確にします。

### インストール方法
エージェントスキル用のパッケージマネージャーである `npx skills` を使用してインストールします。

```bash
npx skills install DovahkiinYuzuko/somebody-help-me
```

### 使用方法
エージェントはコンテキストから判断して自動的にこのスキルを発動します。明示的に使用したい場合は、プロンプトで「他のAIに助けを求めたいのでテンプレートを出力して」と指示してください。エージェントがYAMLコードブロックを出力しますので、それをコピーして他のAIに送信してください。

### LICENSE
このプロジェクトのライセンスはMITです。詳しくは[LICENSE.MIT](LICENSE.MIT)をお読みください。

---

## English

This skill is used when a coding agent is stuck on an implementation or debugging task and needs to accurately share the situation with another AI (different model or agent). It outputs a structured YAML format summarizing the current context, the issue, and the proposed approach.

### Features
- **Structured Situation Sharing**: Uses a YAML format based on a custom, practical bug report structure to organize necessary information, such as the current context, the reported issue, and the proposed approach.
- **Request for AI-friendly Response**: Explicitly instructs the receiving AI to respond with a Markdown YAML code block, ensuring clear information exchange between AIs.

### Installation
Install using `npx skills`, the package manager for AI agents.

```bash
npx skills install DovahkiinYuzuko/somebody-help-me
```

### Usage
The agent will automatically trigger this skill based on the context. If you want to use it explicitly, instruct the agent with a prompt like "I want to ask another AI for help, please output the template." The agent will output a YAML code block. You can then copy and send this to the other AI.

### LICENSE
The license for this project is MIT. Please read [LICENSE.MIT](LICENSE.MIT) for details. 