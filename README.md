# 伝言ゲーム — dengon

[English](#english)

一つの作品を、違う文法へ訳し継ぐブラウザアプリ。写真 → 言葉 → 音 → 絵…。どこで何が落ちて、何が勝手に生まれるかを見る。

**▶ [ブラウザで今すぐ開く](https://hallucination-freqwave-af.github.io/dengon/)**

自分の Anthropic API キーを入れて使う。キーはそのブラウザから Anthropic に直接送るだけで、ほかのどこにも送らない。

## かたち

- **一周して戻る**：はじまり（写真か言葉）から決めた手数だけ訳し継いで、最初と最後を並べる
- **流れ続ける**：止めるまで、毎回ちがう文法へ流れていく
- **絵本**：最初の言葉が1ページ目。絵描きはそのページの文だけを見て描き、書き手はそれまでの話を覚えたまま、前の絵と今の絵を見て次のページを書く。大人向け／子ども向け、終わりを決めない、も選べる
- **データ絵本**：[異文法の銀河](https://github.com/hallucination-freqwave-af/igrammar-groove) が書き出すCSVを台本にする。数え方たちが登場人物になり、三層（CSV → 数え方の話 → 人間ドラマ）で一冊になる。人間ドラマの舞台（江戸、宇宙船…）だけ選べる。最後はエンドロール

訳し手は Claude（Haiku / Sonnet / Opus）。訳し手ごとに訛りが違う。

写真やCSVは画面に落とせば入る。できた記録は JSON で保存できる。

---

## English

A browser app that keeps translating one work into different grammars — photo → words → sound → picture… — to see what falls away and what appears on its own.

**▶ [Open in your browser](https://hallucination-freqwave-af.github.io/dengon/)**

Bring your own Anthropic API key. It is sent only from your browser directly to Anthropic.

Modes: loop back to the start, flow on forever, picture book (an illustrator who sees only the current page, a writer who remembers the whole story), and data picture book, which turns a CSV log from [iGrammar Groove](https://github.com/hallucination-freqwave-af/igrammar-groove) into a three-layer book (CSV → a story of counting systems → a human drama) with end credits. The UI is in Japanese for now.

Made with Claude. MIT License.
