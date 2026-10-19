# 人工植牙有聲互動簡報

開啟 `index.html` 可使用自含版本（不需連網）。建議 Chrome / Edge / Safari。
按左右方向鍵換頁，點「播放本頁旁白」。重播、速度、逐字稿、章節跳轉均在下方。
可重播每頁動畫，音訊可播放與暫停。音檔為 HsiaoChen 台灣國語合成音。

`啟動簡報.command` 可啟動本機伺服器並開啟簡報。另可透過同一伺服器開啟 `hyperframes.html`，使用內建 Present 講者模式。音訊在講者端播放；遠距分享需勾選分享分頁音訊。
`composition/index.html` 為 HyperFrames 原始動畫，`slides.json` 是可編輯的旁白與內容來源。

醫療使用：一般衛教，不含診所識別。請依診所實際流程確認個別指示。完整官方連結見「旁白稿與來源.md」。

單檔 index.html 已內嵌圖片、語音與動畫程式，可獨立複製使用。
內容來源為 content.json，重建指令：python3 scripts/build.py。旁白文字或醫療內容更新時，請同步重製對應音檔。
