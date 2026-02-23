### コンポーネントとは
UI の部品を表す再利用可能なコード。

### JSX要素とは
何を表示したいかを記述するための JavaScript コードと HTML タグの組み合わせ。

### onClickとhandleClick
- onClick -> イベント(webページ上で起きアクション)
- handleClick -> イベントハンドラ(イベントに応じて実行される処理)

https://ja.react.dev/learn/responding-to-events

> 慣習的に、イベントハンドラは handle の後ろにイベントの名称をつなげた名前にすることが一般的です。onClick={handleClick}、onMouseEnter={handleMouseEnter} などがよく見られます。

### state
状態を記憶するためのもの

### slice
https://developer.mozilla.org/ja/docs/Web/JavaScript/Reference/Global_Objects/Array/slice
> slice() は Array インスタンスのメソッドで、配列の一部を start から end （end は含まれない）までの範囲で、選択した新しい配列オブジェクトにシャローコピーして返します。 ここで start と end はその配列に含まれる項目のインデックスを表します。元の配列は変更されません。

### 命名
https://ja.react.dev/learn/tutorial-tic-tac-toe
> React では、イベントを表す props には onSomething という名前を使い、それらのイベントを処理するハンドラ関数の定義には handleSomething という名前を使うことが一般的です。

### イミュータブルのメリット
- 過去のデータを再利用できる
- イミュータブルにしておくことで再レンダーをスキップすることが容易にできる
https://ja.react.dev/reference/react/memo

### キーについて
> key は React における、特別に予約されたプロパティ。
key は React が自動的に使用して、どのコンポーネントを更新するかを自動的に決定する。
key はグローバルに一意である必要はなく、コンポーネントとその兄弟間で一意であれば十分。