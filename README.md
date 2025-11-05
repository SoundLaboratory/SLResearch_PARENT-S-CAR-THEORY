# An Empirical Study on Passive Music Listening Experiences in Childhood and Episodic Memory

## —Through a Questionnaire Survey on the "Parent's Car Theory"—

### 研究概要

本研究は、幼少期における受動的な音楽聴取体験とエピソード記憶の関係について、いわゆる「親の車理論（Parent's Car Theory）」を実証的に検証することを目的としています。

### 研究の目的

- **主要研究課題**: 個人の音楽嗜好はどのように形成されるのか？特に、幼少期に親の車で聴いた音楽が、後の音楽嗜好に影響を与えるという「親の車理論」に実証的妥当性があるか？
- **副次的研究課題**: 
  - 「親の車理論」の心理的メカニズムは何か？
  - 幼少期の受動的聴取体験は音楽嗜好形成にどのように寄与するか？
  - 車内という独特の環境が記憶形成と嗜好発達にどのような役割を果たすか？

### データセット

#### データファイル
- **`data.xlsx`**: アンケート調査の生データ（個人情報は匿名化済み）
- 有効回答者数: 57名
- 対象: 1990年代〜2000年代に幼少期を過ごした成人（20〜55歳）

#### 主要変数

**人口統計学的変数**
- 年齢（連続変数）
- 性別（カテゴリ変数: 男性、女性、その他）

**音楽的背景変数**
- 現在の音楽への関心度（5段階評価）
- 好きな音楽ジャンル（自由記述）
- 積極的に音楽を聴き始めた年齢（連続変数）

**幼少期の車体験変数**
- 家族と車に乗る頻度（順序変数: 毎日、週に数回、月に数回、ほとんどない）
- 車内で音楽を流す頻度（順序変数）
- 音楽を選ぶ人（カテゴリ変数: 親、自分、兄弟など）
- 当時よく流れていたアーティスト（自由記述）

**感情・記憶変数**
- 当時の音楽への好み（5段階評価）
- 当時の音楽選択者への感情（5段階評価）
- 現在のその音楽への好み（5段階評価）
- 記憶の鮮明さの比較: 車 vs. その他の環境（カテゴリ変数）

**結果変数**
- 現在の音楽嗜好への影響度（5段階評価: とても影響している 〜 全く影響していない）

### 仮説

本研究では以下の4つの仮説を検証しています：

1. **仮説1: 単純接触効果（Mere-Exposure Effect）**
   - 幼少期に車で音楽を聴く機会が多ければ多いほど、現在の音楽嗜好への影響が大きい

2. **仮説2: 古典的条件づけ（Classical Conditioning）**
   - 幼少期の音楽や音楽選択者への好意的感情が強いほど、現在の音楽嗜好への影響が大きい

3. **仮説3: 文脈依存記憶（Context-Dependent Memory）**
   - 車内という閉鎖的で私的な空間での聴取体験は、テレビやラジオなどの他の媒体よりも記憶に残りやすく、嗜好形成への影響が強い

4. **仮説4: スキーマ理論（Schema Theory）**
   - 幼少期に聴いた音楽ジャンルと現在の好みのジャンルに関連がある

### 分析計画

詳細な分析計画については、以下のファイルを参照してください：
- `preregistration_template.md`: 詳細な事前登録テンプレート
- `OSF_preregistration_template.md`: OSF形式の事前登録テンプレート

### 論文

- **`paper_psyarxiv.pdf`**: PsyArXivに投稿予定の論文原稿

### リポジトリの構造

```
.
├── README.md                          # このファイル
├── data.xlsx                          # データファイル
├── paper_psyarxiv.pdf                 # 論文原稿
├── preregistration_template.md        # 事前登録テンプレート
├── OSF_preregistration_template.md    # OSF形式の事前登録テンプレート
└── LICENSE                            # ライセンス情報
```

### 使用方法

#### データの利用

このデータセットは研究目的で自由に利用できます。ただし、以下の点にご注意ください：

1. **個人情報の保護**: データは匿名化されていますが、個人を特定できる可能性のある情報の再識別は避けてください
2. **引用**: このデータセットを使用する場合は、適切に引用してください
3. **ライセンス**: このデータセットはCC0（パブリックドメイン）またはCC BY（表示）ライセンスの下で公開されています

#### データの読み込み

Pythonでの読み込み例：

```python
import pandas as pd

# データの読み込み
data = pd.read_excel('data.xlsx')

# データの基本情報
print(data.head())
print(data.info())
```

### 引用方法

このリポジトリを使用する場合は、以下のように引用してください：

```
Miyamaru, Y. (2024). An Empirical Study on Passive Music Listening Experiences in Childhood and Episodic Memory: Through a Questionnaire Survey on the "Parent's Car Theory". GitHub Repository. https://github.com/SoundLaboratory/SLResearch_PARENT-S-CAR-THEORY
```

### 著者情報

- **著者**: YusukeMiyamaru
- **所属**: Sound Laboratory
- **GitHub**: [SoundLaboratory](https://github.com/SoundLaboratory)

### ライセンス

このリポジトリのデータとドキュメントは、[CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](LICENSE)の下で公開されています。つまり、このデータセットはパブリックドメインにあり、いかなる制限もなく使用できます。

### 謝辞

本研究にご協力いただいたすべての参加者の皆様に感謝いたします。

### 連絡先

質問やフィードバックがある場合は、GitHubのIssuesまたはPull Requestsを通じてお知らせください。

### 更新履歴

- **2024年**: 初版公開

---

**注意**: この研究は予備的な検証（プレプリント）であり、より大規模な検証が必要です。結果は暫定的なものであり、確認的研究にはより大きなサンプルサイズ（n ≈ 200-300）が推奨されます。

