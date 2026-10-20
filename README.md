## 松浦 孝征（Takayuki Matsuura）

**できること：SQL でデータマートを設計し、Power BI（DAX・RLS）で見える化し、Python で回帰・予測モデルまで作れます。**

![YouTube の視聴回数と何が関連しているか（Power BI・重回帰）](https://raw.githubusercontent.com/takayuki-0127/youtube-data-mart/main/images/pbi_page4_drivers.png)

更新日：2026-10-21

- 銀行向け業務システムを作るエンジニアです（C#・SQL Server、約4年）。その前は損害保険会社の保険数理グループで、統計を使って保険引受のリスクを分析していました。
- 副業で、クライアント向けのレポート作成と SNS の数値集計を約2年続けています。
- いまはデータ分析・BI の仕事に向けて、SQL Server・Power BI・Python で自分のデータを分析しています。統計検定2級・基本情報技術者。

### ポートフォリオ

| リポジトリ | 何ができるか |
|---|---|
| [youtube-data-mart](https://github.com/takayuki-0127/youtube-data-mart) | CSV を pandas → SQL Server（stg・mart のスタースキーマ）→ Power BI（RLS つき）とつなぎ、重回帰で「視聴回数に何が効いているか」を確かめられる。[SQL 面接用の5問](https://github.com/takayuki-0127/youtube-data-mart/blob/main/docs/SQL面接用の5問.md)（gaps and islands・パレートなど）つき。[予測モデル（LightGBM・時系列 CV・SHAP）](https://github.com/takayuki-0127/youtube-data-mart/blob/main/notebooks/e_06_predict_views.ipynb)と、[同じウィンドウ関数の BigQuery 版](https://github.com/takayuki-0127/youtube-data-mart/tree/main/extras/bigquery)も |
| [video-analysis-sample](https://github.com/takayuki-0127/video-analysis-sample) | 公開データ（YouTube 急上昇・日本・12,909本）を自作の分析テンプレートに通し、「わかったこと → 次の打ち手」の1枚レポートまで出したサンプル |
| [analysis-samples](https://github.com/takayuki-0127/analysis-samples) | 公開データ（SNS・EC・アンケート）で、仮説 → 分析 → 次の打ち手（確かめ方つき）まで1枚にまとめた分析サンプル3本と、Power BI の月次ダッシュボード1本。ロジスティック回帰・RFM／コホート・カイ二乗検定・DAX。英語の要約つき。[一覧 PDF](https://github.com/takayuki-0127/analysis-samples/blob/main/analysis_samples_overview.pdf) |
| [bdb2027-combine-transfer](https://github.com/takayuki-0127/bdb2027-combine-transfer) | Kaggle の分析コンペ「NFL Big Data Bowl 2027」の Writeup の要約。コンバインの測定値のうち何が試合に移るかを、測定の再現性から出した上限と比べて整理（最高速は移る・スタートの加速は移らない）。[本体ノートブック](https://www.kaggle.com/code/takayuki0127/what-transfers-from-the-combine-bdb-2027)・[追加分析](https://www.kaggle.com/code/takayuki0127/bdb-2027-follow-up-analyses) |
| [youtube-analytics-powerbi](https://github.com/takayuki-0127/youtube-analytics-powerbi) | 同じ指標（7日移動平均など）を SQL・DAX・pandas の3通りで出し、答えがそろうことを確かめられる |

### note

学んだことや、作ったものの裏側を書いています。

- [note のトップ](https://note.com/takayukimatsuura)
- [自分の YouTube チャンネルを SQL と Power BI で分析してみた（7日移動平均で答え合わせ）](https://note.com/takayukimatsuura/n/n5970e2120a3f)
- [実績ゼロから「分析の副業」を始めるまでにやった4つのこと（公開データのサンプル・メニュー設計・提案文の型）](https://note.com/takayukimatsuura/n/nba02d238dfac)

### Kaggle

[kaggle.com/takayuki0127](https://www.kaggle.com/takayuki0127)：コンペにソロで参加しています。

- Featured コンペ「AI Agent Security - Multi-Step Tool Attacks」で上位17%（724 / 4,186）
- テーブルデータの Playground シリーズで上位18%・27%・30%
- Name That LLM（Featured・文章を書いた LLM を18種類から当てる）：参加中（2027年1月締め切り）。事前学習済み LLM（Qwen3-8B-Base）の中間層の出力を特徴量にし、重みは入れ子 CV で決めている
- NFL Big Data Bowl 2027（分析コンペ）：Writeup を提出済み（2026年10月）→ [要約と図](https://github.com/takayuki-0127/bdb2027-combine-transfer)
- Playground S6E10（航空会社の満足度予測、2026年10月）：結果は締め切り（10/31）後に記載

### 使っている技術

SQL Server（CTE・ウィンドウ関数）／Power BI（DAX・Power Query・RLS）／Python（pandas・statsmodels・scikit-learn・LightGBM・CatBoost）／C#／Azure
