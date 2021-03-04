# ESCFontProject  
EnhancedStreamChat向けフォント作成プロジェクトです。
# Font Assetの作り方  
1.Assets/FontFileに.ttfなり.otfなりのフォントファイルをドラッグアンドドロップします。  
![image](https://user-images.githubusercontent.com/55026301/106466823-2d929d80-64df-11eb-958a-19c9732d8b5d.png)  
  
2.入れたフォントを右クリックして「Create->Text Mesh Pro->Font Asset」をクリック
![image](https://user-images.githubusercontent.com/55026301/106466970-5fa3ff80-64df-11eb-9123-42bdc4f2a4d5.png)  
  
3.できたフォントアセットをクリックしてInspectorの「Update Atlas Textuer」をクリック  
![image](https://user-images.githubusercontent.com/55026301/106468141-e6a5a780-64e0-11eb-9447-8c5548979da0.png)  
  
4.FontAssetCreatorにてSource Font File以外を同じ値にします。  
![image](https://user-images.githubusercontent.com/55026301/106468664-9549e800-64e1-11eb-8715-5724451f348c.png)  
  
  
5.InspectorのGenerationSettingsにあるAtlas Population ModeをStaticに変更します。  
![image](https://user-images.githubusercontent.com/55026301/109971874-0a574a00-7d3a-11eb-8f6d-0a3ba9809c32.png)
  
6.Generate Font Atlasを押してお茶と饅頭を用意してまったりしてください。  
7.Saveを押して完成。  
  
# Asset Bundleの作り方  
※Asset Bundle BrowserがツールバーのWindowにない人はPackageManagerから検索してInstallポチってください  
![image](https://user-images.githubusercontent.com/55026301/106469260-6aac5f00-64e2-11eb-9ea0-ff1a9b6b8d8e.png)  
![image](https://user-images.githubusercontent.com/55026301/106469307-7861e480-64e2-11eb-83bc-5f836342a20d.png)  
  
1.Window->Asset Bundle BrowserのConfigureに作ったFont Assetをドラッグアンドドロップします。  
![image](https://user-images.githubusercontent.com/55026301/106469601-d68ec780-64e2-11eb-8f2f-d2ed9d99a1a6.png)  
  
2.名前の最後に.assetを書きます。するとassetsが子になります。  
![image](https://user-images.githubusercontent.com/55026301/106469768-0dfd7400-64e3-11eb-8417-144e3bc51291.png)  
  
3.BuildタブでBuildを押すと自動でパッケージにしてくれます。  
![image](https://user-images.githubusercontent.com/55026301/106470498-e0fd9100-64e3-11eb-9e4d-345411e0421d.png)  
  
4.なんかいろいろ作られますが、.assetsだけしか使いません。それをBeatSaberインストールフォルダのUserData\FontAssets\Mainにほうりこんで終わりです。  
![image](https://user-images.githubusercontent.com/55026301/106470696-25892c80-64e4-11eb-9420-b5b416fd0178.png)
