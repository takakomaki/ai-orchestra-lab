# リポジトリ構造ツリー（UTF-8 / 文字化けなし）

このファイルは `C:\doc\ai-orchestra-lab` のフォルダ・ファイル構造をツリー化したものです。

## 生成方法

```powershell
pwsh -NoProfile -File .\\tools\\generate_repo_tree_md.ps1 -Path . -OutputFile .\\memory\\repo_tree.md -ExcludeGit
```

## ツリー（`.git` 除外）

```text
ai-orchestra-lab
├── .github
│   ├── issue_template
│   │   └── task.md
│   └── workflows
│       ├── ai-orchestra-ci.txt
│       ├── issue-claude-comment.yml
│       ├── issue-gemini-comment.yml
│       ├── issue-gpt-comment.txt
│       └── sample.txt
├── drafts
│   └── .gitkeep
├── inbox
│   └── .gitkeep
├── orchestra
│   └── .gitkeep
├── output
│   └── ai-orchestra-intro.md
├── tools
│   ├── generate_repo_tree_md.ps1
│   └── tree_utf8.ps1
├── .gitignore
├── README.md
└── test.md
```

