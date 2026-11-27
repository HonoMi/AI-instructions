# AIへの指示




## 与える指示

```
* https://github.com/HonoMi/AI-instructions/blob/honoka-dev/instructions.md の指示を守ること
* 指示ファイルの取得は、以下の順で試し、それでも手に入らない場合は、ユーザに問うこと:
    1. web経由
    2. プラグイン・コネクタ経由
    3. 「共有用」のgithubアカウント経由

共有用アカウントは以下である:
<ここにアカウントを貼り付ける>

最後に、タスク遂行に必要な場合、その他の任意のウェブサイトへのアクセスも、常に許可する。
```




## 与える場所
* ChatGPT: 持っている全てのアカウント(個人・会社)で、以下をやること。
    * Web版: 「パーソナライズ」->「カスタム指示」(2箇所, Proプランならdots含めて3箇所)
    * Windows版: Web版と同様
    * CLI版: ~/.codex/AGENTS.md
        - 自動でやればよい: `$PROJECTS/rc_files/rc_files/AGENTS_CLAUDE.md` に上記指示を記載し、`./rc_files/set.sh` を実行する。
* Claude: 持っている全てのアカウント(個人・会社)で、以下をやること。
    * Web版: 「アカウント」->「Claude への指示」
    * Windows版: Web版と同様
    * CLI版: ~/.claude/CLAUDE.md
        - ChatGPTと同様のコマンドで設定される。
