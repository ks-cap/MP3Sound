# MP3Sound
## リモコンを用いたMP3ファイルを再生（ライブラリでMP3PlayerShieldを利用
・librarysにSFEMP3Shieldを利用  
・赤外線受信モジュール接続ピン番号を5番  
・受信したデータから読取る内容のデータ位置は3番目   
・10種類の音声を出力（0~9のボタンを利用）、仮として決定ボタンは停止処理のみ  
・音量をsetup()にて0x00と定義（聞こえやすい音量としている）
