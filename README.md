# gpa

[![test](https://github.com/Saito-Ayumu/gpy/actions/workflows/test.yml/badge.svg)](https://github.com/Saito-Ayumu/gpy/actions/workflows/test.yml)

成績(S,A,B,C,D)を入力しGPAを計算します。

---

## 使い方

```bash
$ echo S A B C D | ./gpa
2.00
```

---

## インストール
```bash
git clone https://github.com/Saito-Ayumu/gpy
cd gpy
chmod +x gpa test.bash
```
---

## 成績からのGPA算出

* 入力: 成績"S A B C D"(空白区切り)
* 出力: GPAを1行で出力
* 無効な成績:無視

---

## 必要なソフトウェア
- Python
    - テスト済みバージョン: 3.7 ~ 3.10

---

## テスト環境
- Ubuntu 24.04 LTS

--- 

## ライセンス

このソフトウェアパッケージは，BSD-3-Clauseライセンスの下，再頒布および使用が許可されます．

© 2025 Ayumu Saito
