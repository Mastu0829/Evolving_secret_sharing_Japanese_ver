# Evolving_secret_sharing_Japanese_ver
# Evolving-secret-sharing

Evolving 2-Threshold Secret Sharing — XOR Implementation

XOR 演算による Evolving 型 2-しきい値秘密分散法の Google Colab 実装です。

> 本実装は学習目的の簡易モデルです。

---

## 概要

参加者数を事前に決めずに運用できる秘密分散法です。

- 2 人以上で秘密を復元できる

- 新しい参加者は逐次追加できる

- 既存参加者のシェアは変更されない

---

## 使い方

セルを上から順に実行してください。

| セル | 内容 |

|---|---|

| セル1 | クラス定義・シェア生成・復元 |

| セル2 | 参加者追加関数 |

| セル3 | 参加者追加・復元の実行例 |

セル3 の以下の行をコメントアウトすると、前回の状態を引き継いで参加者を追加できます。

```python

# ess = EvolvingSecretSharing(secret)

```

---

## ライセンス

MIT License
