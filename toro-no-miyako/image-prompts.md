# 灯籠の都(仮題)画像生成の指示

版:2026-10-29 02:40

監修役のAIが画像を作るときの共通ルールと、キャラクターシートの指示文。設定は [settei.md](./settei.md) と [characters.md](./characters.md) を優先する。

## 共通ルール

- 世界観:平安の公家文化と江戸の武家文化が残ったまま2026年に至った、もう一つの日本。和装が普通で、スマホなど現代の道具も当たり前にある
- 画風:日本のアニメ・漫画風。3人で同じ画風にそろえる
- AIらしさを抑える:はっきりした線画、平塗りに近い控えめな影(セル塗り)、色数を絞る。髪や瞳の強い光沢、過剰なグラデーション、装飾の盛りすぎを避ける。左右対称すぎる顔やポーズを避ける
- 現代の要素:伝統7割・現代3割を目安に、各キャラに現代の物を必ず入れる。神聖な物(巫女装束、刀など)は伝統の形のまま、日々の便利な物(スマホ、イヤホン、靴など)を現代の物にする
- 細部の一致:正面・横・後ろで、持ち物の形や色をそろえる
- キャラクターシート:1枚に、全身の正面・横・後ろ、表情の違い(3〜4種)、持ち物の拡大を並べる。背景は無地
- 一度気に入った画像ができたら、それを基準画像として、同じキャラの以降の生成で参照する
- 別のキャラを初めて作るときは、他のキャラの画像を添付しない(顔や髪型が写ってしまうため)。画風は文章で指定し、3人の画風合わせは集合絵の段階で行う
- やむを得ず他のキャラの画像を参照するときは、「線と塗りの画風だけを参照し、顔・髪型・体格・年齢・服装は写さない」と明記する
- 文字は画像に入れない(崩れやすいため)
- 実在の作品のキャラクターに似せない

## 3人の色

| 人物 | 象徴 | 髪 | 差し色 |
| --- | --- | --- | --- |
| ツグミ | 灯 | 茜色(朱がかった赤茶)の短髪 | 白と朱 |
| 九郎 | 刀 | 黒の長髪を後ろで束ねる | 濃紺 |
| シオン | 帳 | 焦げ茶の髪をきっちりまとめる | 深緑 |

## 3人の身長(案)

| 人物 | 身長 | 体格 |
| --- | --- | --- |
| ツグミ | 約155cm | 小柄 |
| 九郎 | 約172cm | なで肩でひょろりとした細身の少年。手と腕だけが鍛えられている |
| シオン | 約163cm | 中肉中背 |

## キャラクターシートの指示文

### ツグミ

```
Japanese anime style character reference sheet, plain light background.
Clean bold line art, flat cel shading with soft minimal shadows, limited color palette, no glossy highlights, no heavy gradients, not overly symmetrical.
Tsugumi, 17-year-old shrine maiden apprentice in an alternate modern Japan where traditional culture survived into 2026.
Personality: usually a dreamy, easygoing girl who seems to listen to voices others cannot hear; becomes dignified and sharp only when something truly matters.
Short madder-red (reddish auburn) hair tied with a thin red cord.
Traditional white and vermilion miko outfit, a small paper lantern hanging at her waist, a small handwritten notebook.
Modern items: white sneakers instead of traditional sandals, a smartphone peeking from her sleeve with a small lantern-shaped charm, one wireless earbud in one ear.
Include: full body front, side and back views with the same items in every view;
expressions: dreamily gazing into the air, smiling and talking toward empty space, tilting her head, frozen with a completely blank face when praised, and one dignified serious face with a straight gaze.
Close-ups of the waist lantern, the notebook and the smartphone with its charm. No animals. No text in the image.
```

### 九郎

**基準画像:A案(2026-10-28 仮完成)**。以降は同じチャットで、この顔・髪型・体格を変えずに直す。B案(より爽やかな印象)は別の場面用に残しておく。

注意:顔の造りは良い(10/29 変更。最初の指示文の「ハンサムにしない」は使わない)。ただし表情は真顔で、色気や爽やかさは出さない。注意:髪は「真っ黒(jet black)」。焦げ茶に寄りやすいので、シオンの焦げ茶と区別できるよう毎回指定する。動きは力任せにせず、礼法の型で美しく。

以下は最初に2案を作ったときの指示文(記録用)。

```
Japanese anime style character reference sheets, plain light background. Create TWO separate design proposals (Version A and Version B) of the same character.
Clean bold line art, flat cel shading with soft minimal shadows, limited color palette, no glossy highlights, no heavy gradients. Simple anime style with fewer lines. Must not resemble any existing anime character.

Kurou, 18-year-old disinherited swordsman in an alternate modern Japan where traditional culture survived into 2026. He is a teenage boy, not an adult man.
He is a sword fool: he cares about nothing but swordsmanship and lacks common sense entirely. He is NOT handsome, NOT cool, NOT gentle-handsome, NOT charming, NOT wild, NOT clever. An ordinary, plain-looking, slightly odd teenage boy.
Face: a plain, average-looking boyish face, not a pretty boy and not a rugged man. Almost expressionless at all times: a deadpan, unblinking face with eyes always staring straight ahead. His expression barely changes even when he says something absurd.
Body: about 172 cm, skinny and lanky with clearly sloping, narrow shoulders. NOT muscular, NOT broad-shouldered, NOT tall and imposing. Only his hands look hardened from training.
Hair: long straight black hair reaching his mid-back, tied in a single low ponytail at the nape.
Clothes: one old indigo kimono and hakama he took from his family home and keeps wearing: originally fine quality but now visibly faded, frayed at the hems and patched in several places. On the back, the family crest has been removed, leaving only a faded mark where the crest used to be.
Sword: only one katana, which cannot be drawn; its scabbard is wrapped with paper talismans and tied shut with a red cord.
Modern items: worn-out black sneakers, a convenience store plastic bag with cat treats. He has NO phone at all: do not draw any phone or flip phone anywhere.

Version A: the above description as written.
Version B: push it further: an even stranger, more deadpan and absurd look, extremely stiff and formal posture, as if he does not understand the modern world at all.

Each sheet includes: full body front, side and back views with the same items in every view;
expressions with almost no change: deadpan stare, deadpan deep formal bow, deadpan while saying something absurd, and an intense fighting face (the only clearly different one);
one action pose striking with the sheathed sword in a beautiful formal stance;
close-ups of the talisman-sealed scabbard, the removed family crest mark on the back, and the cat treat bag. No animals. No text in the image.
```

### シオン

**基準画像:2026-10-29 仮完成**。指示文から次を変えた:年齢22歳、明るい灰色でやや短い袴(靴下が見える丈)、酔った顔は「目を閉じた笑顔・顔の上半分の影・白く光る眼鏡・お酌」。以降は同じチャットで、顔(丸く大きな茶色の瞳、目の下の影なし)を毎回具体的に指定して直す。

**2026-10-28 改訂**。ツグミ・九郎のシート作りで分かったことを反映した。絵師殿の新しいチャットで使い、他のキャラの画像は添付しない。

改訂の要点:
- 「丸眼鏡の皮肉屋の事務員」はよくある型なので、シオンだけの目印を足した(案):**髪のまとめ髪に簪の代わりに筆を挿している**、**袖に事務用の黒い袖カバー**、**右手の指先に墨の汚れ**
- 髪は「温かみのある焦げ茶」。九郎の真っ黒と見分けられるよう、黒にしないと明記
- 美人・色っぽさ・クールビューティーに寄せない。22歳の地味で疲れた女性(10/29 に25歳から変更)
- 九郎のシートで背景の場面が入ったため、無地の背景と場面なしを明記
- 足元はツグミ・九郎と重ならないよう、スニーカーではなく黒い革のローファー

```
Japanese anime style character reference sheet on a plain flat light background. No scenery, no background scenes, no panels with locations.
Clean bold line art, flat cel shading with soft minimal shadows, limited color palette, no glossy highlights, no heavy gradients, not overly symmetrical. Simple anime style with fewer lines. Must not resemble any existing anime character.

Shion, 22-year-old overworked government clerk at a spirit records office in an alternate modern Japan where traditional culture survived into 2026. She is a young woman, plain and tired-looking, but clearly young, not middle-aged.
She is NOT glamorous, NOT sexy, NOT a cool beauty, NOT a strict teacher type. An ordinary, slightly worn-out office worker with sharp, intelligent eyes.
Personality: sarcastic and sharp-tongued, knows every rule and every loophole, chronically overworked; becomes perfectly polite and quietly frightening when drunk.
Face: tired eyes with faint dark circles, round thin-framed glasses.
Body: about 163 cm, average height and average build, slightly slouched posture from desk work.
Hair: warm dark brown hair (clearly brown, NOT black), neatly tied up in a tight bun. Instead of a hairpin, a writing brush is stuck through the bun.
Clothes: a plain muted kimono with a dark green haori. Black office sleeve covers (arm covers) over the kimono sleeves. Faint ink stains on the fingertips of her right hand.
Items: a thick ledger bound with string, a writing brush, a small ink stone.
Modern items: a staff ID card on a lanyard around her neck, a smartwatch on her left wrist, a can of energy drink. Plain black leather loafers (no sneakers).
Include: full body front, side and back views with the same items in every view;
expressions: sarcastic smirk, overworked and exhausted staring into space, cold smile while pointing out a loophole, perfectly polite but frightening with slightly flushed cheeks (drunk), calm and focused while writing;
one pose standing with the ledger open on her forearm, writing with the brush in a calm, precise motion;
close-ups of the ledger, brush, ink stone, ID card, smartwatch and the brush in her hair bun. No animals. No text in the image.

### 3人の集合絵(画風と身長合わせ)

**2026-10-29 作成**。絵師殿の新しいチャットで、3人のキャラクターシートを「ツグミ → 九郎 → シオン」の順に添付して使う。目的は画風と身長のバランスをそろえることなので、まずは並んで立つだけの絵にする。見栄えのする場面の絵は、この後に作る。

注意:
- 九郎のシートだけ、塗りが濃く傷みの表現が細かい。ツグミ・シオンの明るく平たい塗りに合わせる
- 3人の顔が混ざりやすいので、添付画像の順番と各人の特徴を文章でも書く
- シオンはふだんの姿(焦げ茶のまとめ髪)。覚醒の姿にしない

```
I attached three character reference sheets in this order: 1st = Tsugumi, 2nd = Kurou, 3rd = Shion.
Draw all three standing side by side in one image, full body, front view, relaxed natural poses, plain flat light background. No scenery, no animals, no text.

Purpose: unify the art style and show correct height differences.
Art style for all three: clean bold line art, flat cel shading with soft minimal shadows, limited color palette, light and bright overall tone, like the 1st and 3rd sheets. Draw Kurou in this same lighter, simpler style (keep his clothes worn and patched, but with fewer fine details and no heavy dark texture).

Heights (very important): Tsugumi about 155 cm (the shortest), Shion about 163 cm (middle), Kurou about 172 cm (the tallest). Order from left to right: Tsugumi, Kurou, Shion.

Keep each face and design exactly as in their own sheet. Do not mix faces or hairstyles between them.
- Tsugumi: 17, short madder-red hair with a red cord, white and vermilion miko outfit, small paper lantern at her waist, white sneakers, one wireless earbud. Dreamy expression, looking slightly off to the side.
- Kurou: 18, skinny teenage boy with sloping shoulders, long jet-black hair (pure black) in a low ponytail, worn indigo kimono and hakama, one katana with a talisman-wrapped scabbard tied with a red cord, worn black sneakers, convenience store bag with cat treats. No phone. Deadpan expression, staring straight ahead.
- Shion: 22, warm dark brown hair (clearly brown, not black) in a bun with a writing brush stuck through it, round glasses with large round brown eyes, dark green haori, black sleeve covers, light ash-gray hakama, white socks and black loafers, staff ID lanyard, thick ledger. Slightly tired, sarcastic small smile.
```
