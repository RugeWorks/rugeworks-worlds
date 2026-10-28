# 灯籠の都(仮題)画像生成の指示

版:2026-10-28 23:50

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

注意:髪は「真っ黒(jet black)」。焦げ茶に寄りやすいので、シオンの焦げ茶と区別できるよう毎回指定する。動きは力任せにせず、礼法の型で美しく。

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

```
Japanese anime style character reference sheet, plain light background.
Clean bold line art, flat cel shading with soft minimal shadows, limited color palette, no glossy highlights, no heavy gradients, not overly symmetrical.
Shion, 25-year-old exhausted government clerk at a spirit records office in an alternate modern Japan where traditional culture survived into 2026.
Personality: sarcastic and sharp-tongued, knows every rule and its loopholes, overworked; becomes perfectly polite and quietly frightening when drunk.
Dark brown hair neatly tied up, round glasses, tired but sharp eyes.
Plain kimono with a dark green haori, a thick ledger and a writing brush, an ink stone.
Modern items: a staff ID card on a lanyard around her neck, a smartwatch on her wrist, a can of energy drink.
Include: full body front, side and back views with the same items in every view;
expressions: sarcastic smirk, overworked and exhausted, cold smile pointing out a loophole, perfectly polite but frightening, calmly writing in the ledger.
Close-ups of the ledger, brush, ink stone, ID card and smartwatch. No animals. No text in the image.
```
