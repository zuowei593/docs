---
title: ticloud project list
summary: The reference of `ticloud project list`.
---

# ticloudプロジェクトリスト {#ticloud-project-list}

アクセス可能なすべてのプロジェクトをリストします。

```shell
ticloud project list [flags]
```

または、次のエイリアス コマンドを使用します。

```shell
ticloud project ls [flags]
```

## 例 {#examples}

アクセス可能なすべてのプロジェクトをリストします。

```shell
ticloud project list
```

アクセス可能なすべてのプロジェクトを JSON 形式でリストします。

```shell
ticloud project list -o json
```

## フラグ {#flags}

非対話型モードでは、必要なフラグを手動で入力する必要があります。対話型モードでは、CLI プロンプトに従って入力するだけです。

| 国旗          | 説明                                                                         | 必要  | ノート                      |
| ----------- | -------------------------------------------------------------------------- | --- | ------------------------ |
| -h, --help  | このコマンドのヘルプ情報                                                               | いいえ | 非対話型モードと対話型モードの両方で動作します。 |
| -o, --出力文字列 | 出力形式 (デフォルトでは`human` )。有効な値は`human`または`json`です。完全な結果を得るには、 `json`形式を使用します。 | いいえ | 非対話型モードと対話型モードの両方で動作します。 |

## 継承されたフラグ {#inherited-flags}

| 国旗             | 説明                                                                               | 必要  | ノート                                                               |
| -------------- | -------------------------------------------------------------------------------- | --- | ----------------------------------------------------------------- |
| --色なし          | 出力のカラーを無効にします。                                                                   | いいえ | 非対話モードでのみ動作します。インタラクティブ モードでは、一部の UI コンポーネントで色の無効化が機能しない可能性があります。 |
| -P、--プロファイル文字列 | このコマンドで使用されるアクティブな[ユーザープロフィール](/tidb-cloud/cli-reference.md#user-profile)を指定します。 | いいえ | 非対話型モードと対話型モードの両方で動作します。                                          |

## フィードバック {#feedback}

TiDB Cloud CLI に関して質問や提案がある場合は、お気軽に[問題](https://github.com/tidbcloud/tidbcloud-cli/issues/new/choose)を作成してください。また、貢献も歓迎します。