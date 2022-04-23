# ⭐ Level System

Each Marble starts at level 1 and receives initial skill points, depending on their rarity. Marbles receive additional skill points each time they level up.&#x20;

Upgrading Marbles will not change their attributes. For example, high level Common Marbles will be able to get more skill points than low level Rare Marbles, but their rarity will stay as Common.&#x20;

Additionally, all upgrades are stored in blockchain and they get transferred over with trades.\


| Level                                  | Upgrade Cost (RLM) | Total Cost (RLM) | Skill Points |
| -------------------------------------- | :----------------: | :--------------: | :----------: |
| <mark style="color:yellow;">1</mark>   |         100        |        100       |      +2      |
| <mark style="color:yellow;">2</mark>   |         120        |        220       |      +4      |
| <mark style="color:yellow;">3</mark>   |         140        |        360       |      +6      |
| <mark style="color:yellow;">4</mark>   |         160        |        520       |      +8      |
| <mark style="color:yellow;">5</mark>   |         180        |        700       |      +10     |
| <mark style="color:yellow;">6</mark>   |         200        |        900       |      +12     |
| <mark style="color:yellow;">7</mark>   |         220        |       1120       |      +14     |
| <mark style="color:yellow;">8</mark>   |         240        |       1360       |      +16     |
| <mark style="color:yellow;">9</mark>   |         260        |       1620       |      +18     |
| <mark style="color:yellow;">10</mark>  |         280        |       1920       |      +20     |
| <mark style="color:yellow;">...</mark> |         ...        |        ...       |      ...     |



Available Skill point can be calculated as:\
`Available Points = Base Skill Point From Rarity + (Marble Level * 2)`

