# SAMEGA TIDE

## 日本語

### 概要

SAMEGA TIDE は、さめがめ型のパズルゲームを PC とスマートフォンで遊べるように設計した、単一ファイル形式のゲームです。

この README は、同じフォルダ内の index.html で動く SAMEGA TIDE のための説明書です。

### ファイル構成

- index.html: ゲーム本体
- README.md: 説明書

### 遊び方

1. index.html をブラウザで開くと、ゲームが始まります。
2. 同じ色で2つ以上つながったブロックを選択して、消していくゲームです。
3. 大きく消すほど高得点になります。
4. 消したブロックの上にあるブロックは、下へ落ちます。
5. 空になった列は、左へ詰められます。
6. すべてのブロックを消すと、オールクリアボーナスが得られます。

### 操作

スマートフォン・タブレット向け:

1. 同じ色で2つ以上つながったブロックをタップします。
2. 選択されたブロックが強調表示されます。
3. 同じグループをもう一度タップすると、そのブロックが消えます。

PC向け:

1. 同じ色で2つ以上つながったグループにマウスを合わせると、そのグループが強調表示されます。
2. 一度クリックすると、そのブロックが消えます。

### 画面上のボタン

- 新しいゲーム: 現在のゲームを始めて、新しい盤面を作成します。
- サウンド ON / OFF: ゲーム中の効果音を開始または停止します。
- 保存消去: このブラウザに保存されたハイスコアと、保存中のゲームデータを消去します。
- 言語: 表示言語を変更します。
- 難易度: やさしい、ふつう、むずかしいから選べます。

### 難易度

- やさしい: 3色で遊べます。
- ふつう: 4色で遊べます。
- むずかしい: 5色で遊べます。

### スコア

2つ以上つながった同じ色のブロックを消すと、スコアが増えます。

大きなブロックを消すほど、スコアが高くなります。

すべてのブロックを消すと、ボーナスが入ります。

ハイスコアは、難易度ごとに保存されます。

### 多言語対応

このゲームは、次の言語に対応しています。

- 日本語
- English
- 简体中文
- 한국어
- Español

画面内の言語は、言語選択メニューから変更できます。

### セーブデータ

ゲームデータはこの端末のブラウザ内部に自動保存されます。

保存される情報:

- 選択中の言語
- サウンド設定
- 選択中の難易度
- 各難易度のハイスコア
- 途中で中断したゲームの盤面とスコア

保存は、このブラウザと同じ端末、同じブラウザ、同じブラウザ設定でのみ復元できます。

シークレットモードや、サイト内の保存機能がブロックされている環境では、保存できなかったり、保存されても次回に復元できないことがあります。

### ローカル保存が動かないとき

一部のブラウザでは、ファイル名 index.html を直接開いただけでは保存機能が使えません。

その場合は、次のことをお試しください。

1. 同じブラウザで開き直してください。
2. シークレットモードを解除してください。
3. ブラウザのサイトデータ保存許可を確認してください。
4. 別のブラウザでお試しください。
5. ローカルサーバーや静的サイトホスティングで開いてください。

### 画面表示について

このゲームは、スマホでの操作を前提に縦長画面に収まるように作られています。

スマホ、タブレット、PCのブラウザ画面に合わせて、盤面サイズが自動的に調整されます。

### サウンド

サウンドボタンを押すと、効果音が切り替わります。

効果音はブラウザ内だけで合成される音です。

外部の音源ファイルは使いません。

### 動作確認

最近の主なブラウザで動くように作られています。

推奨環境:

- PC: Chrome, Firefox, Edge, Safari などの最近のブラウザ
- Android: 最近の Chrome, Firefox
- iPhone / iPad: 最近の Safari

古いブラウザでは、一部の機能が使えない場合があります。

### トラブル

ゲームが消去される、ハイスコアが消える、言語が変わらないなどの問題がある場合は、次の原因が考えられます。

- ブラウザのサイトデータが消去された。
- 別のブラウザや別の端末で開いた。
- シークレットモードで開いている。
- ブラウザの保存機能がブロックされている。
- ファイルを移動して、別の保存領域として読み込まれた。

---

## English

### Overview

SAMEGA TIDE is a SameGame-style puzzle game for PC and smartphone, packaged as a single HTML file.

This README explains how to use the SAMEGA TIDE game located at index.html in the same folder.

### File structure

- index.html: the game itself
- README.md: this guide

### How to play

1. Open index.html in a browser to start the game.
2. Select groups of two or more connected blocks of the same color.
3. Remove blocks to earn score.
4. Blocks above removed blocks fall downward.
5. Empty columns shift left.
6. Clearing all blocks gives an all-clear bonus.

### Controls

For smartphones and tablets:

1. Tap a group of two or more connected same-colored blocks.
2. The selected group is highlighted.
3. Tap the same group again to remove it.

For PC:

1. Move the mouse pointer over a group of two or more connected same-colored blocks.
2. The group is highlighted.
3. Click once to remove it.

### Interface buttons

- New Game: start a new game and create a new board.
- Sound ON / OFF: turn game sound effects on or off.
- Clear Save: erase saved high scores and any saved game state in this browser.
- Language: change the interface language.
- Difficulty: choose Easy, Normal, or Hard.

### Difficulty

- Easy: 3 colors
- Normal: 4 colors
- Hard: 5 colors

### Score

Removing a group of two or more connected same-colored blocks increases your score.

Larger groups give much higher scores.

Clearing all blocks gives a bonus.

High scores are saved separately for each difficulty.

### Languages

The game supports these languages:

- Japanese
- English
- Simplified Chinese
- Korean
- Spanish

The interface language can be changed from the language selector.

### Local save data

Game data is saved automatically inside this browser.

Saved data includes:

- Interface language
- Sound setting
- Selected difficulty
- High score for each difficulty
- The current game board and score, if the game was left unfinished

Saved data can only be restored in the same browser on the same device.

In private mode, or if browser storage is blocked, the game may not save, or saved data may not be restored next time.

### If saving does not work

Some browsers restrict storage when index.html is opened directly as a local file.

If saving does not work, try:

1. Reopen the game in the same browser.
2. Turn off private or incognito mode.
3. Allow site data storage in the browser settings.
4. Try another browser.
5. Use a local server or static hosting.

### Display layout

The game is designed to fit a portrait-style screen, mainly for mobile use.

The board size automatically adapts to smartphone, tablet, and PC browser windows.

### Sound

Press the sound button to enable or disable sound effects.

Sound effects are synthesized inside the browser.

No external sound files are used.

### Compatibility

The game is made to work in recent browsers.

Recommended:

- PC: recent Chrome, Firefox, Edge, or Safari
- Android: recent Chrome or Firefox
- iPhone / iPad: recent Safari

Older browsers may not support all features.

### Troubleshooting

If the game disappears, high scores disappear, or the language does not change, possible causes include:

- Browser site data was deleted.
- The game was opened in another browser or on another device.
- Private or incognito mode is being used.
- Browser storage is blocked.
- The file was moved to a different location and is being treated as a separate app origin.

---

## 简体中文

### 概述

SAMEGA TIDE 是一个可在 PC 和手机上游玩的同色消除型拼图游戏，以单个 HTML 文件形式运行。

本 README 用于说明同一文件夹中 index.html 对应的游戏。

### 文件结构

- index.html: 游戏本体
- README.md: 说明文档

### 玩法

1. 在浏览器中打开 index.html，游戏开始。
2. 选择两个或更多相邻连接的同色方块。
3. 消除方块以获得分数。
4. 上方方块会下落。
5. 空列会向左移动。
6. 消除全部方块会获得全清奖励。

### 操作

手机 / 平板:

1. 点按一组两个或更多相邻连接的同色方块。
2. 所选方块组会被高亮。
3. 再次点按同一组即可消除。

PC:

1. 将鼠标移到一组两个或更多相邻连接的同色方块上。
2. 该组会高亮。
3. 单击一次即可消除。

### 界面按钮

- 新游戏: 开始新游戏并生成新盘面。
- 音效开/关: 开启或关闭游戏音效。
- 清除存档: 删除当前浏览器中保存的最高分与未结束游戏数据。
- 语言: 切换界面语言。
- 难度: 选择简单、普通或困难。

### 难度

- 简单: 3种颜色
- 普通: 4种颜色
- 困难: 5种颜色

### 分数

消除两个或更多相邻连接的同色方块会增加分数。

消除更多方块会获得更高分数。

消除全部方块会获得奖励。

最高分会按不同难度分别保存。

### 多语言支持

游戏支持以下语言:

- 日语
- 英语
- 简体中文
- 韩语
- 西班牙语

界面语言可通过语言选择菜单切换。

### 本地存档

游戏数据会自动保存在当前浏览器内部。

保存的数据包括:

- 界面语言
- 音效设置
- 当前难度
- 各难度最高分
- 如果游戏未结束，则包括当前盘面和分数

存档只能在同一设备的同一浏览器中恢复。

在无痕模式或浏览器存储被阻止时，可能无法保存，或下次无法恢复。

### 如果无法保存

某些浏览器直接打开本地文件时会限制存储。

如果无法保存，请尝试:

1. 在同一个浏览器中重新打开。
2. 退出无痕或隐身模式。
3. 允许浏览器保存网站数据。
4. 尝试其他浏览器。
5. 使用本地服务器或静态托管。

### 画面显示

本游戏以竖屏布局为基本设计，适合手机游玩。

盘面大小会根据手机、平板和 PC 浏览器窗口自动调整。

### 音效

点击音效按钮可开启或关闭音效。

音效由浏览器内部合成。

不使用外部音频文件。

### 兼容性

游戏面向近期浏览器设计。

推荐:

- PC: 近期 Chrome、Firefox、Edge、Safari
- Android: 近期 Chrome 或 Firefox
- iPhone / iPad: 近期 Safari

旧浏览器可能不支持部分功能。

### 故障排除

如果游戏消失、最高分消失或语言未变化，可能原因包括:

- 浏览器网站数据已被删除。
- 使用了其他浏览器或其他设备。
- 正在使用无痕或隐身模式。
- 浏览器存储被阻止。
- 文件被移动到不同位置，被视为不同应用来源。

---

## 한국어

### 개요

SAMEGA TIDE는 PC와 스마트폰에서 즐길 수 있는 같은 색 블록 소거형 퍼즐 게임이며, 단일 HTML 파일 형태로 동작합니다.

이 README는 같은 폴더의 index.html에서 실행되는 SAMEGA TIDE를 설명합니다.

### 파일 구성

- index.html: 게임 본체
- README.md: 설명서

### 게임 방법

1. 브라우저에서 index.html을 열면 게임이 시작됩니다.
2. 같은 색으로 2개 이상 연결된 블록 그룹을 선택합니다.
3. 블록을 제거하여 점수를 얻습니다.
4. 제거된 블록 위의 블록은 아래로 떨어집니다.
5. 빈 열은 왼쪽으로 이동합니다.
6. 모든 블록을 제거하면 전체 클리어 보너스를 받습니다.

### 조작

스마트폰 / 태블릿:

1. 같은 색으로 2개 이상 연결된 블록 그룹을 탭합니다.
2. 선택된 그룹이 강조됩니다.
3. 같은 그룹을 한 번 더 탭하면 제거됩니다.

PC:

1. 같은 색으로 2개 이상 연결된 그룹에 마우스를 올립니다.
2. 그룹이 강조됩니다.
3. 한 번 클릭하면 제거됩니다.

### 화면 버튼

- 새 게임: 새 게임을 시작하고 새 보드를 생성합니다.
- 소리 켜짐 / 꺼짐: 게임 효과를 켜거나 끄는 버튼입니다.
- 저장 삭제: 이 브라우저에 저장된 최고 점수와 저장된 게임 데이터를 삭제합니다.
- 언어: 인터페이스 언어를 변경합니다.
- 난이도: 쉬움, 보통, 어려움 중 하나를 선택합니다.

### 난이도

- 쉬움: 3색
- 보통: 4색
- 어려움: 5색

### 점수

2개 이상 연결된 같은 색 블록을 제거하면 점수가 증가합니다.

더 큰 그룹을 제거하면 더 높은 점수를 얻습니다.

모든 블록을 제거하면 보너스를 받습니다.

최고 점수는 난이도별로 저장됩니다.

### 다국어 지원

다음 언어를 지원합니다.

- 일본어
- 영어
- 중국어 간체
- 한국어
- 스페인어

언어 선택 메뉴에서 인터페이스 언어를 변경할 수 있습니다.

### 로컬 저장 데이터

게임 데이터는 현재 브라우저 내부에 자동 저장됩니다.

저장되는 정보:

- 인터페이스 언어
- 소리 설정
- 선택한 난이도
- 난이도별 최고 점수
- 게임이 끝나지 않은 경우 보드와 점수

저장 데이터는 같은 기기, 같은 브라우저에서만 복원됩니다.

시크릿 모드나 브라우저 저장 기능이 차단된 환경에서는 저장되지 않거나 다음 실행 시 복원되지 않을 수 있습니다.

### 저장이 되지 않을 때

일부 브라우저에서는 index.html을 파일로 직접 열었을 때 저장이 제한될 수 있습니다.

저장이 되지 않으면:

1. 같은 브라우저에서 다시 열어 보세요.
2. 시크릿 또는 시크릿 browsing 모드를 해제하세요.
3. 브라우저의 사이트 데이터 저장을 허용하세요.
4. 다른 브라우저에서 실행해 보세요.
5. 로컬 서버 또는 정적 호스팅을 이용하세요.

### 화면 표시

이 게임은 스마트폰 사용을 중심으로 세로 화면에 맞게 설계되었습니다.

보드 크기는 스마트폰, 태블릿, PC 브라우저 화면에 자동으로 조정됩니다.

### 소리

소리 버튼을 눌러 게임 효과음을 켜거나 끌 수 있습니다.

효과음은 브라우저 내부에서 생성됩니다.

외부 오디오 파일은 사용하지 않습니다.

### 동작 환경

최근 브라우저에서 동작하도록 만들었습니다.

권장:

- PC: 최근 Chrome, Firefox, Edge, Safari
- Android: 최근 Chrome 또는 Firefox
- iPhone / iPad: 최근 Safari

오래된 브라우저에서는 일부 기능이 동작하지 않을 수 있습니다.

### 문제 해결

게임이 사라지거나, 최고 점수가 사라지거나, 언어가 변경되지 않는 경우의 원인은 다음과 같습니다.

- 브라우저 사이트 데이터가 삭제됨
- 다른 브라우저 또는 다른 기기에서 실행됨
- 시크릿 모드 사용
- 브라우저 저장 기능이 차단됨
- 파일을 다른 위치로 이동해 다른 앱 출처로 인식됨

---

## Español

### Resumen

SAMEGA TIDE es un juego de puzzle estilo SameGame para PC y smartphone, creado como un único archivo HTML.

Este README explica cómo usar el juego SAMEGA TIDE que se encuentra en index.html dentro de la misma carpeta.

### Estructura de archivos

- index.html: el juego
- README.md: esta guía

### Cómo jugar

1. Abre index.html en un navegador para iniciar el juego.
2. Selecciona grupos de dos o más bloques conectados del mismo color.
3. Elimina bloques para obtener puntos.
4. Los bloques superiores caen hacia abajo.
5. Las columnas vacías se desplazan hacia la izquierda.
6. Si eliminas todos los bloques, obtienes un bonus de limpieza total.

### Controles

Para smartphones y tablets:

1. Toca un grupo de dos o más bloques conectados del mismo color.
2. El grupo seleccionado se resalta.
3. Vuelve a tocar el mismo grupo para eliminarlo.

Para PC:

1. Coloca el puntero sobre un grupo de dos o más bloques conectados del mismo color.
2. El grupo se resalta.
3. Haz clic una vez para eliminarlo.

### Botones de la interfaz

- Nuevo juego: inicia una nueva partida y crea un nuevo tablero.
- Sonido ON / OFF: activa o desactiva los efectos de sonido.
- Borrar guardado: elimina las mejores puntuaciones y el estado guardado en este navegador.
- Idioma: cambia el idioma de la interfaz.
- Dificultad: elige Fácil, Normal o Difícil.

### Dificultad

- Fácil: 3 colores
- Normal: 4 colores
- Difícil: 5 colores

### Puntuación

Eliminar grupos de dos o más bloques conectados del mismo color aumenta la puntuación.

Los grupos más grandes otorgan muchos más puntos.

Eliminar todos los bloques otorga un bonus.

Las mejores puntuaciones se guardan por separado para cada dificultad.

### Idiomas

El juego admite estos idiomas:

- Japonés
- Inglés
- Chino simplificado
- Coreano
- Español

El idioma de la interfaz puede cambiarse desde el selector de idioma.

### Guardado local

Los datos del juego se guardan automáticamente dentro de este navegador.

Los datos guardados incluyen:

- Idioma de la interfaz
- Configuración de sonido
- Dificultad seleccionada
- Mejor puntuación por dificultad
- El tablero y la puntuación actual si la partida no terminó

Los datos guardados solo pueden restaurarse en el mismo navegador del mismo dispositivo.

En modo privado o si el almacenamiento del navegador está bloqueado, el juego puede no guardar, o los datos pueden no restaurarse la próxima vez.

### Si no se guarda

Algunos navegadores restringen el almacenamiento cuando index.html se abre directamente como archivo local.

Si el guardado no funciona, intenta:

1. Reabrir el juego en el mismo navegador.
2. Desactivar el modo privado o incógnito.
3. Permitir el almacenamiento de datos del sitio en el navegador.
4. Probar otro navegador.
5. Usar un servidor local o alojamiento estático.

### Diseño de pantalla

El juego está diseñado para ajustarse a una pantalla vertical, especialmente para móviles.

El tamaño del tablero se adapta automáticamente a smartphones, tablets y ventanas de PC.

### Sonido

Usa el botón de sonido para activar o desactivar los efectos de sonido.

Los efectos de sonido se generan dentro del navegador.

No se usan archivos de sonido externos.

### Compatibilidad

El juego está hecho para funcionar en navegadores recientes.

Recomendado:

- PC: Chrome, Firefox, Edge o Safari recientes
- Android: Chrome o Firefox recientes
- iPhone / iPad: Safari reciente

Los navegadores antiguos pueden no soportar todas las funciones.

### Problemas

Si el juego desaparece, las mejores puntuaciones desaparecen o el idioma no cambia, las causas posibles incluyen:

- Los datos del sitio del navegador fueron borrados.
- El juego se abrió en otro navegador o dispositivo.
- Se está usando modo privado o incógnito.
- El almacenamiento del navegador está bloqueado.
- El archivo fue movido a otra ubicación y se interpreta como un origen diferente.