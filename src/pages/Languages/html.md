<properties
	pageTitle="HTML"
	_description="The HTML editor was completely rewritten in Visual Studio 2013 to create a foundation for a great HTML 5 editing experience that is constantly getting better."
	description="HTML5 の素晴らしい編集体験の基礎を作るために Visual Studio 2013 で HTML エディターは完全に書き直され、絶え間なく改善しています。"
	slug="html"
	order="200"
	keywords="html, intellisense, html5, xhtml, autocomplete"
/>

## Auto-completion
<!--
The HTML editor's up-to-date web standards definitions provide accurate and fast [IntelliSense](http://go.microsoft.com/fwlink/?LinkId=532997) for all elements and attributes. For attributes, IntelliSense lists available values as well as names.
-->

HTML エディタの持つ最新の Web 標準の定義は全ての要素や属性の [IntelliSense](http://go.microsoft.com/fwlink/?LinkId=532997) を的確で素早く提供します。

![Basic auto completion](_assets/html-auto-completion.gif)

## Match end-tag
<!--
Never let your tags get out of sync again when editing. When you edit a tag, Visual Studio automatically updates its corresponding begin or end tag to keep them in sync.
-->

編集時にタグの同期がとれていないことはもうありません。タグを編集すると Visual Studio は自動的に対応する開始、終了タグの同期をとります。

![Match end-tag](_assets/html-match-end-tag.gif)

## Classes and IDs
<!--
It's easy to forget the names of CSS classes and IDs, so Visual Studio IntelliSense lists them for you as you type. You get all of the classes and IDs that are defined in the current document or in any stylesheet in your project. For example, if you use Bootstrap, IntelliSense shows all of the available Bootstrap classes.
-->

CSS クラスや ID といった名前を忘れてしまっても大丈夫です。文字を打ち込めば Visual Studio IntelliSense は一覧を表示します。現在のドキュメントやプロジェクトに含まれているスタイルシートで定義されている、すべてのクラスや ID を得ることができます。
例えば、もし Bootstrap を使っていれば IntelliSense は 利用可能な Bootstrap のクラスをすべて表示します。

![Classes and IDs](_assets/html-classes-and-ids.gif)

## Dynamic data attributes
<!--
When using `data-*` attributes in HTML 5 to store custom data, it can be difficult to remember the various attribute names and their values. Visual Studio automatically keeps track of your `data-*` attributes and gives IntelliSense for both the attribute name and previously used values.
-->

カスタムなデータを格納するために HTML5 の `data-*` 属性を利用する場合、属性名の種類とその値を思い出すのが難しいことがあります。Visual Studio は自動的に `data-*` 属性を追跡し続け、属性名と以前利用した値を IntelliSense に表示します。

![Dynamic attriute values](_assets/html-dynamic-attribute-values.gif)

## Wrap with tag
<!--
Be more productive by using this handy shortcut to wrap selected text with any element of your choice.
-->

お手軽なショートカットで選択されたテキストと要素を包むことができ、より生産性を高められます。

<!--
Simply hit `Shift+Alt+W` to wrap the selection.
-->

選択したものを包むには単純に `Shift+Alt+W` を押してください。

![Wrap with tag](_assets/html-wrap-with-tag.gif)

## Snippets
<!--
Snippets provide a shortcut for adding common elements to a page. Visual Studio has built-in snippets for `<video>`, `<audio>`, `<picture>`, and many more. You can create your own snippets as well.
-->

スニペットはページに共通の要素を追加するショートカットを提供します。Visual Studio は `<video>` や `<audio>`、 `<picture>` や他のたくさんのビルトインのスニペットを持っています。もちろん自分自身でスニペットを作ることもできます。

![Snippets](_assets/html-snippets.gif)

## File picker
<!--
The file picker gives you an easy way to add references to files in your project. It's smart enough to know what files you would typically use for `<img>`, `<a>`, `<script>`, `<source>` and `<link>` elements, so it automatically filters the list to show only those file types.
-->

ファイルピッカーはプロジェクトのファイルに参照を追加する簡単な方法を提供します。`<img>`, `<a>`, `<script>`, `<source>` や `<link>` 要素でよく使われるファイルについてよく知っているので、それらのファイルタイプのみをフィルターして一覧に表示します。

![File picker](_assets/html-file-picker.gif)

## HTML 5 Microdata
<!--
It's important to be very accurate when dealing with 
[Microdata](http://html5doctor.com/microdata/). Visual Studio helps you avoid typos by giving IntelliSense for the most common Microdata vocabularies.
-->

[Microdata](http://html5doctor.com/microdata/) を扱うのであれば正確であることが重要になります。Visual Studio は IntelliSense を通して多くの一般的な Microdata のボキャブラリーを提供し、誤字を避ける手助けをします。

![HTML 5 Microdata](_assets/html-microdata.gif)

## ARIA attributes
<!--
IntelliSense lists the choices for ARIA landmarks such as the `role` attribute, as well as for `aria-*` attributes.
-->

IntelliSense は `role` 属性のような ARIA ランドマークの選択肢を表示します。もちろん `aria-*` 属性もです。

![ARIA attributes](_assets/html-aria.gif)

## HTML entities
<!--
Get quick and easy access to all those HTML entities that are so hard to remember.
-->

思い出すことが難しいようなあらゆるHTMLの文字実体参照にサッっと簡単にアクセスできます。

![Entities](_assets/html-entities.gif)

## Template syntax
<!--
Whether you use Mustache, Handlebars, Angular, or any other double-curly based template language, Visual Studio gives you nice colorization.
-->

Mustache や Handlebars、 Angular であっても、その他の二重ブレース({{, }})を元にしたテンプレート言語であっても、Visual Studio はよい感じの色付けを提供します。

![Template syntax](_assets/html-template-syntax.gif)

## Glyph icons
<!--
See the actual glyph icons from all the major CSS icon libraries, including Bootstrap, Font Awesome, Foundation, Ionicons and IcoMoon using the
[Glyphfriend](https://visualstudiogallery.msdn.microsoft.com/5fd24afb-b3b2-4cec-9b03-1cfcec6123aa) extension.
-->

Bootstrap、Font Awesome、Foundation、Ionicons や IcoMoon といった主要な CSS アイコンライブラリに含まれているグリフアイコンの実体を [Glyphfriend](https://visualstudiogallery.msdn.microsoft.com/5fd24afb-b3b2-4cec-9b03-1cfcec6123aa) 拡張を使うことで見ることができます。

![Glyphfriend](_assets/html-glyphfriend.png)

## Quick actions
<!--
Light bulbs show up wherever Visual Studio finds opportunities to provide helpers that give you hints about how to solve problems or refactor.
-->

電球マークによって Visual Studio が問題やリファクタリングのヒントを表示するヘルパーを提供できそうだということを知らせます。

![Quick action](_assets/html-quick-action.gif)

<aside role="complementary">

## Related resources

<section>

### More information

- [HTML 5 specification](http://www.w3.org/TR/html5/)
- [Intro to HTML 5](http://www.w3schools.com/html/html5_intro.asp)
</section>

<section>

### Relevant extensions

- [Web Essentials](https://visualstudiogallery.msdn.microsoft.com/ee6e6d8c-c837-41fb-886a-6b50ae2d06a2)
- [Glyphfriends](https://visualstudiogallery.msdn.microsoft.com/5fd24afb-b3b2-4cec-9b03-1cfcec6123aa)
- [Bootstrap Snippet Pack](https://visualstudiogallery.msdn.microsoft.com/e82e7862-f731-4183-a27a-3a44b261bfe5)
</section>

</aside>