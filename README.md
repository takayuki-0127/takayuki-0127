## 松浦 孝征（Takayuki Matsuura）

**できること：SQL でデータマートを設計し、Power BI（DAX・RLS）で見える化し、Python で回帰・予測モデルまで作れます。公的統計で交絡をそろえた効果の検証もしています。**

![YouTube の視聴回数と何が関連しているか（Power BI・重回帰）](https://raw.githubusercontent.com/takayuki-0127/youtube-data-mart/main/images/pbi_page4_drivers.png)

更新日：2026-10-25

- 銀行向け業務システムを作るエンジニアです（C#・SQL Server、約4年）。その前は損害保険会社の保険数理グループで、統計を使って保険引受のリスクを分析していました。
- 副業で、クライアント向けのレポート作成と SNS の数値集計を約2年続けています。
- いまはデータ分析・BI の仕事に向けて、SQL Server・Power BI・Python で自分のデータを分析しています。統計検定2級・基本情報技術者。

### 看板記事（公的データ × 手法をくわしく）

| 記事 | 手法 |
|---|---|
| [F01 最低賃金の引き上げは、雇用を減らしたのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F01_minimum_wage_did) | 差の差・イベントスタディ・プラセボ・並べ替え検定・wild cluster bootstrap |
| [F02 コロナがなかったら、赤ちゃんは何人多かったのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F02_births_counterfactual) | 時系列の反実仮想（SARIMA・ETS・Prophet）・バックテスト |
| [F03 地価を決めているのは何か？ 全国2.6万地点を機械学習で読む](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F03_land_price_ml) | LightGBM・空間ブロック CV・SHAP・部分依存 |
| [F04 Go To トラベルは宿泊をどれだけ増やしたのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F04_goto_causalimpact) | ベイズ構造時系列・差の差・合成コントロール |
| [F05 医療費の地域差は「県」と「市町村」のどちらで決まるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F05_medical_cost_hierarchical) | 階層ベイズモデル（PyMC）・分散の分解・部分プーリング |
| [F06 高齢化は地図の上で固まっているか？ 札幌・横浜・福岡の町丁字で見る](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F06_aging_spatial) | 空間自己相関（Moran's I・LISA）・面積按分 |
| [F07 新卒は何年目に辞めやすいのか？ 30年分の卒業年を生存分析で追う](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F07_turnover_survival) | 離散時間ハザード（生存分析）・卒業年コホート・景気との回帰 |
| [F08 1,740市区町村を62の指標で分けると何タイプか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F08_municipal_segments) | PCA・UMAP・クラスタリング・ブートストラップ安定性 |
| [F09 国会で「賃上げ」はいつから語られるようになったのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F09_diet_text) | テキストマイニング（API 取得・形態素解析・共起ネットワーク・LDA） |
| [F10 人の流れで見ると、日本はいくつの「圏」に分かれるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F10_mobility_network) | ネットワーク分析（PageRank・Leiden 法）・解像度の比較 |
| [F11 消費増税の「駆け込み」と「反動」はどれだけだったか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F11_tax_hike_event) | イベントスタディ・プラセボ・差の差の差 |
| [F12 公的統計を毎月自動で更新する「くらしの指標」パイプライン](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F12_stats_pipeline) | e-Stat→DuckDB→dbt（テスト20本）・Streamlit・Actions |
| [F13 失業率を来月まで予測できるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F13_unemployment_forecast) | 予測モデルの比較（ARIMA・ElasticNet・LightGBM）・ローリング評価・DM 検定 |
| [F14 コンパクトシティの計画で、中心部の人口密度は保てたか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F14_compact_city_psm_did) | 傾向スコアマッチング・差の差・Callaway–Sant'Anna 型 |
| [F15 県境をまたぐと最低賃金が違う。隣どうしの町で雇用は違ったか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F15_border_minwage) | 境界不連続デザイン・ペア固定効果・三重差・検出力 |
| [F16 保育所に通う子どもが増えた町で、女性は働きに出たのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F16_childcare_dml) | ダブル機械学習（DML）・交差適合・重回帰との比較・プラセボ |
| [F17 最低賃金の影響が大きかったのはどんな県か？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F17_minwage_causal_forest) | 因果フォレスト・効果の異質性の検証（BLP・GATES）・プラセボ |
| [F18 景気は今どうなのか？ GDP を公表前に推定する](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F18_nowcast_dfm) | ダイナミックファクターモデル（状態空間・カルマンフィルタ）・ナウキャスト |
| [F19 小さな町の検診受診率は、どこまで信用できるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F19_small_area_fh) | 小地域推定（Fay–Herriot モデル・経験ベイズ） |
| [F20 出生率は隣の町と似るのか？ 空間回帰で考える](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F20_tfr_spatial_regression) | 空間ラグ・空間誤差モデル・GWR |
| [F21 公的統計の「いつもと違う動き」を自動で見つける](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F21_anomaly_detection) | 異常検知（STL・Isolation Forest・変化点検出） |
| [F22 明日の電力需要はどこまで当てられるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F22_power_demand_forecast) | 時系列 CV・ベースライン比較・LightGBM・誤差分析・SHAP |
| [F23 救急車をどこに置けば、到着が早くなるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F23_ambulance_location) | 数理最適化（p-median・最大カバー）・道路距離（OSRM） |
| [F25 経済白書41年分を文埋め込みで読む](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F25_whitepaper_embeddings) | 文埋め込み（ruri-v3）・クラスタリング・意味検索 |
| [F26 政策の効果を見つけるには、何県・何年のデータが要るのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F26_power_simulation) | 検出力シミュレーション（差の差のモンテカルロ）・標準誤差の比較 |
| [F27 市区町村の死亡率の地図を、ぶれずに描く](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F27_disease_map_bym2) | 空間ベイズ（BYM2、PyMC）・公表のベイズ推定値との比較 |
| [F28 法人は何年続くのか？ 150万法人の登記を生存分析で追う](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F28_corporate_survival) | 生存分析（Kaplan–Meier・Cox 比例ハザード・比例ハザードの確認） |
| [F29 北陸新幹線の金沢延伸で、石川県の宿泊客はどれだけ増えたか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F29_shinkansen_sdid) | 合成コントロール・Synthetic DID・Augmented SCM・プラセボ |
| [F31 60歳・65歳で、働く人はどれだけ減るのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F31_retirement_rdd) | 回帰不連続（年齢）・偽の境界（プラセボ） |
| [F32 所得の高い町と低い町で、効いている要因は同じか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F32_income_quantile) | 分位点回帰・ブートストラップ |
| [F33 人の移動は距離でどれだけ減るのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F33_migration_gravity) | 重力モデル（PPML・固定効果）・対数の最小二乗法との比較 |
| [F34 同じお金で、どの市町村が多くのサービスを出しているか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F34_municipal_efficiency) | 包絡分析法（DEA）・確率的フロンティア（SFA）・手法による順位の違い |
| [F35 景気の「山」と「谷」をデータだけで当てられるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F35_business_cycle_markov) | マルコフ切り替えモデル・景気基準日付との比較・リアルタイム判定 |
| [F36 全国と47都道府県の予測を、足し算が合うようにそろえると？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F36_hierarchical_forecast) | 階層時系列予測の整合（MinT・ボトムアップ・トップダウン）・ローリング予測 |
| [F37 地価の予測に「この範囲に9割入る」を付けられるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F37_conformal_land_price) | コンフォーマル予測（分割・CQR）・空間ブロックCVでの当たり方 |
| [F38 観光客が1兆円使うと、日本全体の生産はいくら増えるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F38_input_output_tourism) | 産業連関分析（逆行列・1次／2次波及・雇用誘発） |
| [F39 物価・賃金・金利は、どれがどれを動かしているのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F39_causal_discovery_macro) | 因果探索（VAR-LiNGAM・PC）とグレンジャー因果の比較 |
| [F40 所得の格差は「県の間」と「県の中」のどちらにあるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F40_inequality_decomposition) | タイル指数の分解（県の間・県の中）・ジニ係数の分解 |
| [F41 欠けているデータを埋めると、結論は変わるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F41_missing_data_mi) | 多重代入法・欠測の仕組みのシミュレーション |
| [F42 季節調整を自分でやると、公表値と同じになるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F42_seasonal_adjustment) | X-13ARIMA-SEATS で公表値を再現・曜日／祝日の調整・STL との比較 |
| [F43 金利が上がると、何か月後に何が動くのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F43_local_projections) | 局所射影とVARの比較・再帰的識別 |
| [F44 出生率のトレンドはいつ折れたのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F44_structural_breaks) | 構造変化の検定（Bai–Perron・CUSUM） |
| [F45 将来人口の推計は、自分で再現できるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F45_population_projection) | コーホート要因法の自作・2025年国勢調査での答え合わせ |
| [F46 雇用が増えた町に、人は集まったのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F46_bartik_iv) | シフトシェア（バーティク）操作変数・Rotemberg 重み・事前トレンドの検証 |
| [F47 都市ごとの「食の好み」を、行列分解で取り出せるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F47_food_nmf) | 非負値行列因子分解（NMF）・安定性の確認・PCA との比較 |
| [F48 ガソリンが10%上がると、買う量は何%減るか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F48_gasoline_elasticity) | 需要の価格弾力性・操作変数法・短期と長期 |
| [F49 平均寿命の県の差は、何歳の死亡で生まれているのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F49_life_expectancy_decomposition) | 生命表の自作・Arriaga 法（年齢別分解） |
| [F50 GDP の速報は、あとでどれだけ直されるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F50_gdp_revisions) | リアルタイムデータ分析（速報と確報の改定）・偏りの検定 |
| [F51 保育所の整備は、出生率に「女性の就業」を通じて効いたのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F51_childcare_mediation) | 媒介分析・感度分析 |
| [F52 インフルエンザは、どの県からどの県へ広がるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F52_influenza_spread) | 時空間の自己回帰・Moran's I・順位の一貫性 |
| [F53 日銀の声明文は、いつ「強気」から「弱気」に変わったか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F53_boj_statement_tone) | テキストの感情スコア（辞書法・文の埋め込み） |
| [F54 働く女性の賃金は、働いている人だけを見ると高く見えるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F54_heckman_women_wage) | 選択バイアスの補正（Heckman の2段階、集計データ版） |
| [F55 ベイズで出生数を予測すると、予測の幅はどう変わるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F55_births_bsts) | ベイズ構造時系列（PyMC）・予測区間のバックテスト |
| [F56 住宅価格指数を「繰り返し売買法」で作ると、ヘドニックと同じになるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F56_repeat_sales_index) | 繰り返し売買法（Case–Shiller）・ヘドニック指数との比較・築年の補正 |

### ポートフォリオ

| リポジトリ | 何ができるか |
|---|---|
| [youtube-data-mart](https://github.com/takayuki-0127/youtube-data-mart) | CSV を pandas → SQL Server（stg・mart のスタースキーマ）→ Power BI（RLS つき）とつなぎ、重回帰で「視聴回数に何が効いているか」を確かめられる。[SQL 面接用の5問](https://github.com/takayuki-0127/youtube-data-mart/blob/main/docs/SQL面接用の5問.md)（gaps and islands・パレートなど）つき。[予測モデル（LightGBM・時系列 CV・SHAP）](https://github.com/takayuki-0127/youtube-data-mart/blob/main/notebooks/e_06_predict_views.ipynb)と、[同じウィンドウ関数の BigQuery 版](https://github.com/takayuki-0127/youtube-data-mart/tree/main/extras/bigquery)も |
| [japan-open-data-notes](https://github.com/takayuki-0127/japan-open-data-notes) | 日本の公的統計（e-Stat・気象庁・日銀・国土交通省など）を使った分析を **1記事1フォルダで220本以上**まとめたリポジトリ。各フォルダにデータ・コード・図・結果と「このデータで言えないこと」まで。手法は重回帰・固定効果・合成コントロール・ヘドニック指数・VAR・ランダムフォレスト・要因分解・クラスタリングなど。代表例は下の表 |
| ↳ [000_women_labor](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/000_women_labor) | 全国1,739市区町村で「何が女性の労働力率を左右しているか」を重回帰で検証。交絡と都道府県の固定効果をそろえ、頑健性チェックと「この回帰で言えないこと」まで。[note の解説](https://note.com/takayukimatsuura/n/n683afeafc893) |
| [youtube-views-predictor](https://github.com/takayuki-0127/youtube-views-predictor) | 公開前の条件から YouTube の再生数を予測する Streamlit アプリ（LightGBM・SHAP のウォーターフォール図・時系列 CV、予測範囲の当たり方も表示）。**[アプリを開く](https://takayuki-youtube-views.streamlit.app/)** |
| [video-analysis-sample](https://github.com/takayuki-0127/video-analysis-sample) | 公開データ（YouTube 急上昇・日本・12,909本）を自作の分析テンプレートに通し、「わかったこと → 次の打ち手」の1枚レポートまで出したサンプル |
| [analysis-samples](https://github.com/takayuki-0127/analysis-samples) | 公開データ（SNS・EC・アンケート）で、仮説 → 分析 → 次の打ち手（確かめ方つき）まで1枚にまとめた分析サンプル3本と、Power BI の月次ダッシュボード1本。ロジスティック回帰・RFM／コホート・カイ二乗検定・DAX。英語の要約つき。[一覧 PDF](https://github.com/takayuki-0127/analysis-samples/blob/main/analysis_samples_overview.pdf) |
| [bdb2027-combine-transfer](https://github.com/takayuki-0127/bdb2027-combine-transfer) | Kaggle の分析コンペ「NFL Big Data Bowl 2027」の Writeup の要約。コンバインの測定値のうち何が試合に移るかを、測定の再現性から出した上限と比べて整理（最高速は移る・スタートの加速は移らない）。[本体ノートブック](https://www.kaggle.com/code/takayuki0127/what-transfers-from-the-combine-bdb-2027)・[追加分析](https://www.kaggle.com/code/takayuki0127/bdb-2027-follow-up-analyses) |
| [youtube-analytics-powerbi](https://github.com/takayuki-0127/youtube-analytics-powerbi) | 同じ指標（7日移動平均など）を SQL・DAX・pandas の3通りで出し、答えがそろうことを確かめられる |

### 公的データの分析（代表例）

| 記事 | 手法 |
|---|---|
| [029 コロナで東京への人の流れはどれだけ減ったか](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/029_covid_tokyo_synth) | 合成コントロール法・プラセボ検定 |
| [022 保育所を増やした県で出生率は上がったか](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/022_nursery_birthrate_fe) | 二方向固定効果（都道府県×年のパネル） |
| [037 東京の中古マンションは10年で何%上がったか](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/037_tokyo_condo_hedonic) | ヘドニック回帰による品質調整済み価格指数 |
| [035 円安はどれくらい物価を上げるか](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/035_yen_prices_var) | 日銀 API でデータ取得 → VAR・インパルス応答 |
| [095 就業者の増加の内訳](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/095_employment_growth) | 要因分解（人口要因と就業率要因） |
| [137 市区町村の歳出の4割は福祉](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/137_welfare_spending) | e-Stat の CSV から必要な行を抜き出して市区町村×年度の表を作るところからコード化 |

全記事の一覧は [japan-open-data-notes の README](https://github.com/takayuki-0127/japan-open-data-notes#readme) にあります。

### note

学んだことや、作ったものの裏側を書いています。

- [note のトップ](https://note.com/takayukimatsuura)：公的データの分析記事を毎日公開しています
- [自分の YouTube チャンネルを SQL と Power BI で分析してみた（7日移動平均で答え合わせ）](https://note.com/takayukimatsuura/n/n5970e2120a3f)
- [女性の労働力率は何で決まる？ 全国1,739市区町村の公開データで調べてみた（e-Stat・重回帰）](https://note.com/takayukimatsuura/n/n683afeafc893)
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
