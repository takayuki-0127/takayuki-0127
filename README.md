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
| [F57 インフルエンザの流行は、SIRモデルで再現できるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F57_flu_sir) | SIR／SEIR モデル・再生産数・山の予測 |
| [F58 合計特殊出生率は、年齢のどこで下がったのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F58_tfr_age_tempo) | 年齢別の分解・Bongaarts–Feeney のテンポ調整 |
| [F59 学力調査の県の順位は、毎年どれくらい入れ替わるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F59_test_rank_stability) | 順位の安定性・標本誤差による順位の区間・分散分解 |
| [F60 去年いちばん悪かった県は、今年よくなるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F60_regression_to_mean) | 平均への回帰・見かけの施策効果の補正・シミュレーション |
| [F61 小さい町の「ランキング1位」は、なぜ毎回入れ替わるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F61_funnel_eb_rankings) | ファンネルプロット・経験ベイズ・同じ率のシミュレーション |
| [F62 死亡率は10年で上がったのか、下がったのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F62_simpson_standardization) | 年齢調整（直接法・SMR）・Kitagawa 分解・シンプソンのパラドックス |
| [F63 「前年比」と「前月比」、景気の変わり目を早く見つけられるのはどちらか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F63_yoy_vs_mom) | 転換点の判定の比較（遅れ・空振り）・相互相関・シミュレーション |
| [F64 エンゲル係数の上昇は、本当に生活苦か？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F64_engel_decomposition) | 要因分解（相対価格・シフトシェア・エンゲル曲線のパネル） |
| [F65 医師が多い県ほど、平均寿命は長いのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F65_doctors_life_dag) | DAG と裏口基準で調整変数を選ぶ・256通りの仕様曲線 |
| [F66 統計の推計方法が変わると、数字はどれだけ動くのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F66_series_breaks) | 系列の段差の推定・接続の方法（平行移動・比率・三角修正）の比較 |
| [F67 気温が1℃上がると、電気の使用量は何%増えるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F67_temp_power_gam) | 一般化加法モデル（GAM）・スプライン回帰・時刻別の比較 |
| [F68 訪日客の「来る季節」は、国によっていくつの型に分かれるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F68_inbound_seasonality_clusters) | 時系列クラスタリング（k-means・DTW・k-shape）・安定性の検証 |
| [F69 統計表の「-」は0なのか、欠測なのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F69_data_quality) | データ品質の点検（記号・0・合計・桁ずれ・単位の自動チェック） |
| [F70 同じ数字でも、グラフの見せ方で印象はどこまで変わるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F70_chart_honesty) | lie factor による誇張の数値化・見かけの相関のシミュレーション |
| [F71 都道府県の所得の差は、縮まっているのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F71_income_convergence) | β・σ収束、動学パネル GMM（差分・system） |
| [F72 家計は物価が何%上がると思っているのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F72_inflation_expectations_cp) | Carlson–Parkin 法・最尤法・実績との比較 |
| [F73 街の人の「景気の声」は、数字より先に動くか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F73_watcher_text_tone) | テキストの感情スコア（辞書法・文の埋め込み）・DI との比較 |
| [F74 観測点のない場所の気温を、どこまで当てられるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F74_temperature_kriging) | クリギング・回帰クリギング・LightGBM の比較、空間ブロック CV |
| [F75 地価の地図を「なめらかに」描くと、どこまで当たるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F75_gp_land_price) | ガウス過程回帰・回帰クリギング・空間ブロック CV |
| [F76 所得が高い県は、ずっと高いままか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F76_income_mobility_markov) | 順位のマルコフ遷移行列・移動性の指標・定常分布 |
| [F77 今の人の流れが続くと、人口の分布は最後にどうなるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F77_migration_markov) | 人口移動のマルコフ連鎖・定常分布・収束の速さ |
| [F78 産業がばらけている町は、不景気に強いのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F78_industry_portfolio) | 多様性指数・バーティク・産業ポートフォリオのぶれ |
| [F79 会社の終わり方は「閉鎖」か「合併」か？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F79_closure_vs_merger) | 競合リスク（累積発生関数・Fine–Gray） |
| [F80 47都道府県×100指標の「有意な差」はいくつ偶然か？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F80_multiple_comparisons) | 多重比較（Bonferroni・Holm・FDR） |
| [F81 通勤で町の外へ出る人が多いほど、子どもは少ないのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F81_commute_gps) | 一般化傾向スコア（連続処置・用量反応曲線） |
| [F82 「年収の壁」の手前に、人はどれくらい集まっているのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F82_income_wall_bunching) | 集積（bunching）分析・反実仮想の分布 |
| [F83 日本の生産性の伸びは「産業の中」か「産業の入れ替わり」か？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F83_productivity_shift_share) | シフトシェア分解（産業の中・入れ替わり・交差項） |
| [F84 男女の賃金差のうち、「説明できる部分」はどれだけか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F84_oaxaca_gender_wage) | Oaxaca–Blinder 分解（集計データ版） |
| [F85 日本経済の「要」の産業はどれか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F85_io_network) | 産業連関ネットワーク（連関・中心性・ショックの伝わり方） |
| [F86 平均寿命はこの先どこまで延びるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F86_lee_carter_e0) | Lee–Carter 死亡率モデル・確率的な予測区間・バックテスト |
| [F87 結婚が減ったのは「時代」のせいか「世代」のせいか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F87_marriage_apc) | 年齢・時代・コホート（APC）分解と識別の問題 |
| [F88 携帯料金の値下げは、物価をどれだけ下げたか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F88_mobile_fee_rdit) | 時間の回帰不連続（RDiT）・寄与度・プラセボ |
| [F89 最低賃金の効果、これまでの推定をまとめると？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F89_minwage_meta) | メタ分析（固定効果・ランダム効果・フォレストプロット）・推定値の選び方の感度・検出力 |
| [F90 月次の統計で、四半期のGDPをどこまで当てられるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F90_midas_nowcast) | MIDAS 回帰・ブリッジ方程式・DFM との比較（疑似リアルタイムのナウキャスト） |
| [F91 機械学習の「何が効いているか」は、手法で答えが変わるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F91_interpretation_methods) | SHAP・並べ替え重要度・PDP・ALE の比較・相関する変数の落とし穴・人工データでの検証 |
| [F92 電力需要の「上振れ」はどこまで見込めばよいか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F92_power_quantile_forecast) | 分位点予測（分割コンフォーマル・分位点回帰・LightGBM の分位点損失）・カバー率の評価 |
| [F93 PDF の統計表を機械で読むと、どれくらい間違えるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F93_pdf_table_extraction) | PDF の表の抽出（13通り）の精度評価・検算の自動化・読み間違いの検出率 |
| [F94 市町村合併をどう扱うかで、20年の推移の分析は変わるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F94_municipal_merger_panel) | 新旧の市町村の対応表（廃置分合の記録からのレコードリンケージ）・按分・扱い方による結果の違い |
| [F95 新幹線の効果は、隣の県にもこぼれたのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F95_shinkansen_spillover) | 空間スピルオーバーの差の差（隣・隣の隣・距離帯）・Synthetic DID・プラセボ・F29 との比較 |
| [F96 e-Stat の数万の統計表から、欲しい表をすぐ探せるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F96_estat_semantic_search) | 表題の文埋め込み（ruri-v3）による意味検索・BM25 との比較・検索精度の評価（Hit@10・MRR） |
| [F97 「前年比+1%」は、本当に増えたと言えるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F97_sampling_error_yoy) | 公表された標準誤差率による前年比・前月差の判定・見つけられる最小の変化・標本の重なりの扱い |
| [F98 大きな災害のあと、宿泊客はどれくらいで戻るのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F98_disaster_lodging_recovery) | 複数の事例をそろえたイベントスタディ・プラセボの帯・回復の基準の比較 |
| [F99 作るものを変えると、カロリーの自給率はどこまで上がるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F99_food_self_sufficiency_lp) | 線形計画法・前提を変えたシナリオの比較・双対価格 |
| [F100 同じ問いを5つの手法で分析すると、答えはそろうのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F100_five_methods_one_question) | 回帰・固定効果・マッチング・DML・空間回帰の比較・仕様の曲線 |
| [F101 物価と賃金は、長い目で見ると一緒に動いているのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F101_price_wage_cointegration) | 共和分（Engle–Granger・Johansen）・誤差修正モデル |
| [F102 円安が物価に効くのは、円安が大きいときだけか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F102_fx_threshold_passthrough) | 閾値 VAR・一般化インパルス応答・状態で分けた局所射影 |
| [F103 電力需要や物価の「長い記憶」は、どれくらい続くか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F103_long_memory) | 長期記憶（ARFIMA・局所Whittle・DFA・ハースト指数） |
| [F104 気温と電力需要の関係を、ガウス過程の時系列で読むと？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F104_gp_power_temperature) | ガウス過程回帰（成分カーネル・予測区間のカバー率・気温シナリオ） |
| [F105 閉鎖を数年おきの調査でしか確かめられないと、生存曲線はどこまでずれるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F105_interval_censoring) | 区間打ち切りの生存分析（Turnbull 推定・区間尤度のパラメトリック・比例ハザード） |
| [F106 同じ県の会社は、同じように閉鎖しやすいのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F106_shared_frailty) | 共有フレイルつきの生存分析（ガンマ・対数正規フレイル、経験ベイズ、シミュレーション） |
| [F107 市区町村のつながり（隣接・通勤）を使うと、予測は良くなるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F107_gcn_municipal) | グラフニューラルネットワーク（GCN・GraphSAGE 型）と LightGBM＋隣の平均、ランダムと都道府県ブロックの検証 |
| [F108 予測モデルは、地域によって外れ方が偏っていないか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F108_prediction_fairness) | 予測の公平性（グループ別の誤差・偏り・区間のカバー率、Mondrian コンフォーマル、偏りの補正の比較） |
| [F109 どのデータを集めれば、予測は早く良くなるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F109_active_learning_land_price) | 能動学習（不確実性サンプリング・k-means の多様性・組み合わせとランダムの比較、シミュレーション） |
| [F110 予測モデルの設定は、どう選ぶのが効率的か？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F110_hyperparam_bayesopt) | ハイパーパラメータ探索の比較（グリッド・ランダム・TPE・ガウス過程のベイズ最適化、検証とテストのずれ、作り直しによる確認） |
| [F111 人口が減る町で、店はいつ消えるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F111_shop_abm) | エージェントベースのモデル（住民と店のシミュレーション、実データとの照合、2050年への投影と前提の確認） |
| [F112 救急隊が全部出払う確率は、隊を1つ増やすとどれだけ下がるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F112_ambulance_queueing) | 待ち行列（M/M/c・Erlang C の時間変動つき近似と M/G/c シミュレーション、公表されていない仮定を変えた幅） |
| [F113 物価指数の作り方で、インフレ率はどれだけ変わるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F113_price_index_formulas) | 指数の式の比較（ラスパイレス・パーシェ・フィッシャーなど8つの式、固定基準と連鎖、代替バイアスのブートストラップ） |
| [F114 東京の1万円と地方の1万円は、同じ価値か？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F114_regional_purchasing_power) | 地域の購買力（所得を消費者物価地域差指数で割る、世帯の型の重み、住居の重みの掃引） |
| [F115 統計の公表値から、元のばらつきをどこまで復元できるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F115_grouped_income_distribution) | 階級別の度数からの分布の推定（区間の最尤推定・単調スプライン＋パレート、公表値との答え合わせ、階級の粗さとシミュレーション） |
| [F116 47都道府県の指標を1つの「暮らしやすさ」にまとめると、重みでどれだけ順位が変わるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F116_composite_index_weights) | 合成指標の感度分析（正規化・重み・集計の比較、主成分の重み、データ包絡、ディリクレ分布の重みで順位の幅） |
| [F117 調査の回答率が下がると、結果はどれだけずれるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F117_nonresponse_weighting) | 非回答の補正（事後層化・レーキング、国勢調査との比較、答えの分かる世帯でのシミュレーション） |
| [F118 「保育所と出生率」に、これまでの記事はどう答えたか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F118_childcare_fertility_synthesis) | 推定のまとめ直し（6本の記事の23の推定を共通の単位に換算、都道府県パネルの再推定、比べ方ごとの整理） |
| [F119 予測した記事は、その後どれだけ当たったか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F119_forecast_scorecard) | 予測の答え合わせ（F22・F92 の電力を記事のあとの10月で、F55 の出生数を2026年1〜5月の概数で、F86 の平均寿命を2025年の簡易生命表で確かめ、未公表の予測を一覧に） |
| [F120 2025年国勢調査で、記事の結論は変わったか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F120_census2025_update) | 公表済み集計による記事の更新（旧市町村別の2025年人口で F94 の按分を答え合わせ、F14 の比較を2025年まで延長、F87 の未婚割合を原数値と不詳補完値で比較） |
| [F121 「最低賃金と雇用」に、4本の記事はどう答えたか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F121_minwage_methods_review) | 手法のまとめ直し（差の差・県境のペア比較・因果フォレスト・メタ分析の17の推定を共通の単位に換算し、使えた変動と検出力を比較） |
| [F122 手法ごとに、どこでつまずいたか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F122_pitfalls_from_logs) | 作業ログの集計（118本の「設計から変えたこと」と「言えないこと」をキーワード辞書で分類、手法の系統別の比較、数え方を変えた順位の相関） |
| [F123 「場所で分けて確かめる」と、記事の結論は変わったか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F123_spatial_block_cv_review) | 空間ブロック交差検証の見直し（地価・出生率・気温で4つのモデルをランダム・ブロック・都道府県ごと・緩衝帯で比較、これまでの記事の数字を横並び） |
| [F124 同じデータを何本の記事で使い回したか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F124_data_lineage_network) | データの系譜（118本の README を名寄せした記事×データの二部グラフ、記事→記事の使い回しの有向グラフ、F122 の分類との比較） |
| [F125 100本を超えた看板記事で、「見えなかった」はどれくらいあったか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F125_null_results_review) | 結論の振り返り（118本の結論を手作業で判定、記事の種類・手法の系統・データの単位別の割合、Fisher の正確検定、キーワード判定との一致） |
| [F126 暑い日の何日後まで、熱中症の搬送は増えるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F126_heatstroke_dlnm) | 分布ラグ非線形モデル（気温×遅れ0〜10日、熱中症搬送の日別・47都道府県 2015〜2025年） |
| [F127 空き家は、人口が減った分だけ増えたのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F127_vacant_houses_decomposition) | 要因分解（住宅ストック・人口・世帯の小型化、LMDI）と都道府県パネル回帰（住宅・土地統計調査 2003〜2023年） |
| [F128 家賃は、都心からの距離でどれだけ下がるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F128_rent_distance) | GAM と折れ線回帰（民営借家の家賃と都心・駅からの距離、住宅・土地統計調査 2018・2023年） |
| [F129 薬の処方量の地域差は、年齢構成でどこまで説明できるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F129_prescription_age_adjust) | 間接法の年齢調整とファンネルプロット（NDBオープンデータ 処方薬・人口推計、2023・2024年度） |
| [F130 介護の認定率の地域差は、高齢化だけで説明できるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F130_care_certification_shrinkage) | 年齢調整（間接法）とポアソン階層ベイズの縮小（介護保険事業状況報告 保険者別、1,573保険者、2020〜2024年度） |
| [F131 大学に進む人が増えると、地元に残る若者は減るのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F131_univ_youth_migration) | 固定効果パネルと対数による要因分解（学校基本調査 出身高校の所在地県別 大学入学者・住民基本台帳人口移動報告、47都道府県、2005〜2025年度） |
| [F132 農家は「やめる」のか「大きくなる」のか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F132_farm_size_transitions) | 規模の遷移行列（マルコフ連鎖）と2025年センサスでの予測検証、シフトシェア（農林業センサス 構造動態の相関表、2005〜2020年） |
| [F133 輸出先は、距離と経済規模でどこまで決まるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F133_export_gravity) | 重力モデルの PPML 推定（年・国の固定効果、品目別・年ごと。財務省 貿易統計〈UN Comtrade 経由〉・IMF WEO・世界銀行、194か国×2000〜2024年） |
| [F134 再生可能エネルギーの導入は、どこで速く進んだのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F134_renewable_diffusion) | 普及曲線（Bass・ロジスティック・ゴンペルツ）の当てはめと予測検証、地域差の順位相関（資源エネルギー庁 FIT・FIP 都道府県別導入量、2012〜2026年） |
| [F135 雨の日は、小売の売上をどれだけ動かすのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F135_rain_retail) | 天候ショックの回帰（前年同月差、Newey–West）と業態・品目・曜日の比較、月の固定効果つき地域パネル（商業動態統計×気象庁 日別値、2014〜2026年） |
| [F136 鉄道の利用は、コロナ前にどこまで戻ったのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F136_rail_covid_recovery) | 季節つき中断時系列（コロナ前の傾向と季節から反実仮想、回復率と95%予測区間、定期・定期外・業態・地方の比較。鉄道輸送統計調査 月次、2014〜2026年） |
| [F137 郵便物は、いつ半分になるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F137_postal_decay) | 減衰モデルと予測区間（指数・対数2次・ロジスティックを比べ、半分になる年度をブートストラップの90%区間とローリング予測で検証。日本郵便 引受物数、FY2003〜2025） |
| [F138 テレワークは、どの産業・地域に残ったのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F138_telework_decomposition) | 集計データの要因分解（対称型シフト・シェアで都道府県の差を産業構成と産業内に分け、分散の説明割合と東京圏への集中を比較。令和4年就業構造基本調査） |
| [F139 副業をしている人は、どんな働き方の人か？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F139_side_job_loglinear) | 集計表のログリニアモデル（男女×年齢×雇用形態×所得×副業の有無、逸脱度の比較と調整オッズ比、2017→2022のシフトシェア分解。就業構造基本調査） |
| [F140 外国人の住民は、どの地域に、どの速さで増えたのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F140_foreign_residents_concentration) | 空間的な集中度と増え方の分解（日本人との非類似度指数・ジニ・Theilの都道府県間／内の分解・立地係数、人口動態による増減の分解、国籍・地域の構成だけを変えた反実仮想。住民基本台帳・在留外国人統計） |
| [F141 特許の出願は、どの分野で地方に広がったのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F141_ip_regional_concentration) | 集中度の指標と時系列（東京・三大都市圏以外の割合、HHI、ジニ係数の傾き、特化係数、権利の構成によるシフトシェア分解。特許行政年次報告書の都道府県別の表） |
| [F142 森林は、「切れる木」がどれだけ増えたのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F142_forest_age_harvest) | 齢級のコホート推移と伐採量の比較（人工林の齢級別の面積・蓄積の推移、5年後の残り方、蓄積の増えのうち伐った割合、見通し。森林資源の現況・木材統計） |
| [F143 漁獲量の減り方は、魚の種類でどう違うのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F143_fish_catch_decline) | 時系列クラスタリングと変化点（42魚種・65年の漁獲量の形を k-means で4つの型に分け、log 漁獲量の区分線形で変化点を BIC で推定、型別の減少の分解、漁業種類でも確認） |
| [F144 水道料金の差は、人口密度と水源でどこまで説明できるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F144_water_tariff_density) | 費用関数の回帰と R² の分解（料金を給水人口・管路1kmあたり給水人口・水源で回帰し Shapley 値で分解、県の固定効果、勾配ブースティングの交差検証、給水原価の規模の経済と密度の経済。地方公営企業年鑑の事業別の個表） |
| [F145 ごみの量は、有料化のあとに減ったのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F145_waste_fee_did) | 段階的な差の差（Callaway–Sant'Anna 型）、イベントスタディ、ブートストラップ |
| [F146 統計の秘匿をノイズで置き換えると、分析の答えはどれだけ変わるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F146_dp_noise_vs_suppression) | 差分プライバシー（ラプラス機構でε=0.01〜10のノイズを市区町村の集計表に入れ、率の誤差・順位・上位50・ファンネルの外れ・回帰の係数の変わり方を比較。小さい値を伏せる一次秘匿、県単位への直接ノイズとも比較。F19/F20/F27/F61 の表） |
| [F147 集計表から「それらしい個票」を作ると、元の分析を再現できるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F147_synthetic_from_tables) | 合成データ（就業構造基本調査の6変数の表を本当の表とみなし、1〜3変数の周辺表だけから IPF・ベイズネットワーク〈Chow–Liu・BIC〉など7通りで合成。全変動距離と、F139 の分析〈オッズ比・逸脱度の割合・交互作用〉の再現を、本当の表からの引き直しと比較） |
| [F148 会社は「休眠」をはさんでどう移り変わるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F148_dormancy_multistate) | 多状態の生存モデル（法人番号の全件データ585万法人を「活動・清算の結了など・合併・登記官による閉鎖」と閉鎖からの「復活」に分け、Aalen–Johansen 推定。2015年10月にあった法人の登記がなくなった道の30%は登記官による閉鎖で、その88%は毎年1月。復活は閉鎖100件に約1.2件） |
| [F149 生存分析を機械学習でやると、何が良くなるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F149_ml_survival) | ランダムサバイバルフォレスト・勾配ブースティングと Cox の比較（法人番号の10万社で閉鎖までの時間を予測。Uno の C は Cox 0.593・GBM 0.591〜0.592・RSF 0.586 でほぼ同じ。半合成データでは曲がり・交互作用があれば GBM が差の3分の2を取り戻すので、足りないのは手法ではなく特徴量） |
| [F150 季節のパターンそのものは、年々変わっているのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F150_dynamic_seasonality) | 動的調和回帰（出生数・訪日外客数・電力需要の月次系列に、係数がランダムウォークで動く季節〈6つの調和項〉の状態空間モデルを当て、固定の季節と尤度比で比較。出生は1〜3月が低く夏が高い形が強まり振れ幅8.7→13.4ポイント、電力の夏の山の高まりは気温でほぼ説明でき、訪日の7・8月の山は入国制限のあとに消え、国・地域の構成ではなく各国・地域の形の変化。予測の形の外れ方はわずかに改善） |
| [F151 47都道府県の求人倍率の「同じ動き」は、いくつに分けられるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F151_pref_hierarchical_dfm) | 階層型の動的因子モデル（一般職業紹介状況の都道府県別の月次〈1990〜2026年〉を全国＋7地方の因子に分解。月々の動きは全国53%・地方6%・県だけ37%〈中央値〉、全国の動きを除くと近い県ほど一緒に動くが、クラスタリングではっきりしたまとまりは出なかった） |
| [F152 統計の速報は、確報でどれだけ直されるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F152_revision_news_noise) | 改定の分析（GDP 速報の需要項目と毎月勤労統計の速報・確報を Mankiw–Shapiro の方法でニュース型・ノイズ型に分ける。GDP の1年後の改定はニュース型で、設備投資・公共投資・政府消費は改定が確定値の動きの7〜9割。毎勤の所定内給与の前年比は確報で平均−0.16ポイント） |
| [F153 平均でなく「分布」で比べると、地域の差は何に見えるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F153_distribution_regional) | 分布の比較（住宅・土地統計調査の世帯の年間収入の分布を47都道府県で分位関数にし、2-Wasserstein 距離を位置・広がり・形に分解。差の66%は位置・30%は広がり・形は3%〈対数では位置93%〉で、各県はほぼ「全国の k 倍」。世帯人員×持ち家・借家の構成をそろえても差は縮まらず、分布のクラスタは条件で入れ替わる） |
| [F154 推定の「不確かさ」は、図の形で何が読み取れるかが変わるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F154_uncertainty_viz) | 不確実性の可視化（出生数・平均寿命・電力の予測を点・95%区間・ファン図・ドット・HOP で描き分け、確率の読みのずれを計算。ファン図とドットは1ポイント前後、点だけは約20ポイント。年ごとの区間からは2つの年の比較を読み違える） |
| [F155 分析の手順を変えると、答えはどこまで変わるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F155_multiverse) | マルチバース分析（最低賃金と就業率〈F01〉・保育所と出生率〈F100〉の問いで、分析の選択肢の全組み合わせ288通り・528通りを推定。最低賃金では就業率が有意に下がった指定は0、保育所と出生率は県ダミーを入れるかの1つで向きが逆に。シャープレイ値によるばらつきの分解、並べ替え・効果0を課したブートストラップによる joint inference） |
| [F156 最低賃金の効果は、地域の「賃金の低さ」で違うのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F156_minwage_bite_heterogeneity) | 効き方の異質性（短時間労働者の時給を47都道府県×17年分集め直し、全国の引き上げ×賃金の低さの交互作用と、同じ年の中の上げ幅だけを使う因果フォレストを比較。最低賃金の低い県ほど時給に届いた〈2012〜19年〉が、雇用の差は地方×年の効果と年の並べ替えプラセボで消える） |
| [F157 電力需要の予測を、1年通して運用したらどうなるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F157_power_forecast_operation) | 予測の運用の再現（東京の翌日24時間の需要予測を365日くり返し、再学習を固定・四半期・毎月・毎週・誤差の監視ルールで比較。毎週でも MAPE 2.27%→2.23% とほぼ変わらず、2年前のモデルのままだと +0.37ポイント、データの短い関西では毎週の再学習で −0.25。ピーク上限の幅を直近90日で更新） |
| [F158 地価の予測モデルは、毎年作り直す必要があるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F158_land_price_update) | 年ごとの再学習と更新間隔の比較（地価公示2017〜2026年。2017年のモデルのままでは誤差が年0.8ポイントずつ広がり、2年ごとの更新で毎年とほぼ同じ。重要度の顔ぶれは変わらず、効き方が強まった） |
| [F159 出生数の予測を、毎月の速報で更新すると当たり方は変わるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F159_births_nowcast) | ナウキャスト（速報236回・概数184回を公表日どおりに並べて2012〜25年を再現。速報が1〜3か月分のうちは年初の予測より外れが大きく、11月には1.5%から0.5%まで縮む。外国人の出生を含む速報は同じ年の概数で直す必要があった） |
| [F160 人口の将来推計を、自分で作るとどこまで合うか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F160_cohort_projection_backtest) | コーホート要因法の答え合わせ（1,681市区町村で自作の仮定を変えて2015・2020・2025年の国勢調査と比べると、5年先の外れは社人研1.7〜1.8%・自作1.8〜2.4%。外れる場所はほぼ同じで、自作の外れの8割は移動率の仮定から来ていた） |
| [F161 同じデータで記事を書き直すと、結論はどれだけ変わるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F161_rewrite_old_articles) | 初期3本の作り直し（回帰・クラスタリング・時系列予測を今の手順でやり直すと、9つの点のうち変わったのは3つ。組み合わせ512通り・復元抽出・比べる相手の追加と差の検定が結論を動かした） |
| [F162 公的データは「API で取れる」のか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F162_data_access_map) | 取得経路の集計（377記事の README と取得コードから、新しく取った428組の取り方を分類すると、ファイル67%・API 2%（日銀など9組）・記録なし25%。e-Stat 経由ほどファイルで取れ、後の記事ほど PDF・画面からが増えた） |
| [F163 125本の看板記事で、いちばん効いた頑健性チェックは何だったか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F163_robustness_checks_review) | 頑健性チェックの効き目の集計（F01〜F125 の README を手作業で判定すると、結論が変わったのは113本中23本〈20%〉。いちばん多く使った「対象を絞る・除く」が結論を動かしたのは9%で、変数・モデル・期間を変えるチェック〈18〜20%〉の半分。上位の順は数え方で入れ替わった） |
| [F164 図をどう作ると、読まれ方が変わったか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F164_figures_and_reads) | 自分の note の公開数字の振り返り（公開済み34本のスキ・コメントと図の枚数・字数・タイトルの字数を、正確な区間・日数をオフセットにしたポアソン回帰で記述すると、図5枚以上の差は日数の扱いで4.6倍〜2.3倍と揺れ、図の枚数はタイトルの長さと重なっていて分けられなかった） |
| [F165 データ分析の「再現できる形」は、どこまで作れたか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F165_reproducibility_audit) | 記事フォルダの再現性の監査（379本のコードと requirements.txt の棚卸しと、無作為に選んだ40本を新しい仮想環境で最初から動かし直して results/ と照合すると、数字が一致したのは33本。通常記事は20本すべて再現したが、看板記事でそのまま再現したのは20本中9本で、ずれた7本のうち3本は書いたときの環境なら一致した） |
| [F166 公的統計の数字は、ベンフォードの法則に従っているか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F166_benford_public_stats) | ベンフォードの法則（市区町村の10系列は第1桁で「おおむね合う」以上、第2桁はすべて「よく合う」。約1,700件では本当にベンフォードに従う数でも先頭2桁は「ぎりぎり」と判定され、単位を換えるだけで判定が入れ替わる系列もあった） |
| [F167 「100年に1度の大雨」は、本当に100年に1度なのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F167_return_period_heavy_rain) | 極値理論・GEV と再現期間（気象庁28地点の年最大日降水量で、1901〜60年で決めた100年値を1961〜2025年が超えたのは1,620地点年で18回〈単純な期待値16.2回、推定の揺れを含む期待値23.7回〉。100年値の95%区間の幅は値の47%、ふだんの年の最大は+13%、1991年以降に限ると1.6倍。GPD・ブロックの長さ・検出力も確認） |
| [F168 猛暑日の数は、どこまで増えたと言えるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F168_extreme_heat_trend) | 非定常の極値分布（気象庁30地点の125年で、年最高気温は30地点すべてで上昇〈中央値+1.7℃／100年〉、38℃以上の年は6.4倍。都市の影響と見分けられるのは約0.5℃） |
| [F169 円安と株高は、大きく動く日にだけ一緒に動くのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F169_yen_stock_copula) | コピュラと裾の依存（1998〜2026年の7,062日で、上下2.5%どうしがそろう割合は円安×株高0.16・円高×株安0.25とガウスの0.10を上回るが、はっきり出たのは2007〜2012年。「大きく動いた日だけの相関」は選び方だけで高く出る） |
| [F170 産業の構成比を比べるとき、割合のまま回帰してよいか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F170_compositional_industry_shares) | 組成データ・ilr（製造業の割合の係数は基準の産業しだいで−1.4%〜+7.9%と符号まで変わるが、ilr では+1.5%の1つに決まる。割合にするだけで負の相関が生まれる） |
| [F171 人口ピラミッドの「形」は、いくつの型に分かれるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F171_pyramid_shape_fda) | 関数主成分とクラスタリング（1,740市区町村の各歳人口の曲線で、形の違いの69%は平均年齢とほぼ同じ1本の軸〈相関0.99〉。はっきり分かれるのは2つまで〈シルエット0.39〉、安定して分けられるのは3つまでで、境目は手法や対象を変えると大きく動く） |
| [F172 生まれる日・亡くなる日は、曜日と季節でどう偏るか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F172_birth_death_calendar) | 円周統計と曜日効果（2018〜2025年の出生629万人で、日曜は平日より41%少なく〈病院55%・助産所98%〉、差の8割は9時台〜16時台。季節の集中度 R は曜日の6分の1ほどで、出生の季節は1950年代の1〜2月集中からほぼ消え、死亡は今も冬に集中） |
| [F173 2つの年の所得分布は、どれだけ「動いた」のか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F173_income_distribution_wasserstein) | 最適輸送（Wasserstein 距離）と分位点の差（国民生活基礎調査の39年分の所得分布で、1994→2024 の距離は2024年の価格で178.8万円とほぼ全部が下向き。どの順位も下がったので距離は平均の差と同じで、平均を超える情報を足したのは平均がほとんど動かない年の組だけ） |
| [F174 景気の「局面」は、データから自動で見つけられるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F174_business_cycle_hmm_multiseries) | 多変量の隠れマルコフモデル（一致系列7本を並べたまま、1975年以降の後退9回のうち8回を見つけ一致率73.7%。BIC は3状態を選んだが公式に最も合うのは4状態、初期値を変えた当てはまりのほぼ同じ解では61〜62%、CI1本〈84.3%〉に届かず） |
| [F175 予測モデルの精度は、どの特徴量の「おかげ」なのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F175_r2_shapley_decomposition) | R² の Shapley 分解（128通りの学び直し・SAGE・線形 LMG・\|SHAP\| の比較。地価の乗降客数は SAGE 66%・学び直し21%） |
| [F176 白書の文章は、年々読みやすくなったのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F176_whitepaper_readability) | 文章の読みやすさの指標の時系列（3つの白書の約39万文で、1文の字数・漢字とカタカナの割合・語種・jReadability。経済白書の1文は1960〜80年代に69字まで短くなったが2020年代は80字、漢字の割合はほぼ横ばいで増えたのはカタカナと外来語。情報通信白書は文が長くなったのに総合指標では「やさしく」なり、指標で向きが逆になった） |
| [F177 「差がある」は、並べ替えで確かめるとどうなるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F177_permutation_tests) | 置換検定・ランダム化推論と t 検定の比較（過去の記事の小さな比較3つで、検定を換えても p はほぼ同じ〈都市と都市以外の気温の上がり方 Welch 0.049・並べ替え 0.0498〉だが、並べ替えの単位を換えると東西100指標の p<0.05 は19→4、豪雨のあとの宿泊の差は p=0.034→0.18。人工データでは外れ値に強く、ばらつきの違いには弱い） |
| [F178 回帰の外れ値は、どの点がどれだけ結論を動かしているか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F178_regression_influence) | 影響度の診断（Cook の距離・DFBETA・1県ずつ／2県ずつ除く）と頑健回帰・HC3・ブートストラップの比較（物価と所得の傾きは東京1点で0.067→0.042、医師と女性の寿命は東京を除くと p=0.027→0.48。83指標3,403組では p<0.05 の13%が1県を除くだけで入れ替わり、正規分布の乱数より裾の重い分布に近い） |
| [F179 欠測を埋める方法で、答えはどれだけ変わるか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F179_imputation_by_estimand) | 多重代入（連鎖方程式・PMM）と単一代入・完全ケースの比較（3項目を30%欠かした1,740市区町村で、1つの値で埋めると割合は8.7%→6%に縮み、人口が小さい町ほど欠けると多重代入でも係数の符号が逆に。人口で分けて埋めると区間の当たり31%→87%） |
| [F180 2つの統計の数字は、本当に同じものを測っているか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F180_measurement_agreement) | 測定の一致度（Bland–Altman 法・一致相関 CCC）と系統的なずれ（国勢調査と住民基本台帳・労働力調査の8組。人口は相関1.00 でも住基が0.9〜1.2%多く、世帯数は全47県で7%多い。失業率は相関0.75 でも CCC0.13 で労働力調査が全47県で1.4ポイント低く、就業率は「不詳」の扱いでずれが6倍に） |
| [F181 家が建つ数は、金利と人口のどちらで決まるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F181_housing_starts_rates_population) | 時系列の回帰・VAR の分散分解・都道府県パネル（新設住宅着工60年分。年ごとの増減の取り分は金利15%・人口2%、VAR の5年先は金利2割強・人口6%。ピークから58%減のうち25〜44歳人口の減少で説明できるのは3割弱で、1996〜2009年は人口が増えても着工は半減） |
| [F182 中古住宅は、新築の何年分の価格差で売られているか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F182_condo_depreciation_curve) | 築年数の減価曲線（1年ごとのダミーのヘドニック回帰、市区町村×四半期の固定効果、全国の中古マンション54.7万件）と地域・期間・構造の比較（築0→3年で15%下がり、その後の年2.7%の6.2年分。築1年の半分は築23.5年で、東京23区30年〜地方19年） |
| [F183 車を持つ世帯は、どこで減りはじめたのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F183_car_ownership_change_points) | 普及率の変化点（最も高かった年・折れ線回帰）と台数・世帯数への分解、人口密度・鉄道・高齢化との順位相関（世帯当たり台数は全国で2006年が最高だが台数は2026年も過去最多。減りはじめは大都市圏の2007年以前と地方の2017〜19年、人口当たりでは45県で増加） |
| [F184 空の便は、新幹線の開業でどれだけ減ったのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F184_air_shinkansen_did) | 路線別の差の差と並べ替え推論（航空輸送統計の214路線。新幹線の開業区間の7路線は対照より平均−40%、鉄道が速いほど大きく減る） |
| [F185 宅配便の個数は、どこまで通販で説明できるのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F185_parcels_online_shopping) | 時系列の回帰（水準と前年度比）・変数の組み合わせ・前半で推定して後半を当てる予測（宅配便21年度分と家計のネット通販支出。2004〜24年度で宅配便 +63%・ネット支出13倍、水準の R² 0.96 はトレンドだけでも0.94、前年度比の R² は0.04 で効いたのはコロナの2020年度） |
| [F187 子どもの身長の伸びは、いつ止まったのか？](https://github.com/takayuki-0127/japan-open-data-notes/tree/main/articles/F187_height_plateau_changepoint) | 長期系列の変化点（折れ線・平均の変化点・最高値に届いた年）と生まれ年での比較（学校保健統計の5〜17歳の平均身長26系列。伸びが鈍ったのは1970年代、止まったのは17歳男子1991年ごろ・女子1986年ごろ、11〜13歳は1995〜98年まで伸びた） |

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
