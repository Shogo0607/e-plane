# Electric Aircraft Research Summary

最終確認日: 2026-04-30

## 主要な発見
| 調査日 | 地域 | 論点 | 重要度 | 根拠URL | 残る不確実性 |
| --- | --- | --- | --- | --- | --- |
| 2026-04-28 | 中国 | AutoFlight（エアロモビリティ） | 中 | [AutoFlight 公式（英語）](https://www.autoflight.com/en/news/hefei/) / [AutoFlight 公式（中国語）](https://www.autoflight.com/zh/news/hefei-cooperation/) | 亜系統的な機体仕様、認証・試験スケジュール、量産計画の公開状況はまだ限定的。 |
| 2026-04-28 | 欧州 | Vertical Aerospace は Valo 向け battery pilot production line を稼働。VEC で認証機 7 機分の最終バッテリーを製造開始し、VEC2 開設で生産能力 3 倍化を目標に。 | 中 | [Vertical Aerospace](https://vertical-aerospace.com/wp-content/uploads/2026/03/20260318-Battery-Production-Line-Press-Release_v2-1.pdf) | VEC からの量産品質、VEC2 開業条件、認証機/商用機への供給移行、コスト競争力の検証が未確定。 |

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
| 2026-04-26 | 北米 | Joby は FAA-conforming TIA aircraft の飛行開始を示し、Wisk は Gen 6 autonomous eVTOL の初飛行、BETA は eIPP と CTOL 認証用機製造を進める。 | eIPP は個別機体と地上支援・インフラの実証枠になり、FAA TC と初期運航の接続点が増えた。 | conforming aircraft flight、autonomous eVTOL first flight、225 kWh CTOL certification-intent aircraft が焦点。 | 米国は Joby/Archer の認証競争に加え、BETA の eCTOL と Wisk の自律運航が別軸で前進。 |
| 2026-04-26 | 欧州 | Vertical は two-way piloted transition を完了し、Volocopter は Diamond 傘下で VoloXPro へ製品再編を示した。 | UK CAA/EASA 協調のもと、Vertical は 2028 年 TC 目標を維持。Volocopter は ultralight certification 計画に軸足を移す可能性。 | transition 実証は大きな技術リスク低減。一方、欧州勢は資金・事業再編と認証用機体生産が重要論点。 | Vertical は技術面で前進したが資金実行と CDR/認証用機体が次の関門。Volocopter は air taxi 主軸の再評価が必要。 |
| 2026-04-26 | 中国 | EHang は 2025 Q4 に 100 機納入、VT35 初期納入、EH216-S commercial operations 開始見込みを示し、AutoFlight は offshore cargo 実証を進めた。 | CAAC の無人・低空制度化と、EH216-S/CarryAll の個別認証実績が並走。 | pilotless eVTOL の fleet operation、2トン級 cargo eVTOL の海上物流、VT35 の長距離化が焦点。 | 中国は認証・納入数で先行。ただし一般旅客向け継続運航と運航制限の透明性が残る。 |
| 2026-04-26 | 北米 | Joby は Air Space Intelligence と eVTOL 高密度運航の空域統合実証を 2026 年後半に予定。 | FAA eIPP と BNATCS の文脈で、認証済み機体だけでなく運航管理・管制支援ソフトが商用化条件になりつつある。 | Flyways AI platform の 4D modeling、予測的 airspace coordination、live operational exercises が焦点。 | 機体認証の次のボトルネックとして NAS 統合と運航密度管理を追跡する必要。 |
| 2026-04-26 | 欧州 | Volocopter は Diamond 傘下で供給網再編を完了し、VoloXPro 2026 年末、VoloCity 2027 年 EASA certification 見込みを維持。 | VoloXPro は ultralight、VoloCity は EASA 都市旅客 eVTOL という二正面の認証路線。 | Bruchsal sandbox で realistic flight operations を模擬する計画。 | VoloCity の TC 進捗と軽量機路線への経営資源配分が主要な確認点。 |
| 2026-04-26 | 中国 | AutoFlight は Matrix 5トン級 eVTOL の full transition public demo を実施し、旅客型・貨物型を提示。 | CAAC 認証段階は未確認で、CarryAll の認証実績から大型機へ拡張する局面。 | MTOW 5,700 kg、純電動 250 km、hybrid-electric 1,500 km、cargo payload 1,500 kg が公称値。 | 中国 eVTOL は小型観光・貨物から大型都市間/重量物へ拡張するが、認証基準と事業採算が未確定。 |
| 2026-04-26 | 日本 | MLIT/METI がロードマップを改訂し、2027/2028 年から一部地域で商用運航開始、2030年代前半に遠隔操縦旅客輸送、2030年代後半に自動・自律運航の一部実現を示した。 | AAMコリドー、遠隔操縦、運航管理システム、離着陸場整備が機体認証と並ぶ制度整備対象。 | 通信・運航管理・地上インフラ・自律運航 readiness が中長期の技術論点。 | SkyDrive の TC だけでなく、国内交通管理と商用候補地域の具体化を追う必要。 |
| 2026-04-26 | 北米 | Wisk は eIPP を autonomous Gen 6 の早期商用化経路と位置付け、Texas/Houston を主要ローンチ市場に設定。 | eIPP は自律 air taxi、SkyGrid、州・都市提案を通じて FAA 政策形成にデータを戻す枠組みになる可能性。 | Gen 6 は 4席、120 knots、90 miles with reserves、自律運航 with human oversight、12 propeller configuration を公称。 | 自律旅客 eVTOL は機体性能よりも remote supervision、空域統合、規制受容が主要な不確実性。 |
| 2026-04-26 | 中国 | XPENG ARIDGE は Land Aircraft Carrier の 7,000 台超受注、広州工場試作生産、A868 hybrid-electric tiltrotor の flight verification を発表。 | 個人向け flying car と長距離 hybrid-electric 機は、CAAC の低空経済制度と地方観光ルート許可の接点を持つ。 | Land Aircraft Carrier は冗長性と単一スティック操作、A868 は 6席・500 km・360 km/h 目標が焦点。 | 量産能力は大きいが、TC/PC/AC、操縦者訓練、空域運用、実納入の透明性を確認する必要。 |
| 2026-04-26 | 日本 | SkyDrive は MASC と 2028 年 2機納入 LOI、大阪では 2035 年約100機運用ビジョンを確認。 | 国内 AAM は国ロードマップに加え、地域別の実装主体・離着陸場・観光/交通需要の具体化段階に入る。 | SD-05 の短航続・小型 multicopter 特性を、瀬戸内遊覧、大阪湾岸、PA/SA 接続など短距離用途へ当てる構図。 | LOI と構想は TC/運航許可の代替ではないため、firm order 化と地域インフラ整備が次の確認点。 |
| 2026-04-26 | 中国 | AutoFlight CarryAll は Wuhan Crossing the River Festival で大型 eVTOL 初の実水域 rescue standby operations として紹介され、XPENG は Auto China 2026 で Land Aircraft Carrier と ARIDGE 生産拠点を訴求。 | CAAC 認証済み大型貨物 eVTOL の用途が物流・海上輸送から emergency response へ広がる一方、XPENG は量産・市場認知を先行させている。 | CarryAll は救命筏投下、消火弾投下、緊急物資輸送を想定。Land Aircraft Carrier は展示・生産体制公開段階。 | AutoFlight は反復運用・契約・許可条件、XPENG は TC/PC/AC と実納入の透明性が次の確認点。 |
| 2026-04-26 | 北米 | Joby は FAA-conforming TIA aircraft N547JX の飛行開始と 10 州 eIPP early operations 機会を示し、Wisk は TxDOT eIPP で autonomous Gen 6 と SkyGrid Strata を使う段階的実証を掲げた。 | eIPP は piloted eVTOL だけでなく、自律 air taxi の Automated Flight Rules、remote supervisor、Ground Risk の制度化データを集める経路になりつつある。 | Joby は aircraft-level TIA 評価へ、Wisk は focused operations から dedicated routes、高頻度 Gen 6 operations へ進む設計。 | TC/TIA 完了、FAA pilot for-credit testing、eIPP OTA 契約、AFR 制度化と remote supervisor 資格が確認点。 |
| 2026-04-26 | 欧州 | EASA の SC-VTOL/SC E-19 関連資料から、都市上空の第三者リスクと electric/hybrid propulsion endurance/durability の証明枠がさらに具体的に確認できる。 | Category Enhanced は 10^-9 per flight hour と第三者被害を含む catastrophic 定義を重視し、SC E-19 MoC は propulsion system の calibration assurance を整備する。 | 電動・ハイブリッド推進では、認証済み turbine/piston/APU の credit 活用余地がある一方、battery/distribution は別 MoC の追跡が必要。 | SC-VTOL-02/MOC 最終版、SC E-19 Safety Assessment と battery/HV distribution 関連 MoC が次の確認点。 |
| 2026-04-26 | 中国 | EHang は EH216-S の 1,700 回超の OC 後運航、EHang Trip beta、ground operating crew training、VT35 の複数試験実施、Yunfu 年産 1,000 units 目標を開示。 | CAAC OC 取得後の商用化準備が、機体認証から運航者・地上操縦員・予約システム・量産体制へ広がっている。 | VT35 は wind tunnel、ground load、single-blade power failure、transition flights を進め、EH216-S の command-and-control と vertiport を活用する構図。 | 公開有償予約、A-to-B route trial、ground crew license、VT35 for-credit testing と TC 発行時期が確認点。 |
| 2026-04-26 | 日本 | SkyDrive/NEXCO 西日本の連携は、10-30 km 間隔の PA/SA を短距離観光・地域経済・災害対応の eVTOL 拠点候補として検討する内容に具体化。 | 国内 AAM は空港・専用 vertiport だけでなく、高速道路インフラを地上アクセスと非常時対応の結節点に使う構想が出てきた。 | SD-05 の短航続特性は、PA/SA 間の短距離遊覧や災害後の被害把握と相性があるが、離着陸場・消防・騒音・旅客導線が技術/制度論点になる。 | 具体的な候補 PA/SA、自治体協議、バーティポート基準適用、災害対応オペレーション設計が次の確認点。 |
| 2026-04-26 | 北米 | FAA/DOT の eIPP 選定発表本文で、2026 年夏までに初期運航が見え始める見込みと、PANYNJ 案件の Manhattan heliport passenger operations を含む operational concepts が確認できた。 | eIPP は選定先の公表から、個別空港・都市・ヘリポートを使う初期運航実証へ移る段階。 | 実機認証だけでなく、旅客導線、既存 heliport、地域 ATC、保険、住民受容性を含む運航設計が確認点になる。 | 夏の開始見込みは制度・契約・機体状態次第で変わるため、案件別の機体、運航者、搭乗者範囲を追跡する必要。 |
| 2026-04-26 | 中国 | 低空保険の実施意見により、低空経済の制度整備が耐空・登録・運航シナリオから責任保険へ広がった。 | 2027 年までに無人驾驶航空器责任保险の強制投保制度を初歩構築し、2030 年までに低空保険政策枠組みを基本形成する目標。 | 事故データ、運航リスク評価、保険料率、第三者責任が eVTOL/UAS の商用運航コストと許認可に影響し得る。 | 有人 pilotless eVTOL や大型貨物 eVTOL への適用範囲、CAAC 監督と金融監督の実務接続が不確実。 |
| 2026-04-26 | 北米 | FAA が Orlando と Los Angeles の HITL AAM operations reports を AAM ページの latest news に掲げ、空港周辺 eVTOL 初期運航の研究成果を公開。 | eIPP の選定と別に、既存空港・Class B 空域・ATC 手順に eVTOL をどう入れるかの検討が進んでいる。 | Orlando report は最大 26 eVTOL ops/hr のシナリオで route、vertiport、TCAS、go-around、wake turbulence を評価。 | 研究レポートであり運航承認ではない。LAX/MCO の詳細差分と標準化可能な手順を追跡する必要。 |
| 2026-04-26 | 日本 | MLIT 官民協議会資料で、JR East が駅・駅ビル vertiport、盛岡小岩井の宿泊施設起点モデル、広域品川圏モデルを提示。 | 国内 AAM は専用 vertiport や PA/SA だけでなく、鉄道・駅ビル・宿泊施設を地上ネットワークに組み込む構想が具体化。 | SkyDrive SD-05 の短距離特性を、鉄道接続、宿泊滞在型観光、都心臨海部周遊へ当てる方向。 | 構想段階であり、JR East の pre-order が firm order、実証、運航主体、離着陸場整備へ進むかが確認点。 |
| 2026-04-26 | 北米 | BETA は ALIA 導入に向け、Charge Cube の到達人口、ALIA pilot qualification、顧客 pilots/maintainers 訓練実績を示した。 | 認証前でも、充電・GSE・訓練が eCTOL/eVTOL 初期運航の導入条件として前面化している。 | BETA は 50 miles 圏 5,000 万人超、100 miles 圏 米国人口 30% 超という充電網到達性を訴求。 | 型式証明、運航証明、実際の charger 稼働率、充電規格の相互運用性は追跡が必要。 |
| 2026-04-26 | 欧州 | EASA の SC E-19 EHPS.420 MoC から、hybrid-electric propulsion endurance substantiation の技術的枠組みが確認できた。 | EASA は電動・ハイブリッド推進で、既存 CS-E/CS-APU/ED-321 等を使った証明方法を積み上げている。 | battery や distribution は当該 MoC の scope 外で、推進システムと電池/HV 系の認証論点が分かれる。 | SC E-19 Safety Assessment、battery/HV distribution、thermal runaway 関連 MoC の最終化が次の焦点。 |
| 2026-04-26 | 中国 | EHang は VT35 について RMB 6.5 million/機の purchase orders、Hefei hub、約 RMB 500 million 相当の地方支援を開示。 | pilotless eVTOL の商用化は、TC だけでなく地方政府支援、拠点形成、初期受注で推進されている。 | VT35 は EH216-S の認証・運航基盤を都市間機へ拡張する設計だが、TC 前の受注・納入の扱いに注意が必要。 | VT35 の TC、納入機の耐空状態、受注条件、commercial route approval を確認する必要。 |
| 2026-04-26 | 日本 | SkyDrive ADO の認定能力が Aircraft Design and Inspection、証明番号 No.313 と確認できた。 | ADO は政府検査の一部代替を通じて、JCAB 型式証明の実務速度に影響し得る。 | 設計・設計後検査の品質体制は前進したが、compliance testing と個別 CP 承認は別段階。 | ASIMS/MLIT 一覧照合、個別 CP 承認、TC 試験開始の公表を追跡する必要。 |
| 2026-04-26 | 中国 | AutoFlight CarryAll は Guizhou の Anshun-Guiyang 間で spring tea transport trial を実施し、約 120 km を 37 分で飛行後、高速鉄道で Shanghai へ接続する生鮮物流モデルを示した。 | 既に TC/PC/AC を得た大型無人貨物 eVTOL が、低空物流の実用途探索を進めている。 | 「eVTOL + high-speed rail」により、山岳部短距離航空支線と長距離鉄道幹線を組み合わせる設計が見える。 | 反復商用運航、運航許可、荷役・充電・気象制限、収益性を確認する必要。 |
| 2026-04-26 | 北米 | SkyDrive は Aeroauto と Florida 向け SD-05 8機 LOI、SAI Flight との Florida 展開拡張を発表。 | 米国南東部では eIPP 以外にも、販売網・運航支援・vertiport/charging/maintenance/pilot training を束ねる市場形成が進む。 | SD-05 の 2028 年 entry into service 目標は、FAA/JCAB 認証と米国地上インフラ整備の両方に依存する。 | LOI の firm order 化、Florida の運航者・離着陸場・充電/整備体制、FAA 認証パスを確認する必要。 |
| 2026-04-26 | 欧州 | Loganair、Royal Mail、BETA は Scotland で ALIA CTOL の 10日間・23 flights の electric flight demonstration program を完了。 | 欧州の地域航空脱炭素では、eVTOL air taxi よりも eCTOL 貨物・郵便用途が既存空港網で先に運用データを蓄積している。 | 平均 56-mile missions、99 knots、1.37 kWh/nm の実証値は、短距離郵便・貨物路線の電動化評価に使える。 | 型式証明、定期運航承認、冬季・満載・高稼働時の信頼性、充電設備と経済性を追跡する必要。 |
| 2026-04-26 | 日本 | SkyDrive は AeroGulf Services と Dubai 向け SD-05 20機の基本条件に合意し、2028/2029 年納入枠組みを示した。 | 国内認証と並行して、海外ヘリ運航会社・観光市場を初期顧客にする商用化経路が具体化している。 | Suzuki 生産、JCAB/FAA 認証、UAE 運航承認、観光 route design の接続が商用化条件になる。 | 基本合意の契約性、UAE 当局承認、AeroGulf の運航・整備体制、2028 年納入実現性を確認する必要。 |
| 2026-04-27 | 北米 | FAA Q1 2026 Small Airplane Issues List で、eVTOL、electric/hybrid propulsion、distributed propulsion、remote/autonomous systems、AI/ML software などが標準化・MOC 調整項目として確認できた。 | eIPP や powered-lift 規則とは別に、Part 23/eCTOL や非伝統的電動機での認証実務上の論点が明文化されている。 | energy/thrust management、battery state 表示、propulsion as flight control effector、Lightning/HIRF、cybersecurity、run-time assurance が設計審査の焦点。 | BETA ALIA CTOL や将来の自律・ハイブリッド派生機にどの項目が適用されるかは個別 certification plan/MOC issue paper 待ち。 |
| 2026-04-27 | 欧州 | Lilium の中核特許・登録知財が、insolvency proceedings を通じて Archer Aviation へ移転した。 | 欧州 eVTOL 勢の再編は、事業継続・TC 引継ぎではなく、知財の米国勢への移転として進んでいる。 | ducted fan、高電圧系、battery management、flight controls、electric engines などの技術資産は残るが、機体・量産・認証資産とは切り分ける必要。 | 残余資産、人材、設計データ、サプライヤー契約、Archer の実機への反映範囲を追跡する必要。 |
| 2026-04-27 | 中国 | EHang はタイ政府・CAAT と会合し、現地パートナーと MOU を締結。中国の Guangzhou/Hefei では EH216-S public ticketing と低空 sightseeing services を 2026 年 3 月に始める見込みと説明。 | 中国での OC 後運航経験が、タイの規制・標準作りと商用運航準備の参照事例として輸出されつつある。 | 旅客 eVTOL 輸出は機体販売だけでなく、vertiport、通信、digital traffic management、O&M、要員訓練を含む包括導入になる。 | 実際の中国公開チケット運航開始、タイの type certification/operator license、vertiport 承認、CAAC 認証の扱いを確認する必要。 |
| 2026-04-27 | 北米 | FAA Advanced Air Mobility Implementation Plan Version 1.0 を確認。Innovate28 の key site 初期運航に向け、認証・運航・空域・インフラ・地域説明を統合した作業計画が整理されている。 | AAM maturity levels は late-stage certification testing から fully autonomous/high-density network までを段階化し、Part 135、powered-lift pilot qualification、vertiport Part 77/157、環境レビューなどを接続する。 | 初期 vertiport には battery HazMat storage、battery fire suppression、充電容量、weather station など、機体性能以外の技術・地上設備条件が明示される。 | Version 1.0 の計画であり承認済み運航ではない。eIPP key sites、Integrated Master Schedule、地方 zoning、消防・電力要件の実装差分を追跡する必要。 |
| 2026-04-27 | 北米 | FAA AAM Infrastructure ページで、vertiport の法的定義、EB 105A の対象範囲、Part 157/ADIP 手続が確認できた。 | 初期 AAM は既存 airport/heliport 改修を使いつつ、新設 vertiport/vertistop は空港施設手続と NAS 影響評価の対象になる。 | pilot onboard、VMC、MTOW 12,500 lb 以下の eVTOL を前提にした設計ガイダンスであり、自律・IFR・高重量機は追加論点。 | eIPP 施設が EB 105A、Part 157、地方 zoning、消防・電力要件をどう通過するか確認する必要。 |
| 2026-04-27 | 欧州 | Vertical の Valo 公式仕様で、150 mph、100 mile、4 passengers + 1 pilot、8組 propellers、Molicel セル、Honeywell flight control が確認できた。 | SC-VTOL enhanced category を目標に、機体認証だけでなく cyber security、battery、整備性を商品設計上の論点として前面化している。 | simplified pitch control、cloud data insights、自社 battery technology は訴求点だが、認証用機体の evidence は未公開。 | CDR、認証用機体、battery cycle/thermal、cybersecurity evidence、整備間隔を追跡する必要。 |
| 2026-04-27 | 日本 | SkyDrive SD-05 の主要サプライヤーとして Avidyne、Electric Power Systems、Thales、Toray Carbon Magic、Cyient などが確認できた。 | ADO/GCP だけでなく、avionics、battery/BMS、flight control、CFRP、maintenance manuals、certification support が型式証明・整備体制の実装基盤になる。 | 外部サプライヤーと Suzuki 生産の組み合わせで量産・認証体制を作る構図が明確化した。 | 最終認証構成、各部品の certification credit、整備文書承認、保守部品供給を確認する必要。 |
| 2026-04-27 | 北米 | BETA は 2026-05-12 の Q1 決算発表予定を告知し、ALIA family の累計飛行距離 130,000 nautical miles 超、充電インフラ 100 sites 超を示した。 | eCTOL/eVTOL 導入では、機体認証と並行して充電網・aftermarket・GSE の拡張が事業基盤になっている。 | 既存記録の 125,000 nautical miles 超、50 超 charging sites から更新され、運用実績とインフラの伸びが確認できる。 | Q1 決算で certification-intent CTOL、FAA conformity inspection、certification flight testing、充電拠点の稼働内訳を確認する必要。 |
| 2026-04-27 | 北米 | FAA の Propulsion Systems 技術分野で electric/hybrid-electric propulsion systems と hydrogen-fueled aircraft が明示された。 | AAM 専用規則とは別に、電動・ハイブリッド推進は航空機認証横断の専門領域として政策・ガイダンス・国際連携の対象になっている。 | system safety、operational oversight、推進系寿命全体の信頼性が、BETA や将来の hybrid-electric/水素電動機で共通論点になる。 | 個別 special condition、battery/HV/fuel-cell/hydrogen storage の MoC、ZeroAvia/BETA 等への適用を追跡する必要。 |
| 2026-04-27 | 欧州 | EASA ED Decision 2026/003/R により、CS-23 Amendment 6 と AMC & GM to CS-23 Issue 5 が発行された。 | ASTM F44 の更新済み consensus standards を取り込み、normal-category aeroplanes の performance-based certification と技術革新への追随を図る。 | eVTOL 専用ではないが、電動 CTOL・ハイブリッド小型機の欧州認証で参照される compliance means が更新された。 | Heart、Aura Aero、BETA などの欧州申請・実証で、どの ASTM standard が certification basis に入るか確認する必要。 |
| 2026-04-27 | 中国 | CAAC AC-21-AA-2026-45「动力提升航空器适航标准」により、有人・純電・分散式電推 powered-lift の標準が確認できた。 | MTOW 5,700 kg 以下、最大乗客 9 席以下、非与圧、速度 463 km/h 以下という適用範囲で、CCAR-21 special class の型式合格審定基盤を作る。 | 動力電池・配電、推力制御、防火、雷撃/HIRF、高エネルギーローター、電動エンジン、プロペラ、継続耐空文書が審査項目として明確化した。 | pilotless 載人機、10席仕様、hybrid-electric variant、5,700 kg 超機への適用外・追加 special conditions を追跡する必要。 |
| 2026-04-28 | 中国 | AC-21-AA-2026-46 が追加され、正常類不載人多旋翼 UAS の適航要件が separate で明示された。 | CAAC の規格体系が powered-lift 全体（AC-21-AA-2026-45）と不載人 multirotor（AC-21-AA-2026-46）で分節化し、貨物・短距離用途に先に実装条件が揃いつつある。 | AC-21-AA-2026-46 は載人 pilotless eVTOL へ直接適用されるわけではないが、cargo/multi-rotor での認証整合条件に影響し、運航 route の接続条件を確認する。 | AC-21-AA-2026-46 から、試験項目・安全評価・運航制約が cargo eVTOL へどう反映されるかを継続確認する必要。 |
| 2026-04-27 | 日本 | SkyDrive は製造子会社 Sky Works の新代表にスズキ出身の今村元寿氏を置き、2028 年商用化へ向けた量産体制構築を明示した。 | ADO/GCP に続き、製造現場の最適化と認定事業場・TC 取得へ向けた役割分担が具体化している。 | スズキグループ工場、Sky Works、主要サプライヤー、整備文書支援を束ねて、SD-05 の開発機から量産機製造へ移す構図。 | 認定事業場、量産品質システム、TC 後の実納入能力、製造と認証戦略の分担が機能するか確認する必要。 |
| 2026-04-27 | 日本 | MLIT 官民協議会ページで ConOps 第2版概要・本文が確認でき、旧 ConOps の論点を更新すべき状態になった。 | 第2版は AAM フェーズ、AAM コリドー、AATM サービス、遠隔操縦旅客輸送、自動・自律運航をより具体化している。 | 初期は battery eVTOL/ハイブリッド、将来は水素燃料電池、低視程・厳しい気象条件、自律運航を含む段階的な技術成熟シナリオを示す。 | ConOps は概念整理であり制度化済み要件ではない。Appendix 7、通達、実証事業、AATM 実装主体への反映を追跡する必要。 |
| 2026-04-27 | 中国 | AutoFlight の zero-carbon water vertiport は、CarryAll 等の eVTOL を水上モバイル拠点から運用する海空統合インフラとして整理できる。 | CAAC 耐空標準や低空経済政策だけでは足りず、港湾・海事・航空管制・消防・電力・保険を接続する地上/水上インフラ制度が商用化条件になる。 | mobile aerial hub と intelligent command center を水上に置くことで、海上油田、緊急救助、水上観光、mobile vertiport clusters への展開を狙う。 | 恒常設置の許可、荒天・係留・充電・消防、港湾/海事当局との責任分界、反復商用運航の実績を追跡する必要。 |
| 2026-04-27 | 北米 | Archer は Hawthorne Airport 取得契約を締結済みで、LA air taxi network、LA28、AI-powered air traffic/ground operations management の testbed として使う計画を示した。 | eVTOL 事業は機体認証だけでなく、都市内の既存空港・ヘリポート資産、地上運用、AI 運航管理を押さえる段階に進んでいる。 | Midnight は 55 mile/31 minutes/126 mph 超、10,000 ft 到達の試験実績を示す一方、Hawthorne は実運航密度・地上動線・管制支援の検証基盤になる。 | airport acquisition closing、City of Hawthorne 承認、LA network の施設改修、充電・消防・ATC 接続、TIA/piloted transition を追跡する必要。 |
| 2026-04-27 | 日本 | MLIT 第5回バーティポート施設のあり方検討委員会で、整備ロードマップ、公的支援、公共性・社会便益、定性的整備効果、地域医療体制改善が議論された。 | 国内 AAM 実装では、離着陸場を単なる施設基準ではなく、公共サービス・地方創生・公的支援の評価軸で整理する必要が出ている。 | バーティポートの分類・機能に加え、消防・電力・旅客導線・地域医療・災害対応など、地上インフラの社会便益評価が技術実装の前提になる。 | 中間とりまとめ後のフォローアップ、整備支援制度、自治体実装、SkyDrive/NEXCO/JR East 等の候補地への適用を追跡する必要。 |
| 2026-04-27 | 日本 | SkyDrive は 7A Drones と台湾向け SD-05 10機 LOI を締結し、澎湖諸島の緊急医療搬送ルート案を策定。大分県では JR九州等との調査で 48 カ所の離着陸場候補を抽出した。 | 日本発 eVTOL の実装先が、国内観光・高速道路・鉄道接続に加えて、離島医療搬送と地方広域ネットワークへ広がっている。 | SD-05 の短航続・小型機特性は、離島間・観光・医療搬送・駅/港湾接続など短距離高頻度用途に合わせて市場探索されている。 | LOI の firm order 化、台湾 CAA 承認、大分の施設整備要件、医療・消防・保険・荒天時運用を追跡する必要。 |
| 2026-04-27 | 日本 | SkyDrive は SASMOS と SD-05 量産機向け EWIS 開発契約を締結し、配線システムの設計、試作、認証支援、量産準備を外部専門企業と進める。 | ADO/GCP と製造子会社体制に続き、サプライチェーン面では高電圧電動推進機の配線・認証・製造性が具体的な管理項目になった。 | EWIS は battery/BMS、flight control、avionics と並び、電動航空機の安全性、軽量化、保守性、量産品質に直結する技術領域。 | EWIS の最終認証構成、試験合格、サプライヤー品質監査、JCAB 個別 Certification Plans への反映を追跡する必要。 |
| 2026-04-27 | 北米 | Joby は turbine-electric autonomous VTOL demonstrator の初飛行を開示し、全電動 air taxi とは別に長距離・高 payload の派生技術を進めている。 | FAA TIA 対象機とは別系統の技術実証であり、既存 powered-lift 認証進捗と混同しない整理が必要。 | hybrid turbine powertrain と SuperPilot autonomy stack の組み合わせにより、電動推進・自律・防衛/商用派生の技術成熟度が新たな追跡対象になる。 | 実証機の仕様、燃料/発電系、autonomy safety case、認証経路、L3Harris との顧客化を確認する必要。 |
| 2026-04-27 | 北米 | BETA は Near Earth Autonomy と ALIA 系の自律化プログラムを進め、perception/guidance suite の FBW 統合と 2026 年上半期の flight testing 開始見込みを示した。 | ALIA CTOL の型式証明本線とは別に、dual-use/optional piloting と uncrewed operations が BETA の中長期技術軸として確認できる。 | subscale aircraft で 1,000 時間超の uncrewed flights と 158 nautical miles 超の単充電 range を示し、certifiable autonomous systems の実機統合が次の焦点。 | 実機 flight testing、FAA の remote/uncrewed operations 承認、自律化が payload/range/運航経済性に与える実測効果を確認する必要。 |
| 2026-04-27 | 日本 | Joby は Toyota と Fuji Speedway で 14 回の piloted flights を実施し、2025 年国際実証の締めくくりとして日本での operational readiness を示した。 | 日本での Joby 展開は SkyDrive とは別に、Toyota 連携、JCAB validation、東京都 eVTOL 実装事業 consortium との接点を持つ。 | 2025 年の 850 flights 超、50,000 miles 超の fleet data が TIA 準備と国際運航手順の成熟に使われる構図。 | JCAB validation、東京都事業での役割、vertiport/充電/整備/騒音、国内運航主体を確認する必要。 |
| 2026-04-27 | 中国 | EHang は CMG Spring Festival Gala 合肥会場で 16 機の EH216-S と 22,580 機の GD4.0 drones を同時運用する aerial performance を実施した。 | 商用旅客運航ではないが、低空経済都市での public visibility、複数 eVTOL 同時運航、イベント空域管理の実績として整理できる。 | EH216-S の customized lighting、pilotless formation、drone swarm orchestration は fleet management と command-and-control の広報実証になる。 | event-specific approval、空域隔離、地上監視体制、通常の観光・A-to-B 旅客運航への転用可能性を確認する必要。 |
| 2026-04-27 | 北米 | FAA は ZeroAvia ZA601 electric engine の Final Special Conditions を示し、electric motor、motor controller、高電圧電気系を primary propulsion source とする電動エンジンの認証基盤を具体化した。 | Part 33 が想定していない電動エンジンに対し、special conditions を型式証明基盤へ組み込む流れが進んだ。 | 電動推進の技術論点は、モーター出力だけでなく、電力分配、arc fault、高電圧、制御、火災、uncontained debris、ソフトウェアへ広がる。 | ZA601 の MoC、TC 発行、ZA600 hydrogen-electric powertrain の燃料電池・水素貯蔵・熱管理側の認証条件を追跡する必要。 |
| 2026-04-27 | 欧州 | Safran ENGINeUS 100 は EASA 認証済み電動モーターとして、2026 Aviation Week Laureates 受賞と FAA certification underway が確認できた。 | SC E-19 に基づく推進系認証の実例が、機体メーカーより先に成熟している。 | 180 kW maximum takeoff power、integrated electronics、air cooling、SiC、700 時間 flight testing、3,000 時間 laboratory testing が公開ベンチマークになる。 | 採用機体側の TC、FAA 認証完了、量産ライン、実運用での熱管理・整備性を追跡する必要。 |
| 2026-04-27 | 中国 | 南京市の低空経済標準体系に、eVTOL 飛行制御、整機製造、試飛検証、適航安全性評価、電池安全、低空通信・気象・航路・交通管理が列挙された。 | 中国では CAAC の耐空標準に加え、都市単位で低空経済の標準体系を組む動きが出ている。 | 機体だけでなく、5G-A、低空飛行服務平台、気象観測、公共航路、城市空中交通安全間隔まで標準化対象になる。 | 地方標準が国家標準、CAAC 審査、都市 UTM/AAM システムへどう収れんするか確認する必要。 |
| 2026-04-27 | 日本 | MLIT ConOps 第2版本文を確認し、万博後の 2027/2028 年頃からの限定的商用運航、既存施設・VP 活用、二地点間運航、ベイエリア遊覧、地方救急・観光活用が整理された。 | 国内 AAM は、機体認証単体ではなく、需要創出、運航管理、VP、AATM、AAM コリドーを束ねる社会実装フェーズへ移る設計。 | Appendix 群は遠隔操縦、自動・自律運航、交通管理サービス、低高度空域利用を同一文書で扱う。 | ConOps の概念を、具体路線、運航者、VP 許可、AATM サービス主体、通達・実証事業へ照合する必要。 |
| 2026-04-27 | 北米 | Joby は 2024 年末に TIA 配下の FAA-conforming flight deck simulator human factors 試験を実施済みで、2026-04 には Reuben Brothers と Los Angeles の Century Plaza 住宅 vertiport 構想を発表した。 | Joby の認証は simulator TIA から aircraft flight TIA へ進む段階であり、商用化準備は既存 helipad の vertiport 転用、充電、住宅 passenger lounge まで広がっている。 | Century Plaza 案件は既存 helipad を eVTOL 運航・充電に使う都市実装モデルだが、施設承認と TC/運航承認は別工程。 | FAA pilot flight TIA、Century Plaza の地方・州・連邦承認、消防・電力・騒音・住民向け運航範囲を追跡する必要。 |
| 2026-04-27 | 中国 | EHang VT35 の公式仕様ページで、経済巡航速度 216 km/h 以上、満載航続 200 km 以上、耐空 60 分、payload 200 kg 以上、8 lift + 1 propulsion propeller などの公称値を確認した。 | VT35 は EH216-S の短距離観光型から、都市間・島嶼・山岳ルート向けの長距離 pilotless eVTOL へ製品範囲を広げる位置付け。 | remote supervision、obstacle avoidance、multi-aircraft collaboration、EH216-S vertiport 互換を訴求し、機体仕様とインフラ共有を同時に進める構図。 | CAAC TC 上の認証性能値、full-load range、remote supervision safety case、A-to-B 商用ルート承認を確認する必要。 |
| 2026-04-27 | 北米 | FAA AIP の ENR 8.6 に Advanced Air Mobility が掲載され、UAM/RAM、公共サービス、大型貨物、個人・レクリエーション機が想定ユースケースとして明示された。 | AAM が実証プログラムや専用広報ページだけでなく、航空情報公示体系の UAS 節にも位置付けられた。 | 現時点では概念整理で、route、ATC 手順、vertiport 手順、AAM corridor の実運用情報は別途具体化が必要。 | eIPP や Innovate28 の成果が AIP、Chart Supplement、NOTAM、管制手順へどう反映されるか確認する必要。 |
| 2026-04-27 | 中国 | EHang は EH216-S の TC/TCDS 後の初期運航について、CAAC と段階的な operational limitations に合意していたことを再確認した。 | EH216-S は TC/PC/AC/OC を取得済みでも、初期商用化は route、schedule、observer、BVLOS、水上離着陸制限などを段階的に緩和する設計。 | 2026 年の public ticketing や A-to-B route trial を評価する際、単なる「商用開始」ではなく、制限付き運航からの拡張状況を追う必要がある。 | 最新 TCDS、OC 運航マニュアル、地上要員資格、制限緩和の実績を確認する必要。 |
| 2026-04-27 | 北米 | Archer は Texas、Florida、New York の eIPP パートナー選定を受け、2026 年下半期の Midnight early operations 準備を示し、別途 Starlink 搭載試験も発表している。 | eIPP は TC/TIA の代替ではなく、州・都市別の初期運航データを FAA 政策へ戻す枠組み。Starlink は通信・EMI・サイバーセキュリティの認証論点を増やす可能性がある。 | Midnight の運航設計は機体性能、地上施設、AI 運航管理に加え、LEO 通信を含む connected aircraft 化へ広がっている。 | certification plans acceptance、TIA 開始、eIPP 州別 route/搭乗者条件、Starlink が認証用構成へ入るかを追跡する必要。 |
| 2026-04-27 | 北米 | Uber と Joby は Dubai 向けに Uber Air powered by Joby のアプリ予約体験を公開し、Joby は 2026 年後半の初期旅客搭乗を見込むと説明した。 | 米国 FAA TC/eIPP と並行して、海外ローンチ市場では認証・運航承認だけでなく既存配車アプリとの販売導線が商用化準備に入っている。 | multimodal journey、地上交通接続、予約・遅延対応、顧客説明、データ連携が eVTOL 初期サービスの運用技術論点になる。 | Dubai の実運航承認、予約開始日、運賃、旅客搭乗条件、米国 eIPP との知見還流を確認する必要。 |

## 注目すべき規制変化

- 米国: FAA powered-lift final rule と air carrier definition 更新により、商用 powered-lift 運航の制度枠が見えている。MOSAIC は 2026-07-24 に LSA certification 関連規則が有効化予定。
- 米国: eIPP は 8 パートナーを選定し、air taxi、長距離固定翼、貨物、医療・緊急輸送、automation safety の初期運航実証を政策形成に使う枠組みになった。
- 米国: ZeroAvia ZA601 electric engine の Final Special Conditions により、電動エンジンを Part 33 相当の安全水準で扱う個別認証基盤が具体化した。
- 欧州: EASA が 2025-07 に IAM の AMC/GM を追加し、Air OPS、FCL、SERA に manned VTOL-capable aircraft 対応を入れた。
- 欧州: EASA ED Decision 2026/001/R と 2026/002/R により、電動・ハイブリッド推進機の整備士訓練、Part-145/Part-66 等の継続耐空性ルールが具体化した。
- 欧州: Safran ENGINeUS 100 は EASA 認証済み電動モーターとして、SC E-19 の実装例と FAA 認証中の推進系ベンチマークになっている。
- 中国: 改正民用航空法が 2026-07-01 に施行予定。民用無人航空機の耐空証明義務化が低空経済の制度基盤になる。
- 中国: CAAC の実名登録・激活強制標準が 2026-05-01 から新規生産 UAS に適用され、AC-21-AA-2026-47 が不載人 powered-lift UAS の耐空標準を明確化した。
- 中国: AC-21-AA-2026-46 で正常类多旋翼无人驾驶航空器系统（不载人）適航標準が正式に追加発行され、AC-21-AA-2026-47 の系譜に続く不載人用途の分節規定として、貨物・短距離運航での実装条件整理を前進させた。
- 中国: 南京市の低空経済標準体系は、eVTOL 機体・電池・試験・製造だけでなく、低空通信、気象、公共航路、都市空中交通管理まで標準化対象に入れた。
- 日本: SkyDrive の ADO 認定と General Certification Plan 合意により、JCAB 型式証明プロセスが具体化。MLIT は空飛ぶクルマ特別要件と試験飛行手続を整備。
- 日本: MLIT の無人航空機型式認証手続き改正と試験飛行ガイドライン更新要素、バーティポート検討が、空飛ぶクルマ実装の周辺制度として重要。
- 日本: ConOps 第2版本文は、2027/2028 年頃の限定的商用運航、AAM コリドー、AATM サービス、遠隔操縦・自動自律運航を社会実装の前提文書として整理した。

## 次回追跡すべき論点

- FAA eIPP の各パートナー別プロジェクト、対象機体、運航開始日、搭乗者範囲。
- Joby/Archer の TIA、FAA pilot for-credit testing、piloted transition の公式完了情報。
- Archer の Hawthorne Airport 取得 closing、LA air taxi network/LA28 testbed、AI-powered air traffic/ground operations management の安全評価と自治体承認。
- BETA ALIA CTOL の FAA 型式証明状況、Hawaii デモ飛行の実施結果。
- EASA SC-VTOL-02/MOC、SC E-19 MoC の最終化と欧州メーカーへの適用。
- EASA SC E-19 の Safety Assessment、Overspeed and Containment の final publication。
- 中国の改正民用航空法実施細則、EH216-S の一般向け有償運航、VT35 の認証進捗。
- CAAC AC-21-AA-2026-47 の貨物 eVTOL 型式審査への適用事例。
- SkyDrive の個別 Certification Plans 承認、ADO 認定範囲の公的照合、東京デモ後の認証試験計画。
- Wisk Gen 6 の自律運航認証方針、BETA ALIA CTOL の conformity inspection と certification flight testing。
- Joby/ASI の live operational exercises と、eVTOL 高密度運航を既存 NAS/BNATCS に接続する実証結果。
- Joby の turbine-electric autonomous VTOL demonstrator の仕様、SuperPilot autonomy stack、L3Harris 連携、防衛/商用用途での認証経路。
- Joby/Reuben Brothers の Century Plaza residential vertiport が、既存 helipad 改修、充電、passenger lounge、地方・州・連邦承認、住宅利用者向けサービス設計へ進むか。
- Uber Air powered by Joby の Dubai 初期サービスで、アプリ予約、地上交通接続、運賃、運航承認、旅客搭乗実績が公表されるか。
- Vertical Valo の battery pilot line と VEC2 開設、認証用機体生産、hybrid-electric demonstrator の飛行開始。
- Volocopter VoloXPro の ultralight certification と VoloCity EASA TC との関係。
- Volocopter の Bruchsal sandbox、Diamond 傘下の supply chain realignment が VoloCity/VoloXPro の認証スケジュールに与える影響。
- Lilium 残余資産の売却先、Archer 取得特許の実装、欧州発 eVTOL 技術の人材・設計データ承継。
- EHang の 2026 年 commercial operations 実績、AutoFlight CarryAll の反復商用貨物運航。
- AutoFlight Matrix の CAAC 申請、hybrid-electric variant の認証基準、旅客/貨物顧客。
- AutoFlight CarryAll の実水域救助待機が、自治体・公安・医療と連携した定常 emergency response サービスへ進むか。
- 日本ロードマップ改訂後の 2027/2028 年商用運航候補地域、AAMコリドー、遠隔操縦旅客輸送制度。
- Wisk/Texas eIPP、SkyGrid Strata、Gen 6 remote supervision の FAA 受容。
- Wisk/Texas eIPP の three-phase flight program が Automated Flight Rules と remote supervisor 制度化へどう接続されるか。
- FAA eIPP selected projects の 2026 年夏の実運航開始、PANYNJ/Manhattan heliport 案件の機体・運航者・搭乗者範囲。
- XPENG ARIDGE の Land Aircraft Carrier 認証・量産・納入と、A868 hybrid-electric tiltrotor の flight verification。
- SkyDrive MASC LOI の firm order 化、大阪湾岸 100機構想の機体調達・vertiport 実装。
- SkyDrive/NEXCO 西日本の PA/SA 活用が、具体地点、災害対応、消防・騒音・旅客導線を含む vertiport 設計へ進むか。
- 中国の低空保険制度が、UAS/eVTOL の第三者責任、運航許可、商用運航コストにどう組み込まれるか。
- FAA MCO/LAX HITL reports の比較、空港別の route/vertiport 設計、controller workload、TCAS/go-around 論点。
- JR East の駅・宿泊施設連携モデルと SkyDrive 1機 pre-order の実証・firm order 化。
- BETA の Charge Cube 稼働拠点数、ALIA 訓練プログラムの顧客適用、充電規格の他社機対応。
- BETA の 2026-05-12 Q1 決算で、ALIA CTOL の conformity inspection、certification flight testing、累計飛行距離、100 sites 超の充電インフラ内訳が更新されるか。
- BETA/Near Earth Autonomy の自律化プログラムで、2026 年上半期の flight testing、FBW への perception/guidance suite 統合、optional piloting/uncrewed operations の FAA 受容が進むか。
- FAA Propulsion Systems 技術分野で示された electric/hybrid-electric propulsion と hydrogen-fueled aircraft の認証政策が、ZeroAvia、BETA、hybrid-electric eVTOL/CTOL の special conditions や MoC にどう落ちるか。
- ZeroAvia ZA601 electric engine の MoC、FAA TC、ZA600 hydrogen-electric powertrain の燃料電池・水素貯蔵・熱管理認証条件。
- EASA ED Decision 2026/003/R の CS-23/ASTM F44 更新が、欧州の電動 CTOL・ハイブリッド小型機の certification basis にどう反映されるか。
- Safran ENGINeUS 100 の FAA 認証、Niort/Pitstone 量産ライン、採用機体側の TC と実運用信頼性。
- CAAC AC-21-AA-2026-45 が、沃飞、峰飞、沃兰特、时的など中国有人 powered-lift 申請案件の型式合格審定にどう使われ、標準外の pilotless/10席/hybrid 仕様にどんな special conditions が出るか。
- 南京市など地方低空標準体系が、国家標準、CAAC 適航審査、都市 AAM/UTM、eVTOL 電池・飛控・試験・製造標準へどう収れんするか。
- SkyDrive/Sky Works の量産体制強化が、認定事業場取得、TC、量産品質保証、2028 年納入計画にどう接続されるか。
- BETA/Loganair/Royal Mail の Scotland electric flight demonstration 後の MOU 実行、定期郵便・貨物運航への移行可否、UK CAA/EASA 認証との接続。
- EASA SC E-19 の battery、HV distribution、thermal runaway 関連 MoC と、EHPS.420 endurance MoC の個別メーカー適用。
- EHang VT35 の RMB 6.5 million purchase orders の契約性、Hefei hub の量産・認証実績、初期納入機の耐空状態。
- EHang VT35 の公式仕様値が CAAC TC 上の認証性能、remote supervision safety case、obstacle avoidance、A-to-B route approval にどう反映されるか。
- EHang EH216-S の Guangzhou/Hefei public ticketing 実績、タイ CAAT の認証・運航許可・vertiport 基準化。
- EHang の複数 EH216-S 同時運航と drone swarm orchestration が、通常の観光・A-to-B 旅客運航手順へ展開できるか。
- AutoFlight zero-carbon water vertiport の実設置先、港湾・海事・航空管制との承認、充電・消防・係留・荒天時運用条件。
- SkyDrive ADO 認定の ASIMS/MLIT 公的一覧反映、個別 Certification Plans 承認、compliance testing 開始。
- SkyDrive/7A Drones の台湾 10機 LOI が firm order、台湾 CAA 認証・運航承認、澎湖諸島の緊急医療搬送ルート実装へ進むか。
- 大分県の 48 カ所離着陸場候補が、施設整備要件、運航ルート事業性、商業運航ロードマップ、自治体・医療・消防連携へ具体化するか。
- SkyDrive/SASMOS の EWIS 開発が、SD-05 認証用構成、高電圧配線安全、量産準備、保守文書へどう反映されるか。
- Joby/Toyota の Fuji Speedway 実証、JCAB validation、東京都 eVTOL 実装事業 consortium への関与。
- SkyDrive の Florida/Aeroauto 8機 LOI と AeroGulf 20機基本合意が firm order、運航者証明、vertiport/charging/maintenance 体制へ進むか。
- FAA Product Issues List の eVTOL、electric/hybrid propulsion、distributed propulsion、remote/autonomous systems、AI/ML software、Lightning/HIRF 項目が、BETA ALIA CTOL や非伝統的 Part 23 電動機の certification plan/MOC にどう反映されるか。
- FAA Advanced Air Mobility Implementation Plan Version 1.0 の更新、Innovate28 key site と eIPP selected projects の接続、vertiport Part 77/157・環境レビュー・消防・電力要件の具体化。
- FAA AAM Infrastructure/EB 105A の更新、自律・IFR・高重量 eVTOL への vertiport 基準拡張、regional AAM contact と地方承認の実運用。
- Vertical Valo の Molicel/Honeywell/propeller 整備性訴求が、CDR、認証用機体、continued airworthiness 文書にどう反映されるか。
- SkyDrive SD-05 のサプライヤー構成が JCAB 個別 Certification Plans、整備マニュアル、量産品質保証、海外認証へどう接続されるか。
- MLIT ConOps 第2版の Appendix 7、AAM コリドー、AATM サービス、遠隔操縦旅客輸送、自動・自律運航が、具体の通達・実証・事業制度へどう反映されるか。
- ConOps 第2版本文の万博後社会実装イメージを、2027/2028 年候補地域、二地点間運航、空港アクセス、AATM サービス、AAM コリドーの具体案件に照合する。
- 日本のバーティポート整備ロードマップ、公的支援、公共性・社会便益評価が、施設基準・自治体実装・地域医療/災害対応ユースケースへどう反映されるか。

## ファイル構成

- `/Volumes/ex/study/e-plane/research/north-america/notes.md`
- `/Volumes/ex/study/e-plane/research/europe/notes.md`
- `/Volumes/ex/study/e-plane/research/china/notes.md`
- `/Volumes/ex/study/e-plane/research/japan/notes.md`
- `/Volumes/ex/study/e-plane/research/summary.md`
