# レベルシステム

キャラクターの解放と、ランダムピック時の出現確率調節に関わるシステム

## キャラクターのレベリング

- GM, PL どちらで遊んでも 2 のマナ結晶を得る。自身を含み初心者が卓に存在した場合は 5 のマナ結晶を得る。
- 所持中のキャラクターに使用するとレベルを上昇させられる
- レベルが上昇したキャラは [1 ~ 現在レベル] まで出現確率を調節できる

### 経験値テーブル

- 必要マナ結晶 = 現在のレベル * min( 現在のレベル - 5, 1 ) 
- 5 の値を上げることで将来的に緩和する

### レベル上限

- 所持キャラクター数 * 2
- キャラクターを解放することで特定のキャラが出にくくなる事象の緩和

### 出現確率

- キャラクターの出現頻度は [1 ~ 現在のレベル] の間で調節できる（出現補正）
- 出現確率 = 出現補正 / 所持キャラクターの出現補正合計