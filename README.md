# ROBOT-binary
*Ayo kita membuat robot opsi biner yang profitable dan rendah resiko!*

I sometimes posted my scripts on <a href="https://gist.github.com/Fruitfella">My Gists</a>, but due to my lack of knowledge and experience in github and gists (*and scripting lol*), I accidentally posted it as secret gists. therefore you maybe unable to see most of it. I'm too lazy to move it to public gists, so...</br>
Don't worry though, I posted the links <a href="https://github.com/Fruitfella/ROBOT-binary/issues/35">here</a>, so you can access it.

_*I decided to put my scrypts here_ :)

---
## READ THIS FIRST
1. To download the scripts, just right click on the link (script's name) then click `Save linked content as..` , make sure the file type is *xml* then click `Save`.</br>
![untitled-2](https://user-images.githubusercontent.com/26277327/28746118-f3417cc8-74af-11e7-9034-fb9ec105cbd0.gif)

2. Load the scripts on https://bot.binary.com/bot.html by clicking **`Load new blocks (xml file)`** the one with folder icon on the right screen, below your account balance.
3. Once the green **"Blocks are loaded successfully"** notification appear on the bottom-right of the page, you can take the new blocks (the tools) from menu **Advanced -> Functions** and use it on your bot.</br>
![untitled-3](https://user-images.githubusercontent.com/26277327/28746458-f16675a0-74b6-11e7-86a0-05bc4cdd2783.gif)


_*Good luck with your bot!_  🎆 

---
**Please note this :**
Sometimes (frequently) I put _number_ in front of block's name such as **(1) FRUITFELLA MANAGEMENT** or **(4) FRUITFELLA Trade again** . This number means that you must put these block in the main block with the same number. You should noticed that all the 4 main blocks has _number_
Also I give _number_ (5) to the block that must be put in **`This block called on every tick`**</br>
![note](https://user-images.githubusercontent.com/26277327/28250030-d074e6d2-6a8a-11e7-9a55-abdd26b2f471.png)

---
## MONEY MANAGEMENT
They said that the most important factor separating the seasoned traders from the amateurs is Money Management. How so? Dont ask me, it wasn't me who said that!

----
### Martingale
The system's mechanics involve an initial bet; however, each time the bet becomes a loser, the wager is doubled such that, given enough time, one winning trade will make up all of the previous losses.

**Example :**

Your Bet | Wager | Flip Results | Profit/Loss | Account Equity
-----|-----|-----|-----|-----
Heads | $ 1 | Heads | $ 1 | $11
Heads | $ 1 | Tails | $ (1) | $10
Heads | $ 2 | Tails | $ (2) | $8
Heads | $ 4 | Heads | $ 4 | $12

Assume that you have $10 to wager, starting with a first wager of $1. You bet on heads, the coin flips that way and you win $1, bringing your equity up to $11. Each time you are successful, you continue to bet the same $1 until you lose. The next flip is a loser, and you bring your account equity back to $10. On the next bet, you wager $2 hoping that if the coin lands on heads, you will recoup your previous losses and bring your net profit and loss to zero. Unfortunately, it lands on tails again and you lose another $2, bringing your total equity down to $8. So, according to martingale strategy, on the next bet you wager double the prior amount to $4. Thankfully, you hit a winner and gain $4, bringing your total equity back up to $12. As you can see, all you needed was one winner to get back all of your previous losses.

Well, thats how common martingale. As for my martingale, its a bit different but still with the same concept.

**Download martingale :**

| <a href="https://gist.githubusercontent.com/Fruitfella/cc22c35eca8de66e97bc8b418d34c99c/raw/59b66a0a4f5d482a56b0e24b49b9736fb6e0b180/FRUITFELLA's_Martingale_ver.2.1.xml">FRUITFELLA's Martingale Ver.2.1</a> |
|---|
| ![martingale2](https://user-images.githubusercontent.com/26277327/28210528-0c0ab688-68c2-11e7-8c54-66bf22bac3f0.png) |

| <a href="https://gist.githubusercontent.com/Fruitfella/cc22c35eca8de66e97bc8b418d34c99c/raw/59b66a0a4f5d482a56b0e24b49b9736fb6e0b180/FRUITFELLA's_Martingale_ver.3.0.xml">FRUITFELLA's Martingale Ver.3.0</a> |
|---|
| Requested by Cadet21 |
| ![martingale3](https://user-images.githubusercontent.com/26277327/28210552-24940308-68c2-11e7-8ef8-f6efde74694b.png) |

---
### Compound Interest
Basically its adding the prev profit into the next stake. By doing so we could get a bigger profit if we win the next bet and would only loose the initial bet if we loss.
**Example :** your money is $10

Bet | Stake | Result | Profit/Loss | Money
-----|-----|-----|-----|-----
Head | 1 | Tail | -1 | 9
Head | 1 | Head | 1 | 10
Head | 2 | Tail | -2 | 8
Head | 1 | Head | 1 | 9
Head | 2 | Head | 2 | 11
Head | 4 | Head | 4 | 15

**Download Compound Management :**

| <a href="https://gist.githubusercontent.com/Fruitfella/d9747ecf6b4843c03353e67ba9cd07ba/raw/ffba998c8dc4fd656a31b8a8b05778df660f44f7/FRUITFELLA's_Compound_Management_ver.1.0.xml">FRUITFELLA's Compound Management Ver.1.0</a> |
|---|
| Requested by falsinalves |
| ![untitled](https://user-images.githubusercontent.com/26277327/30248451-4beaad0e-9652-11e7-9db2-6f4c3a18b39e.png) |

---
## CANDLE ANALYSIS
| <a href="https://gist.githubusercontent.com/Fruitfella/e086b99dc8fc243067cce18d38e1c398/raw/fc4a069ba65a4a5077f3d8d5ab693ae76186b27f/FRUITFELLA_Candle_Percentage.xml">FRUITFELLA's CANDLE PERCENTAGE</a> |
|---|
| Example : purchase fall if current candle's upper shadow is bigger/longer than candle's body |
| ![capture](https://user-images.githubusercontent.com/26277327/28952671-e7d72e72-78fc-11e7-8629-39fd3209ed62.png) |

| <a href="https://gist.githubusercontent.com/Fruitfella/a322926d20e9733ce1a9c070d60b6b77/raw/2f2cd40688a3e67e3be5fc6497aa8462d96b98fb/FRUITFELLA's%2520New%2520Candle.xml">FRUITFELLA's NEW CANDLE</a> |
|---|
| Example : purchase rise if candle is new |
| ![cin](https://user-images.githubusercontent.com/26277327/28250092-c6c55404-6a8b-11e7-9386-f90f4595c860.png) |

| <a href="https://gist.githubusercontent.com/Fruitfella/571952f7b1e03cf0148655c8364a3214/raw/7be26e77742c8bbcd1d60bd832c808483eb5efb9/FRUITFELLA_New_Candle_v2.xml">FRUITFELLA's NEW CANDLE 2</a> |
|---|
| <i>Detecting a new candle a little faster than the prev version</i> |
| Example : purchase rise if candle is new |
| ![capture](https://user-images.githubusercontent.com/26277327/32705753-e16955dc-c849-11e7-8b26-ba1271a93c87.png) |

| <a href="https://gist.github.com/Fruitfella/e326d8c18c5b9d7200300fabd77a751f/raw/c2b7d9e90fa0f286f25391167b1c6956767f7721/FRUITFELLA's%2520Trend%2520Direction.xml">FRUITFELLA's Trend Direction</a>|
|---|
| This tool check the the direction of the market in given period. |
| Example : purchase rise if trend of 5 minutes candle is up and purchase fall if down |
| ![picture01](https://user-images.githubusercontent.com/26277327/29080554-3b61fde8-7c8a-11e7-8a57-9b62c1fed9a4.png) |

| <a href="https://gist.githubusercontent.com/Fruitfella/f42247cf6c1e771886ca0eb1db71e7ab/raw/1869a9072bd9d48288b4e0fc21ae0bf1571baa68/FRUITFELLA's_EMA_Trend.xml">FRUITFELLA's EMA Trend</a>|
|---|
| This tool check the the direction of the market using 3 Emas. falsinalves' request|
| Example : purchase rise if trend is up and purchase fall if down.
_"Number of list" is for how many candles are count on calculation, its better to make it as higher as possible for accuracy, but too high will slowing the bot._
`Fruitfella UP-TREND (Smooth)` _and_ `Fruitfella DOWN-TREND (Smooth)` _are for detecting strong trend (experiment)_ |
| ![capture](https://user-images.githubusercontent.com/26277327/28652872-8b715192-72b4-11e7-825e-97100477be94.PNG) |

| <a href="https://gist.github.com/Fruitfella/236f579368ee0657fe4cadc6266a5176/raw/672d595abef9a9bd6f1c2d27fa4dc3800476bea8/FRUITFELLA's%25203%2520Candles%2520same%2520color.xml">FRUITFELLA's 3 Candles with same color</a> |
|---|
| _1# fixed 17 Jul 2017, 22.06 GMT+7_ |
| This is most wanted tool |
| Example : purchase rise if 3 recent candles are greens (up) and purchase fall if reds (down) |
| ![picture01](https://user-images.githubusercontent.com/26277327/28251802-6344e8b2-6aaf-11e7-858e-fd6c1716cdf6.png) |

| <a href="https://gist.githubusercontent.com/Fruitfella/e3a5603f47a18785c3a551ce5255ef9a/raw/11c69af4180aa7dc7cb81c7e10264048864d2bc2/FRUITFELLA's_WMA.xml">FRUITFELLA's WEIGHTED MOVING AVERAGE</a> |
|---|
| this indicator were requested by mnaseem |
| Example : purchase rise if the current price is higher than WMA |
| ![untitled](https://user-images.githubusercontent.com/26277327/30519673-1928dcc8-9bc6-11e7-820b-9443f1f79ba4.png) |

---

## TICK ANALYSIS

| <a href="https://gist.githubusercontent.com/Fruitfella/e326d8c18c5b9d7200300fabd77a751f/raw/73c5f86182d988be90878f8994f4dfb9907df584/FRUITFELLA's_Trend_Direction.xml">FRUITFELLA's Trend Direction</a> |
|---|
| This tool check the direction of the market in given period. |
| Example : purchase rise if trend is up and purchase fall if trend is down |
| ![untitled](https://user-images.githubusercontent.com/26277327/29880297-9ca95558-8dd1-11e7-8581-2bb51229323b.png) |

| <a href="https://gist.githubusercontent.com/Fruitfella/f12301e69f0f6a09ca5ddcd68e7c50de/raw/534fc08a4cbbd6703d68bd30f3b99524292a9666/FRUITFELLA_Digit_Analyzer.xml">FRUITFELLA's Last Digit Analyzer</a> |
|---|
| *1# revised 10 Sep 2017, 14:00 GMT+7* |
| This tool create a list of Last Digits from x recent ticks. It also check the most and the least frequent Last Digit |
| ![capture](https://user-images.githubusercontent.com/26277327/30246927-9da7a87a-9631-11e7-9f09-da83191f0bff.png) |

| <a href="https://gist.githubusercontent.com/Fruitfella/ab019eedc64c2c525adfcc9900b99413/raw/9b42a328f2f8bc0706af1561f27ef9b2773a8f4f/FRUITFELLA's_LD_Analyzer_ver.2.0.xml">RUITFELLA's Last Digit Analyzer Ver.2.0</a> |
|---|
| Now that there is **`Last Digit List`** block, things are easier :) |
| ![untitled](https://user-images.githubusercontent.com/26277327/31042369-65953fac-a5d0-11e7-8122-20ee76babbc4.png) |

