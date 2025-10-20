[shelf](https://github.com/kijimaD/shelf)で生成したPDF本棚のメタ情報。PDF本体はプライベートな空間にある。

## Prepare

```
go install github.com/kijimaD/parakeet@main
parakeet generate . --ext pdf
parakeet md . --ext pdf
```

## (private) Sync PDF

事前にSSH configを設定しておくこと。

送信

```
rsync -r -e ssh * xsrv:~/mypdfs/
```

受信

```
rsync -r -e ssh xsrv:~/mypdfs/* .
```

## output

| ID | Title | Tags |
|---|---|---|
| 20251020T211207 | 100gomistakesandhowtoavoidthem |  |
| 20251020T211208 | 2Dグラフィックスのしくみ-――図解でよくわかる画像処理技術のセオリー_00 |  |
| 20251020T211209 | 30日でできる!OS自作入門-1.0.1 |  |
| 20251020T211210 | 32ビットコンピュータをやさしく語るはじめて読む486-1.0.0 |  |
| 20251020T211211 | 9781801070058 |  |
| 20251020T211212 | AWSネットワーク入門第2版-1.0.0 |  |
| 20251020T211213 | CPUの創りかた-1.0.0 |  |
| 20251020T211214 | CircleCI実践入門-──CI-CDがもたらす開発速度と品質の両立_00 |  |
| 20251020T211215 | CleanArchitecture-1.0.0 |  |
| 20251020T211216 | CodeReading_プレミアムブックス版_オープンソースから学ぶソフトウェア開発技法-1.0.0 |  |
| 20251020T211217 | Docker-Kubernetesネットワークのしくみ |  |
| 20251020T211218 | Friends-RISC-V技術書典７電子版 |  |
| 20251020T211219 | Goでちょっとひといき |  |
| 20251020T211220 | GoとSAMで学ぶAWSLambda-1.0.0 |  |
| 20251020T211221 | Goならわかるシステムプログラミング第2版 |  |
| 20251020T211222 | Goプログラミング実践入門_標準ライブラリでゼロからWebアプリを作る-1.4.0 |  |
| 20251020T211223 | Go言語reflectハンドブック-1.0.0 |  |
| 20251020T211224 | Go言語でつくるインタプリタ |  |
| 20251020T211225 | Go言語によるWebアプリケーション開発 |  |
| 20251020T211226 | Go言語を楽しむ5つのレシピ_コタツと蜜柑とゴーファーとわたし-1.0.0 |  |
| 20251020T211227 | HSmath |  |
| 20251020T211228 | Kubernetesで実践するPlatformEngineering |  |
| 20251020T211229 | LinuxContainerBook-1.0.0 |  |
| 20251020T211230 | Linuxのしくみ-―実験と図解で学ぶOS、仮想マシン、コンテナの基礎知識 |  |
| 20251020T211231 | Linuxシステムプログラミング |  |
| 20251020T211232 | MakingSoftware |  |
| 20251020T211233 | NuxtとGoではじめるWebアプリ開発-1.0.0 |  |
| 20251020T211234 | RISC-Vから学ぶC言語-1.0.0 |  |
| 20251020T211235 | Raspberry Pi をはじめよう |  |
| 20251020T211236 | Rubyのしくみ_RubyUnderaMicroscope-1.0.0 |  |
| 20251020T211237 | TCP-IPネットワーク-ステップアップラーニング_00 |  |
| 20251020T211238 | TCP-IP技術入門 |  |
| 20251020T211239 | TypeScriptとReact-Next.jsでつくる-実践Webアプリケーション開発_00 |  |
| 20251020T211240 | WriteGreatCode〈Vol.1〉_ハードウェアを知り、ソフトウェアを書く-1.0.0 |  |
| 20251020T211241 | advancedalgorithmsanddatastructures |  |
| 20251020T211242 | advancednetworksimulationssimplified |  |
| 20251020T211243 | architectingawswithterraform |  |
| 20251020T211244 | asynchronousprogramminginrust |  |
| 20251020T211245 | automatingdevopswithgitlabciandcdpipelines |  |
| 20251020T211246 | awscertifiedsecurity_specialtyscs-c02examguide_secondedition |  |
| 20251020T211247 | awscertifiedsolutionsarchitect_professionalexamguidesap-c02 |  |
| 20251020T211248 | azurearchitectureexplained |  |
| 20251020T211249 | azurefordevelopers_secondedition |  |
| 20251020T211250 | binary_hack |  |
| 20251020T211251 | buildingananonymizationpipeline |  |
| 20251020T211252 | buildingmoderncliapplicationsingo |  |
| 20251020T211253 | buildyourownprogramminglanguage |  |
| 20251020T211254 | c_realtime_os |  |
| 20251020T211255 | cdatastructuresandalgorithms_secondedition |  |
| 20251020T211256 | cloudsolutionarchitectscareermasterplan |  |
| 20251020T211257 | codelikeaproinc |  |
| 20251020T211258 | communicatingwithdata |  |
| 20251020T211259 | comptiaapluspracticetestcore1220-1101 |  |
| 20251020T211300 | comptiaapluspracticetestcore2220-1102 |  |
| 20251020T211301 | comptiaapluspracticetestscore12201101andcore22201102_packt |  |
| 20251020T211302 | computer_architecture_essence |  |
| 20251020T211303 | cost-effectivedatapipelines |  |
| 20251020T211304 | cplusplushighperformance |  |
| 20251020T211305 | dancingwithqubits |  |
| 20251020T211306 | data-orientedprogramming_reducesoftwarecomplexity |  |
| 20251020T211307 | dataalgorithmswithspark |  |
| 20251020T211308 | datapipelinespocketreference |  |
| 20251020T211309 | dataqualityengineeringinfinancialservices |  |
| 20251020T211310 | datascience_thehardparts |  |
| 20251020T211311 | datastructuresandalgorithmswiththecplusplusstl |  |
| 20251020T211312 | decipheringdataarchitectures |  |
| 20251020T211313 | designingandimplementingmicrosoftazurenetworkingsolutions |  |
| 20251020T211314 | designingmachinelearningsystems_V4 |  |
| 20251020T211315 | dockerworkshop |  |
| 20251020T211316 | dokusyu_assembly |  |
| 20251020T211317 | domain-drivendesignwithgolang |  |
| 20251020T211318 | effective_softwaretesting_adevelopers_guide |  |
| 20251020T211319 | effectiveconcurrencyingo |  |
| 20251020T211320 | efficientcloudfinops |  |
| 20251020T211321 | embracingdevopsreleasemanagement |  |
| 20251020T211322 | event-drivenarchitectureingolang |  |
| 20251020T211323 | expertdelphi |  |
| 20251020T211324 | fivelinesofcode_howandwhentorefactor |  |
| 20251020T211325 | footballanalyticswithpythonandr |  |
| 20251020T211326 | foundationsofscalablesystems |  |
| 20251020T211327 | fullstackpythonsecurity |  |
| 20251020T211328 | functionalprogrammingingo |  |
| 20251020T211329 | go_parallel |  |
| 20251020T211330 | gofordevops |  |
| 20251020T211331 | goodcodebadcode |  |
| 20251020T211332 | google_software_engeering |  |
| 20251020T211333 | googlecloudcertifiedprofessionalcloudnetworkengineerguide |  |
| 20251020T211334 | goprogramming_frombeginnertoprofessional |  |
| 20251020T211335 | goprogrammingcookbook |  |
| 20251020T211336 | goworkshop |  |
| 20251020T211337 | graphql |  |
| 20251020T211338 | grokkingcontinuousdelivery |  |
| 20251020T211339 | grpcgoforprofessionals |  |
| 20251020T211340 | hajimete_lisp |  |
| 20251020T211341 | hands-on-rust_P1.0 |  |
| 20251020T211342 | hands-onhighperformancewithgo |  |
| 20251020T211343 | hands-onnetworkprogramingwithc |  |
| 20251020T211344 | hands-onsoftwarearchitecturewithgolang |  |
| 20251020T211345 | hands-onsoftwareengineeringwithgolang |  |
| 20251020T211346 | hands-onsystemprogrammingwithgo |  |
| 20251020T211347 | haskell |  |
| 20251020T211348 | head_first_c |  |
| 20251020T211349 | javascriptdesignpatterns |  |
| 20251020T211350 | jsicp |  |
| 20251020T211351 | juliahighperformance |  |
| 20251020T211352 | kubernetes_devops |  |
| 20251020T211353 | kubernetesworkshop |  |
| 20251020T211354 | land_of_lisp |  |
| 20251020T211355 | learnai-assistedpythonprogramming |  |
| 20251020T211356 | learncprogramming |  |
| 20251020T211357 | learndatastructuresandalgorithmswithgolang |  |
| 20251020T211358 | learningdevopssecondedition |  |
| 20251020T211359 | learnjavawithprojects |  |
| 20251020T211400 | learnllvm17 |  |
| 20251020T211401 | learnwireshark_secondedition |  |
| 20251020T211402 | linuxdevopshandbook |  |
| 20251020T211403 | linuxfornetworkingprofessionals |  |
| 20251020T211404 | mastering-emacs-v3-jp |  |
| 20251020T211405 | mastering-go-standard-packages |  |
| 20251020T211406 | masteringgo |  |
| 20251020T211407 | masteringpaloaltonetworks |  |
| 20251020T211408 | masteringpaloaltonetworks_secondedition |  |
| 20251020T211409 | masteringpfsense_ebook |  |
| 20251020T211410 | masteringpythondesignpatterns_thirdedition |  |
| 20251020T211411 | masteringpythonnetworking_fourthedition |  |
| 20251020T211412 | masteringwindowsserver2022_fourthedition |  |
| 20251020T211413 | microserviceswithgo |  |
| 20251020T211414 | microsoft365administratorms-102examguide |  |
| 20251020T211415 | microsoftazurefundamentalscertificationandbeyond1e |  |
| 20251020T211416 | microsoftazurefundamentalscertificationandbeyond2e |  |
| 20251020T211417 | modern_software_engineer |  |
| 20251020T211418 | moderndevopspractices_secondedition |  |
| 20251020T211419 | modernpythoncookbook |  |
| 20251020T211420 | mongodbthedefinitiveguide |  |
| 20251020T211421 | multi-cloudfordevelopers |  |
| 20251020T211422 | networkautomationcookbook |  |
| 20251020T211423 | networkautomationwithgo |  |
| 20251020T211424 | nodejsdesignpatterns |  |
| 20251020T211425 | n月刊ラムダノートVol4No3(2024)（電子書籍のみ） |  |
| 20251020T211426 | observabilitywithgrafana |  |
| 20251020T211427 | practical_common_lisp |  |
| 20251020T211428 | practicalansible_secondedition |  |
| 20251020T211429 | practicaldataprivacy |  |
| 20251020T211430 | practicesofthepythonpro |  |
| 20251020T211431 | pragmaticmicroserviceswithcandazure |  |
| 20251020T211432 | progit |  |
| 20251020T211433 | programming_scala |  |
| 20251020T211434 | pythonconcurrencywithasyncio |  |
| 20251020T211435 | pythonforsecurityandnetworking |  |
| 20251020T211436 | pythonhow-to_63techniquestoimproveyourpythoncode |  |
| 20251020T211437 | react |  |
| 20251020T211438 | real_world_http |  |
| 20251020T211439 | redhatcertifiedspecialistinservicesmanagementandautomationex358exa |  |
| 20251020T211440 | regex |  |
| 20251020T211441 | regularexpressionpuzzlesandaicodingassistants |  |
| 20251020T211442 | rust |  |
| 20251020T211443 | rustinaction |  |
| 20251020T211444 | rustserversservicesandapps |  |
| 20251020T211445 | scalingpythonwithray |  |
| 20251020T211446 | self-taughtcloudcomputingengineer |  |
| 20251020T211447 | skillsofasuccessfulsoftwareengineer |  |
| 20251020T211448 | softwaremistakesandtradeoffs_howtomakegoodprogrammingdecisions |  |
| 20251020T211449 | softwaretestingstrategies |  |
| 20251020T211450 | sql_anti_pattern |  |
| 20251020T211451 | streetcoder_therulestobreakandhowtobreakthem |  |
| 20251020T211452 | syoukai_linux_pg |  |
| 20251020T211453 | systemdesignguideforsoftwareprofessionals |  |
| 20251020T211454 | systemprogrammingessentialswithgo |  |
| 20251020T211455 | test-drivendevelopmentingo |  |
| 20251020T211456 | the_architecture_of_open_source_applications |  |
| 20251020T211457 | ultimatedockercontainerbook |  |
| 20251020T211458 | unityinaction3e |  |
| 20251020T211459 | web-api |  |
| 20251020T211500 | window_kernel_driver_programming |  |
| 20251020T211501 | zabbix6itinfrastructuremonitoringcookbook_secondedition |  |
| 20251020T211502 | zerodeep01 |  |
| 20251020T211503 | 「技術書」の読書術 |  |
| 20251020T211504 | すごいHaskellたのしく学ぼう！-1.0.0 |  |
| 20251020T211505 | なっとく機械学習 |  |
| 20251020T211506 | はじめてのGoコード生成 |  |
| 20251020T211507 | はじめてのOSコードリーディング-――UNIX-V6で学ぶカーネルのしくみ |  |
| 20251020T211508 | エキスパートたちのGo言語-一流のコードから応用力を学ぶ_00 |  |
| 20251020T211509 | ガベージコレクション |  |
| 20251020T211510 | ガベージコレクションのアルゴリズムと実装-1.0.0 |  |
| 20251020T211511 | コンピュータシステムの理論と実装 |  |
| 20251020T211512 | コーディングを支える技術――成り立ちから学ぶプログラミング作法_00 |  |
| 20251020T211513 | スターティングgRPC-1.0.0 |  |
| 20251020T211514 | ゼロからのOS自作入門 |  |
| 20251020T211515 | ネットワークのしくみ-19971 |  |
| 20251020T211516 | ピアリング戦記日本のインターネットを繋ぐ技術者たち（電子書籍のみ） |  |
| 20251020T211517 | ブラウザハック |  |
| 20251020T211518 | プログラミングClojure第2版-1.0.0 |  |
| 20251020T211519 | プログラミングコンテストチャレンジブック[第2版]-1.19.0 |  |
| 20251020T211520 | プログラミングコンテスト攻略のためのアルゴリズムとデータ構造-1.0.0 |  |
| 20251020T211521 | プログラミング作法-1.0.0 |  |
| 20251020T211522 | マイクロカーネルの設計と実装 |  |
| 20251020T211523 | マスタリングTCP_IP入門編第6版-1.0.0 |  |
| 20251020T211524 | ユーザーストーリーマッピング |  |
| 20251020T211525 | ライティングソフトウェア |  |
| 20251020T211526 | リファクタリング_既存のコードを安全に改善する（第2版）-1.0.0 |  |
| 20251020T211527 | 低レベルプログラミング |  |
| 20251020T211528 | 単体テストの考え方 |  |
| 20251020T211529 | 基礎からわかるGo言語 |  |
| 20251020T211530 | 基礎からわかるTCP_IPネットワークコンピューティング入門第3版-1.0.0 |  |
| 20251020T211531 | 増補改訂版-図解でわかる-はじめてのデジタル画像処理_00 |  |
| 20251020T211532 | 実用Go言語 |  |
| 20251020T211533 | 改訂2版-みんなのGo言語_00 |  |
| 20251020T211534 | 自作エミュレータで学ぶx86アーキテクチャ |  |
| 20251020T211535 | 血と汗とピクセル_大ヒットゲーム開発者たちの激戦記-1.0.0 |  |
| 20251020T211536 | 行列プログラマー |  |
| 20251020T211537 | 詳解Go言語Webアプリケーション開発 |  |
| 20251020T211538 | 詳解linuxカーネル |  |
