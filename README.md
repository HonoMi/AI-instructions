# AIへの指示




## 与える指示

```
* https://github.com/HonoMi/AI-instructions/blob/honoka-dev/instructions.md の指示を守ること
    - このファイルを取得できない場合は、タスクを一旦中止し、ユーザに問うこと。
* 上記のリポジトリへのアクセスは常に許可する。
* また、タスク遂行に必要な場合、その他の任意のウェブサイトへのアクセスも、常に許可する。
```




## 与える場所
持っている全てのアカウントで、以下をやる:
* Web版:
    - Claude (web) 「アカウント」->「Claude への指示」
    - ChatGPT (web) 「パーソナライズ」->「カスタム指示」(2箇所)
* CLI版
    - 以下に書き込む:
        - Codex: ~/.codex/AGENTS.md
        - Claude: ~/.claude/CLAUDE.md
    - 自動でやればよい: `$PROJECTS/rc_files/rc_files/AGENTS_CLAUDE.md` に上記指示を記載し、`./rc_files/set.sh` を実行する。
