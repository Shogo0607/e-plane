# Electric Aircraft Research Summary

最終確認日: 2026-04-26

## 調査方針

1. 作業開始時に `/Volumes/ex/study/e-plane` の構成を確認した。既存資料は `MOC.md` と `research/README.md` のみで、過去の地域別調査はなかったため、初回ベースラインとして北米、欧州、中国、日本を同じ構造で整理した。
2. その後、地域別ノートへ移行し、既存内容を上書きせず、各地域の `最新動向`、`規制動向`、`技術動向` の表へ差分を追記する形式に整理した。
3. web_search を実施し、FAA、EASA、CAAC、MLIT/JCAB、メーカー公式発表を優先した。

## 主要な発見

| 調査日 | 地域 | 最新動向 | 規制動向 | 技術動向 | 総合評価 |
| --- | --- | --- | --- | --- | --- |
| 2026-04-26 | 北米 | Joby は FAA 型式証明 Stage 4 の初期、Archer は MoC 100% acceptance、BETA は ALIA CTOL の商用導入準備。 | FAA は powered-lift 運航規則と AAM 統合方針を整備。MOSAIC は LSA に電動モーターを含む余地を拡大。 | eVTOL は TIA/transition/for-credit testing へ、eCTOL は既存空港活用で先行可能性。 | 認証と初期運航の「最後の実証」段階に近いが、TC 発行は未確定。 |
| 2026-04-26 | 欧州 | EASA IAM Hub と AMC/GM が進展。Vertical は VX4 wingborne 試験を進め、hybrid-electric variant も示す。 | Regulation (EU) 2024/1111 向け AMC/GM、SC-VTOL、SC E-19 MoC が主要論点。 | wingborne/transition、電動・ハイブリッド推進、騒音・ATM 統合が焦点。 | 制度整備は緻密だが、商用機体認証はまだ未完。 |
| 2026-04-26 | 中国 | CAAC 統計で低空経済基盤が急拡大。EHang EH216-S は OC、AutoFlight CarryAll は TC/PC を取得済み。 | 改正民用航空法が 2026-07-01 施行予定。無人航空機の設計・製造・整備・飛行活動の耐空証明義務を強化。 | EH216-S は商用有人無操縦 eVTOL 運航へ、V2000CG は 2トン級 cargo eVTOL 量産へ。 | 認証実績と政策推進は最も先行。ただし一般旅客・貨物の持続的商用実績は継続確認が必要。 |
| 2026-04-26 | 日本 | SkyDrive が JCAB と General Certification Plan 合意、ADO 認定取得。 | 試験飛行ガイドライン、特別要件、無人航空機認証手続き改正が進む。 | SD-05 の構造、システム、電動モーター、騒音の個別計画が審査中。 | SkyDrive の型式証明体制が前進。2028 年実装目標に向けた試験・個別 CP が焦点。 |
| 2026-04-26 | 北米 | FAA が eIPP を 2026-03 に具体化し、8 パートナーを選定。Joby は FAA-conforming TIA aircraft の power-on testing、Archer は MoC 100% acceptance 後の TIA 準備。 | eIPP は認証迂回ではなく、formal type certification 中の機体を使い政策・標準へデータを戻す制度。 | TIA、piloted transition、for-credit testing が焦点。eVTOL 実運航は認証試験消化と初期運航許可がボトルネック。 | 制度実証の入口が明確化。TC 発行前の最終試験段階を追跡する局面。 |
| 2026-04-26 | 欧州 | EASA が 2026 年に CS-MCSD と Part-M/145/66 等 AMC/GM を更新し、new air mobility の整備士訓練・継続耐空性を補強。 | SC-VTOL に加え、開発飛行条件 CM と SC E-19 MoC の最終化が進行中。 | 電動・ハイブリッド推進は型式証明だけでなく、整備士訓練、OSD、継続耐空性が実装論点に移っている。 | 商用導入に必要な後方制度が厚くなった。個別機体の TC 進捗はなお未完。 |
| 2026-04-26 | 中国 | CAAC が 2026-04 に UAS 実名登録・激活、標準シナリオ、正常類 powered-lift UAS 耐空標準を相次ぎ整理。 | 2026-05-01 施行の強制標準と AC-21-AA-2026-47 が低空経済の運航・耐空管理を具体化。 | 不載人 powered-lift UAS と載人 pilotless eVTOL は分けて見る必要があるが、貨物 eVTOL には直接影響し得る。 | 政策・標準化の速度が速い。一般旅客 eVTOL の実績とは別に、UAS/貨物制度が先に固まる。 |
| 2026-04-26 | 日本 | SkyDrive は東京で SD-05 デモ飛行を完了し、ADO 認定と GCP 合意で認証体制を進めた。 | MLIT は No.8-002 改正、試験飛行ガイドライン、バーティポート検討で機体・運航・地上インフラを並行整備。 | 東京デモは運用評価として重要だが、型式証明の適合性証明とは別。個別 CP と試験データが次の焦点。 | SkyDrive 中心に国内実証と認証準備が接続し始めたが、2028 年商用化には複数の制度・試験課題が残る。 |

## 注目すべき規制変化

- 米国: FAA powered-lift final rule と air carrier definition 更新により、商用 powered-lift 運航の制度枠が見えている。MOSAIC は 2026-07-24 に LSA certification 関連規則が有効化予定。
- 米国: eIPP は 8 パートナーを選定し、air taxi、長距離固定翼、貨物、医療・緊急輸送、automation safety の初期運航実証を政策形成に使う枠組みになった。
- 欧州: EASA が 2025-07 に IAM の AMC/GM を追加し、Air OPS、FCL、SERA に manned VTOL-capable aircraft 対応を入れた。
- 欧州: EASA ED Decision 2026/001/R と 2026/002/R により、電動・ハイブリッド推進機の整備士訓練、Part-145/Part-66 等の継続耐空性ルールが具体化した。
- 中国: 改正民用航空法が 2026-07-01 に施行予定。民用無人航空機の耐空証明義務化が低空経済の制度基盤になる。
- 中国: CAAC の実名登録・激活強制標準が 2026-05-01 から新規生産 UAS に適用され、AC-21-AA-2026-47 が不載人 powered-lift UAS の耐空標準を明確化した。
- 日本: SkyDrive の ADO 認定と General Certification Plan 合意により、JCAB 型式証明プロセスが具体化。MLIT は空飛ぶクルマ特別要件と試験飛行手続を整備。
- 日本: MLIT の無人航空機型式認証手続き改正と試験飛行ガイドライン更新要素、バーティポート検討が、空飛ぶクルマ実装の周辺制度として重要。

## 次回追跡すべき論点

- FAA eIPP の各パートナー別プロジェクト、対象機体、運航開始日、搭乗者範囲。
- Joby/Archer の TIA、FAA pilot for-credit testing、piloted transition の公式完了情報。
- BETA ALIA CTOL の FAA 型式証明状況、Hawaii デモ飛行の実施結果。
- EASA SC-VTOL-02/MOC、SC E-19 MoC の最終化と欧州メーカーへの適用。
- EASA SC E-19 の Safety Assessment、Overspeed and Containment の final publication。
- 中国の改正民用航空法実施細則、EH216-S の一般向け有償運航、VT35 の認証進捗。
- CAAC AC-21-AA-2026-47 の貨物 eVTOL 型式審査への適用事例。
- SkyDrive の個別 Certification Plans 承認、ADO 認定範囲の公的照合、東京デモ後の認証試験計画。

## ファイル構成

- `/Volumes/ex/study/e-plane/research/north-america/notes.md`
- `/Volumes/ex/study/e-plane/research/europe/notes.md`
- `/Volumes/ex/study/e-plane/research/china/notes.md`
- `/Volumes/ex/study/e-plane/research/japan/notes.md`
- `/Volumes/ex/study/e-plane/research/summary.md`
