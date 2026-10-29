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
