gh コマンドを使用して、GitHubにissueを作成してください。
コマンドは以下です。

```zh
echo "# 概要 \n# なぜやるのか？ \n# ゴール \n# 納期" | gh issue create -t "$ARGUMENTS" --body-file=-
```

引数が渡されていなかった場合は、処理を中断し、以下の文言を返してください。
「引数は必須です。引数はissueのタイトルとして渡されます。」
