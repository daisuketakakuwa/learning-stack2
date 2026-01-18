## システム と ソフト のちがい
・システムは「ソフト(アプリ＋ネットワーク＋インフラ」もろもろ込で構成されている。<br>
・設計観点だと<br>
　-> ソフト単体でおさまる設計 -> `architecture/software`<br>
　-> システム全体に跨ぐような設計 -> `architecture/database`<br>
<br>

・「レイヤードアーキテクチャ」のような アプリ(SpringBoot)内に閉じた設計の話なら `architecture/software`<br>
・データベースのような、他の要素も絡んでくる話なら `architecture/system`<br>
