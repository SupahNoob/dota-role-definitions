# Defining Roles

## Abstract

---

<b>Background</b>: In the game of DotA, there exists 115 different characters that any given player may choose from. For simplicity's sake, each hero has 4 abilities that comprises its "kit" and help to define the hero's intended role to play within the game. Skills typically fall within a few major categories: damage, heal, crowd-control, damage-augmentation, or damage-mitigation. Very typically, a hero's kit will have some sort of synergy within the four abilities and "best fit" way to play the game. To throw another variable into the mix, there also exists over 125 different items which fall within similar major categories as skills. Needless to say, this combination of items, skills, and heroes within your team of 5 is incredibly massive. The game of DotA as whole is, in its purest essence, about efficient resource gathering\*. Games end by one team razing their enemy's base which is not an easy task without items and team coordination.

---

One of the more challenging aspects in the game of DotA is team composition. You take 5 random players, stick them on the same side, and demand they coordinate their thinking and actions without ever knowing their allies strengths, weakness, or comforts. It doesn't stop at <b>just</b> the draft stage however, but also <i>how their heroes are meant to be played within the match itself</i>. To simplify, we will attempt to classify heroes into two distinct roles:

<b><u>Core</u></b>: a hero whose job it is to gather resources on the map, and after a latent period, end the game out.

<b><u>Support</u></b>: a hero whose job it is secure areas of the map for safe resource gathering, without taking a majority of the resources themselves.

Typically your Cores are high damage-dealing heroes that have kits that help augment this ability, but require items or levels to truly achieve this. Supports either help to mitigate overall damage taken by allies or physically control and limit the movements of their enemies, but typically do not require the large amount of gold and experience that are available on the map.

This Notebook will attempt to classify heroes within those two roles, but with an added layer of complexity. Longtime players of the game can do this rather intuitively for most heroes in their <i>intended state of play</i>, however the meta, or "the way the game is intended to be played", changes over the course of time - sometimes without any game version updates. This can have drastic implications and [even complete role reversals for certain heroes][1]. For these reasons, <b><i>we will attempt to classify heroes within the two roles to create a solution that is game-version agnostic</i></b>.

The Notebook itself will take a more playful and conversational tone as we explore the data, algorithms, and concepts involved in defining roles.

---

\* resources: **gold** to be exchanged for items; **experience** to unlock additional, or higher ranked skills and abilities.

[1]: https://news.unikrn.com/article/eg-mineski-natures-prophet-furion-support-dota-2