# BeatSaber自作ツールの紹介
![image](https://github.com/user-attachments/assets/bf449827-596d-45c1-91f3-a94cf0a816ce)
* [BeatSaber-mod対応状況](https://github.com/rynan4818/rynan4818.github.io/wiki/BeatSaber-mod%E5%AF%BE%E5%BF%9C%E7%8A%B6%E6%B3%81)
* [ChroMapper-Plugin対応状況](https://github.com/rynan4818/rynan4818.github.io/wiki/ChroMapper-Plugin%E5%AF%BE%E5%BF%9C%E7%8A%B6%E6%B3%81)
----
# オーバーレイ関係
## [Beat Saber Overlay 改良版](https://github.com/rynan4818/beat-saber-overlay)
[Beat Saber Overlay](https://github.com/Reselim/beat-saber-overlay)に各種表示オプションを追加し、機能改善したオーバーレイ

<img src="https://rynan4818.github.io/beatsaber-overlay-bsr-image.png" width="301" height="166">

## [tournament_overlay](https://github.com/rynan4818/tournament_overlay)
BeatSaberの大会開催時に便利なスコア表示用オーバーレイ

<img src="https://rynan4818.github.io/tournament_overlay1.png" width="549" height="92">

## [obs-control](https://github.com/rynan4818/obs-control)
[Beat Saber Overlay 改良版](https://github.com/rynan4818/beat-saber-overlay)でOBS Studioのシーンコントロールをする追加スクリプト

[サンプル動画](https://twitter.com/rynan4818/status/1383422547090284550)

## [Streamlabs-obs-control](https://github.com/rynan4818/Streamlabs-obs-control)
[Beat Saber Overlay 改良版](https://github.com/rynan4818/beat-saber-overlay)でStreamlabs OBSのシーンコントロールをする追加スクリプト

[サンプル動画](https://twitter.com/rynan4818/status/1384822435434831874)

## [sound-option](https://github.com/rynan4818/sound-option)
[Beat Saber Overlay 改良版](https://github.com/rynan4818/beat-saber-overlay)でイベント合わせて音声ファイルを鳴らす追加スクリプト

## [HttpPlayButtonStatus](https://github.com/rynan4818/HttpPlayButtonStatus)
obs-controlやStreamlabs-obs-controlのゲームスタートシーンに切り替わるタイミングを、PLAYボタンを押した瞬間に早められるmod。
自動シーン切り替えのON/OFFやオプション用シーン1~3にBeatSaber内から手動切替もできます。

## [BS-AutoSceneChanger](https://github.com/rynan4818/BS-AutoSceneChanger)
XSplit Broadcasterのシーン自動切り替えをする拡張プラグイン

[サンプル動画](https://twitter.com/rynan4818/status/1384522716795994131)

## ["Song of Pi (10238 Digits Ver.)" Overlay](https://github.com/rynan4818/song-of-pi-overlay)
["Song of Pi (10238 Digits Ver.)"](https://beatsaver.com/beatmap/60a)の現在と残り桁数と数字を表示するオーバーレイ

<img src="https://rynan4818.github.io/song-of-pi-overlay.png" width="237" height="116">

## [bsdp-like-overlay](https://github.com/rynan4818/bsdp-like-overlay)
[Beat Saber Overlay 改良版](https://github.com/rynan4818/beat-saber-overlay)用の[BSDP-Overlay](https://github.com/kOFReadie/BSDP-Overlay)ライクなオーバーレイ

<img src="https://rynan4818.github.io/bsdp-like-overlay.png" width="306" height="234">

# 録画用ツール
## [bs-movie-cut (BeatSaberプレイ動画カットツール)](https://github.com/rynan4818/bs-movie-cut)
BeatSaberのゲームプレイ録画の編集や整理を支援するツール

<img src="https://rynan4818.github.io/bs_movie_cut_image.png" width="800" height="355">

## [DataRecorder](https://github.com/rynan4818/DataRecorder)
上記のプレイ動画カットツール（[BS Movie Cut](https://github.com/rynan4818/bs-movie-cut)）用のプレイ情報記録用mod

# カメラスクリプト・演出用ツール
## [ChroMapper-CameraMovement](https://github.com/rynan4818/ChroMapper-CameraMovement)
BeatSaberでカメラワークを作成するための、ChroMapper用のプラグインです。
CameraPlus用のカメラスクリプトのプレビューや、Script Mapperを使ったスクリプトの作成を支援する機能があります。

<img src="https://user-images.githubusercontent.com/14249877/158151048-4d7dbe2e-0df6-4a9d-812a-b977847721b7.png" width="696" hight="443">

## [MovementRecorder](https://github.com/rynan4818/MovementRecorder)
BeatSaberでアバターやセイバー等のオブジェクトの動きを曲の時間に合わせて記録するツールです。ChroMapper-CameraMovementで再生することができます。

## [blender2ScriptMapper](https://github.com/rynan4818/blender2ScriptMapper)
Blenderで作ったカメラパスをCameraPlus用のカメラスクリプトとして出力するBlender用のスクリプトです。
Script MapperのscriptコマンドでBlenderで作ったカメラパスを読み込めます。

## [MovementScriptChange](https://github.com/rynan4818/MovementScriptChange)
CameraPlusのMovementScript(カメラスクリプト)の指定した時間のJSONを書き換えるツールです。

## [AutoItControl](https://github.com/rynan4818/AutoItControl)
BeatSaberでAutoItを使って外部ソフトをコントロールするmod

## [CustomSongTimeEvents](https://github.com/rynan4818/CustomSongTimeEvents)
BeatSaberのCustom Sabers(Saber Factory), Custom Avatars, Custom Platformsの3Dモデルデータに、譜面の曲時間に合わせたイベントを追加するUnityコンポーネント、BeatSaber mod、プレビュー用のChroMapperプラグインです。

# マッピングツール
## [ChroMapper-HalfJumpDurationMark](https://github.com/rynan4818/ChroMapper-HalfJumpDurationMark)
ChroMapperで、Half Jump Durationの位置(ノーツがスポーンする位置)に薄い壁を表示するプラグインです。

<img src="https://user-images.githubusercontent.com/14249877/184469197-987ee5d7-e05b-4b99-89da-89eb6a30157c.png" width="581" hight="389">

## [ChroMapper-SongDataChanger](https://github.com/rynan4818/ChroMapper-SongDataChanger)
ChroMapperで、曲データやオフセットをエディタ上で変更できます。またDemucsを使って曲の分離ができます。

## [Demucs v4の簡単インストーラ](https://drive.google.com/drive/u/1/folders/1bm_OMCmlPIrX1vOgWgVwGNfBB4HrXUnA)
音楽データをAI学習データを使って、ドラム・ベース・ボーカル・その他に高精度に分離することができるDemucs v4の簡単インストーラです。
BeatSaberの作譜用にoggへの変換も自動で行います。作譜の音取りがしやすくなるかもしれません。

## [ChroMapper-ColorPresetManager](https://github.com/rynan4818/ChroMapper-ColorPresetManager)
ChroMapperで、Chromaカラーのプリセットを切り替えられるようになるプラグイン

## [ChroMapper-MultiDisplayWindow](https://github.com/rynan4818/ChroMapper-MultiDisplayWindow)
ChroMapperで、マルチディスプレイ環境の時にマルチウィンドウで複数カメラで表示するプラグインです。

<img src="https://user-images.githubusercontent.com/14249877/171408555-26aa9a59-d6be-4c33-91fb-fcdeea42f00d.png" width="696" hight="594">

## [ChroMapper-RhythmMarker](https://github.com/rynan4818/ChroMapper-RhythmMarker)
ChroMapperで、グリッド上に拍子毎など一定間隔で色付きのラインマークを作成します。

<img src="https://user-images.githubusercontent.com/14249877/193462676-37273fc4-e85d-4b76-b74d-76fea864661f.png" width="696" hight="430">

## [ChroMapper-SettingTweaks](https://github.com/rynan4818/ChroMapper-SettingTweaks)
ChroMapperの変更できない設定を変更する、ちょっとしたプラグインです。

## [ChroMapper-VRMAvatar](https://github.com/rynan4818/ChroMapper-VRMAvatar)
ChroMapperでVRMアバターファイルを読み込んで表示するプラグインです。

## [MediocreMapAssistant2 修正版・日本語版](https://github.com/rynan4818/MediocreMapAssistant2/releases)
作譜ツールのMMA2の英語版の機能修正および主要部分の日本語化したものです。

<img src="https://user-images.githubusercontent.com/14249877/151654488-ede844d5-2d05-4b24-9bb8-3ebbbdcf1d65.gif" width="640" height="376">

# その他BeatSaber用mod
## [PlayerInfoViewer](https://github.com/rynan4818/PlayerInfoViewer)
ScoreSaberのプレイヤー情報のうちScoreSaber modで表示されない項目を追加表示するBeatSaber mod

<img src="https://user-images.githubusercontent.com/14249877/193413697-f5aadd39-aef8-40b5-a3af-59a03a7f320c.png" width="640" height="270">

## [KosorenTool](https://github.com/rynan4818/KosorenTool)
ScoreSaberなどのオンラインリーダーボードにスコアを送信せずにプレイをするためのBeatSaber mod

<img src="https://github.com/rynan4818/KosorenTool/assets/14249877/16c6f34c-4203-4c49-82bb-70e5131395da" width="656" height="400">

## [BSAlarmClock](https://github.com/rynan4818/BSAlarmClock)
自由に移動可能なタイマー・アラーム付き時計です。メニューとプレイ画面で別々に位置・表示・アラーム音有無が設定可能です。

![image](https://github.com/rynan4818/rynan4818.github.io/assets/14249877/a55e074c-46d3-4445-9269-8b88c0ccda48)

## [StagePositionViewer](https://github.com/rynan4818/StagePositionViewer)
ステージ上のプレイヤー(HMD)の位置をグラフィカルに表示するBeatSaber mod

![image](https://user-images.githubusercontent.com/14249877/210227621-3b5585ab-e77a-4067-850e-004ba6ac95be.png)

## [CutSpeedCounter](https://github.com/rynan4818/CutSpeedCounter)
ノーツカットのスピードを表示するCounters+用カスタムカウンター

<img src="https://user-images.githubusercontent.com/14249877/138584495-2aabd12c-4c3a-4d63-9434-197015fdd0ab.png" width="200" height="121">

## [HDTCounter](https://github.com/rynan4818/HDTCounter)
HeadDistanceTravelledのHMD移動距離を表示するCounters+用カスタムカウンター

![image](https://user-images.githubusercontent.com/14249877/172158178-c825414b-6bc0-41b4-8ea5-7851f0afc8dd.png)

## [CO2CounterStatus](https://github.com/rynan4818/CO2CounterStatus)
I/O DATA製のUD-CO2Sを使って、二酸化炭素濃度と温度と湿度を表示するCounters+用のカスタムカウンターと、HttpSiraStatusを使用したオーバーレイ表示、PlayerInfoViewer表示

![image](https://user-images.githubusercontent.com/14249877/219855750-6605731c-b134-46a0-9594-ea347817b993.png)

## [Camera2TransparencyPatch](https://github.com/rynan4818/Camera2TransparencyPatch)
Camera2のEFFECTSのTransparencyで最小でも10%は透過してしまうのを透過させない様にするパッチ。アバターのオーバーレイ表示用。

# その他BeatSaber用ツール
## [SubSongFolderSetting](https://github.com/rynan4818/SubSongFolderSetting)
BeatSaberのカスタムソングフォルダを追加する設定ツール

<img src="https://rynan4818.github.io/SubSongFolderSetting.png" width="447" height="355">

## [bs-mapdown-assistant](https://github.com/rynan4818/bs-mapdown-assistant)
BeatSaverからOneClickでダウンロードする時に指定プレイリストの末尾にダウンロードした譜面を追加するツール

## [onesaber_convert](https://github.com/rynan4818/onesaber_convert)
BeatSaberの譜面をOneSaber化するツール

## [BeatSaberのWebサイトで使えるブックマークレット](https://github.com/rynan4818/BSBookmarklet)
- BeatSaverのAlertsのリストをBeatSaberのプレイリストとして保存するブックマークレット
- 選択もしくは入力されたbsrのbeatsaverの譜面ページに飛ぶブックマークレット

## [PlayListTOOL](https://github.com/rynan4818/PlayListTool)
ScoreSaberの指定ユーザのTopやRecentのスコア一覧をプレイリスト化します。
また、GoogleスプレッドシートやEXCELを使用してBeatSaberのプレイリストの編集を支援する機能もあります。

<img src="https://user-images.githubusercontent.com/14249877/149654844-5f67b7f3-71cc-4a93-9619-4cba55582361.png" width="589" height="529">

## [SongData2CSV](https://drive.google.com/drive/folders/1e2ccPTAIbXYL9KE6paUGcvSud_t35WGU?usp=sharing)
SongDataCoreのデータベースをCSV化するツール

id, key, downloadCount, upVotes, downVotes, heat, rating, automapper, uploaddate, pp, star,	diff, type, len, njs, bmb, nts, obs
の全難易度毎のリストが取得できます

## [Camera2GUI](https://github.com/rynan4818/Camera2GUI)
[Camera2](https://github.com/kinsi55/CS_BeatSaber_Camera2)のGUI設定ツール

<img src="https://rynan4818.github.io/camera2gui1.png" width="403" height="448">

# BeatSaber関係サイト
## [ScoreSaberの各種ランキング](https://github.com/rynan4818/ScoreSaberRanking/blob/master/README.md#scoresaber%E3%81%AE%E5%90%84%E7%A8%AE%E3%83%A9%E3%83%B3%E3%82%AD%E3%83%B3%E3%82%B0)
ScoreSaberのプレイカウントなどによるランキング(自動更新)

<img src="https://user-images.githubusercontent.com/14249877/148824145-4a1fedbc-051a-47d9-a9b5-1f97c7ac4a75.png" width="550" height="214">

## [ScoreSaberの各種データのグラフ・テーブル表示](https://beatsaber.rynan.com/scoresaber/)
ScoreSaberグローバル20000位以内の2019/11/10以降の各種データをグラフ表示・テーブル表示するサイト

<img src="https://github.com/rynan4818/rynan4818.github.io/assets/14249877/7f5961ab-733f-4924-b6ed-642c70ac09a6" width="444" height="276">
<img src="https://github.com/rynan4818/rynan4818.github.io/assets/14249877/7daac0cc-82e1-4891-bb10-ab05d7d31b79" width="444" height="276">

## [BeatSaberの譜面作成方法](https://note.com/rynan/n/nc899b58987c9)
ツールではありませんが、作譜をやってみて調べた内容でnoteの記事を書きました。

## [Quest2でBeatSaberを始めた人が、PC版でアバター表示のプレイ録画するまで](https://note.com/rynan/n/na2e0a6925892)
こちらはQuest2でBeatSaberを始めた人向けのnote記事です。

# 開発用ツール
## [Beat Saber HTTP Status Checker](https://rynan4818.github.io/http_status_check.html)
HTTPStatsuから飛んでくるJSONを確認するツール(HTTPStatusを使ったオーバーレイなどの開発者向け)

## [Beat Saber HTTP Status Checker2](https://rynan4818.github.io/http_status_check2.html)
選択したアイテムを１イベント１行で表示するバージョン

## [ChroMapperPluginTemplates](https://github.com/rynan4818/ChroMapperPluginTemplates)
ChroMapperのプラグインを作る時のVisualStudio用テンプレートです。

## [BSIPA-PluginTemplates](https://github.com/rynan4818/BSIPA-PluginTemplates)
BeatSaberのMod作成用のVisualStudio用テンプレートです。

## [BeatSaber mod製作参考](https://github.com/rynan4818/rynan4818.github.io/wiki/BeatSaber-mod%E8%A3%BD%E4%BD%9C%E5%8F%82%E8%80%83)
私のBeatSaberのmod製作経験上の得た知識のリンクメモです。
