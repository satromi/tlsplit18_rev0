# TL Split Keyboard 18mm Rev0紹介

## はじめに
TL Split Keyboard 18mmは、TRONキーボードを参考にしたキーボードです。
Cherry MXキーが使えるよう、オリジナルのTRONキーボードLサイズと同じ18mmピッチで作られています。

## 配列
72キーなので、ファンクションキーやテンキーは、"TG"キーでファンクション面に切替えて使います。
入門しやすさを重視し、QWERTY配列とDVORAK配列を用意としています。本来あるべき、TRON配列については準備中です。
TRONキーボードは、左右シフトを使い分けることで括弧の開く、閉じるを同じキーで入力することができますが、
現状のQWERTY/DVORAK配列は通常のキーボードからの移行のしやすさを重視して、左右シフトの使い分けには対応していません。
※希望が増えたら対応します。

### QWERTY配列（tlsplit18_default.hex）

- QWERTY配列面

~~~
        ,-----------------------------------------.              ,-----------------------------------------.
        |   [  |   1  |   2  |   3  |   4  |   5  |              |   6  |   7  |   8  |   9  |   0  |   -  |
 ,------+------+------+------+------+------+------+------.,------+------+------+------+------+------+------+------.
 |  ESC | CTRL |   Q  |   W  |   E  |   R  |   T  |  DEL ||  INS |   Y  |   U  |   I  |   O  |   P  |   @  | YEN| |
 |------+------+------+------+------+------+------+------||------+------+------+------+------+------+------+------|
 |  HNK |  ALT |   A  |   S  |   D  |   F  |   G  |  TAB ||  ENT |   H  |   J  |   K  |   L  |   ;  |   :  |   ~  |
 `------+------+------+------+------+------+------+------'`------+------+------+------+------+------+------+------'
        |   ]  |   Z  |   X  |   C  |   V  |   B  |              |   N  |   M  |   ,  |   .  |   /  |   \  |
        `-----------------------------------------'              `-----------------------------------------'
               ,------.      ,---------------------------.,---------------------------.      ,------.
               | PGUP |      |  SPC |  SFT |   TG |  CPS ||   JP |  HNK |  SFT |  BSP |      |   UP |
        +------+------+------+---------------------------'`---------------------------+------+------+------+
        | HOME | PGDN |  END |                                                        |  LFT |  DWN |  RGT |
        `--------------------'                                                        `--------------------'
~~~

- ファンクション面

ファンクション面の空白箇所は、キー割り当てがありません。

~~~
        ,-----------------------------------------.              ,-----------------------------------------.
        |      |   F1 |   F2 |   F3 |   F4 |   F5 |              |   F6 |   F7 |   F8 |   F9 |  F10 |    * |
 ,------+------+------+------+------+------+------+------.,------+------+------+------+------+------+------+------.
 |  ESC | CTRL |      |      |      |      |      |  DEL ||    = |    . |    7 |    8 |    9 |    / |    - |  F11 |
 |------+------+------+------+------+------+------+------||------+------+------+------+------+------+------+------|
 |  HNK |  ALT |      |      |      |      |      |  TAB ||  ENT |    , |    4 |    5 |    6 |    * |NUMLOC|  F12 |
 `------+------+------+------+------+------+------+------'`------+------+------+------+------+------+------+------'
        |      |      |      |      |      |      |              |    0 |    1 |    2 |    3 |    + |      |
        `-----------------------------------------'              `-----------------------------------------'
               ,------.      ,---------------------------.,---------------------------.      ,------.
               | PGUP |      |  SPC |  SFT |   TG |  CPS ||   JP |  HNK |  SFT |  BSP |      |   UP |
        +------+------+------+---------------------------'`---------------------------+------+------+------+
        | HOME | PGDN |  END |                                                        |  LFT |  DWN |  RGT |
        `--------------------'                                                        `--------------------'
~~~

### DVORAK配列（tlsplit18_dvorak.hex）
- DVORAK配列面

~~~
         ,-----------------------------------------.              ,-----------------------------------------.
        |   [  |   1  |   2  |   3  |   4  |   5  |              |   6  |   7  |   8  |   9  |   0  |   /  |
 ,------+------+------+------+------+------+------+------.,------+------+------+------+------+------+------+------.
 |   @  |   ]  |   ;  |   ,  |   .  |   P  |   Y  |  ESC ||  INS |   F  |   G  |   C  |   R  |   L  |   -  | YEN| |
 |------+------+------+------+------+------+------+------||------+------+------+------+------+------+------+------|
 |  HNK |  ALT |   A  |   O  |   E  |   U  |   I  |  TAB ||  ENT |   D  |   H  |   T  |   N  |   S  |   :  |  DEL |
 `------+------+------+------+------+------+------+------'`------+------+------+------+------+------+------+------'
        | CTRL |   ~  |   Q  |   J  |   K  |   X  |              |   B  |   M  |   W  |   V  |   Z  |   \  |
        `-----------------------------------------'              `-----------------------------------------'
               ,------.      ,---------------------------.,---------------------------.      ,------.
               | PGUP |      |  SPC |  SFT |   TG |  CPS ||   JP |  HNK |  SFT |  BSP |      |   UP |
        +------+------+------+---------------------------'`---------------------------+------+------+------+
        | HOME | PGDN |  END |                                                        |  LFT |  DWN |  RGT |
        `--------------------'                                                        `--------------------'
~~~

- ファンクション面

ファンクション面の空白箇所は、キー割り当てがありません。

~~~
        ,-----------------------------------------.              ,-----------------------------------------.
        |      |   F1 |   F2 |   F3 |   F4 |   F5 |              |   F6 |   F7 |   F8 |   F9 |  F10 |    * |
 ,------+------+------+------+------+------+------+------.,------+------+------+------+------+------+------+------.
 |      | CTRL |      |      |      |      |      |  ESC ||    = |    . |    7 |    8 |    9 |    / |    - |      |
 |------+------+------+------+------+------+------+------||------+------+------+------+------+------+------+------|
 |  HNK |  ALT |      |      |      |      |      |  TAB ||  ENT |    , |    4 |    5 |    6 |    * |NUMLOC|  DEL |
 `------+------+------+------+------+------+------+------'`------+------+------+------+------+------+------+------'
        |      |      |      |      |      |      |              |    0 |    1 |    2 |    3 |    + |      |
        `-----------------------------------------'              `-----------------------------------------'
               ,------.      ,---------------------------.,---------------------------.      ,------.
               | PGUP |      |  SPC |  SFT |   TG |  CPS ||   JP |  HNK |  SFT |  BSP |      |   UP |
        +------+------+------+---------------------------'`---------------------------+------+------+------+
        | HOME | PGDN |  END |                                                        |  LFT |  DWN |  RGT |
        `--------------------'                                                        `--------------------'
~~~

ビルドガイドは、[buildguide.md](https://github.com/satromi/tlsplit18_rev0/blob/master/buildguide.md) を参照してください。