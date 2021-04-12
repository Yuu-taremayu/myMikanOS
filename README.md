# Mikan OS
 - This is self-made OS

# Environment
 - Arch linux 5.11.8
	 - って思ったけど環境構築がしんどいのでVirtualBox6.1.18+Ubuntu20.04でやる

## Read chapters
0. 4/1(同日読了)
	 - OS自作のモチベーションや全体像　低レイヤは実際に触ったことがほぼないのでわくわく

1. 4/4(同日読了)
	 - バイナリエディタでhello, worldを出力する実行ファイルを作った
		 - バイナリエディタは初めてだったし面白かった
		 - この環境ではqemuで作ったディスクイメージがマウントできなかった(Operation not permittedで)
		 - linuxのカーネルによってmountできるファイルシステムのタイプが違う...?
		 - サーバかラズパイかなんかで動かすか...
	 - CS初学者に向けた細かい説明もあってすごい
	 - OSが起動するまでの基礎知識　概要を掴むにはいい感じ
	 - 実行ファイルの動作確認できた(4/8)

2. 4/8~13(だいたい)
	 - EDKⅡ入門、正直用意されたシェルスクリプトを走らせたりしただけで、中身についてあまり理解できていない
	 - メモリマップあたりと、それに伴ってポインタの話
		 - ポインタは改めて勉強できてよかった、手動かして身につけたい
