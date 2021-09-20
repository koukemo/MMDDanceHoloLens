# MMDDanceHoloLens

Unity | HoloLensでMMDモデルを利用する

## 環境

Unity 2019.4.18f1 <br>
HoloLens 2 <br>
MixedRealityToolkit 2.6.1 <br>
[MMD4Mecanim Beta 20200105](http://stereoarts.jp/) <br>

## 実行結果
[![YuniDanceDemo](http://img.youtube.com/vi/LBBoCagYCPk/0.jpg)](https://youtu.be/LBBoCagYCPk)

## 手順
1. [MMD4Mecanim Beta 20200105](http://stereoarts.jp/)をダウンロード
2. MMD4Mecanim.unitypackageをimport
3. モデルフォルダをProject viewにドラッグアンドドロップ
4. モデル名.MMD4Mecanimの規約に同意
5. アニメーションファイルを[VMD]にセットし[process]押下で変換 <br>
   正しく変換されれば、fbxが出力される <br>
6. fbxをHierarchy viewへ移動
7. モデルに[Animator]をAdd Component
8. Controller -> Tda に設定
9. Window > Animation > Animatorを開いて, Project viewモデル内のアニメーションファイルをドラッグアンドドロップ
10. Entry -> アニメーションファイル に設定
11. Unityの再生

## お借りしたもの

**好き！雪！本気マジック モーション** <br>
制作者 : hino様 <br>
download link : https://bowlroll.net/file/30993 <br>
動画 : https://www.nicovideo.jp/watch/sm23692832 <br>

**プリンセスコネクト！Re:Dive ユニMMDモデル** <br>
制作者 : ちづる様 <br>
download link : https://3d.nicovideo.jp/works/td68814 <br>
プリンセスコネクト！Re:Dive : https://priconne-redive.jp// <br>

## 参考

- 【[初心者向け】UnityでMMDモデルを動かす手順とコツ| MMD4Mecanim解説 - XR-HU3](https://xr-hub.com/archives/12978)
