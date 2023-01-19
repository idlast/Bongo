この配布パッケージはSRTビンゴと下記ビンゴの中間のバージョンです。
機能としては下記ビンゴと同等の物です。
https://github.com/lepelog/botw-bingo



元ページ: https://pastebin.com/b77T4Hxv

次にボードの例を示します：http://pastebin.com/raw.php?i=1PGPRQ2G
 
ボードは、主に以下を含むJavaScriptファイルです。
 
-すべてのレベル配列を含むボード配列（別名「bingoList」）。
-25レベルの配列。それぞれが1?25のスケールで目標の長さを表します（したがって、bingoList [1]の目標が最も短く、bingoList [25]の目標が最も長くなります）。
-「名前」文字列と「タイプ」配列を含むいくつかの目標オブジェクト。各レベルには、任意の数の目標を含めることができます。
 
タイプ：任意の文字列の配列。これらは、他の目標との行の相乗効果の計算にのみ使用されるため、任意に設定できます。タイプが一致する目標は、同じ行に表示される可能性がはるかに低くなります。共通するタイプが多いほど、それらが一緒に表示される可能性は低くなります。
 
ショート/ノーマル/ロングビンゴの場合：基本的に、ショートビンゴはアルゴリズムを再フォーカスして、低レベルの目標を返します（ロングビンゴと高レベルの目標と同じ）。これらをうまく配布するのに十分な目標がない場合は、短い/長いボタンを削除するように要求するのが賢明かもしれません。
 
目標数について：明らかに、ボードが機能するには最低25の目標が必要です。ただし、25のみで、すべてのボードに同じ目標があります。50は許容可能な開始点ですが、100が推奨されます。最も人気のあるビンゴには、多くの場合200を超えるものがあることに注意してください。

Here's an example board: http://pastebin.com/raw.php?i=1PGPRQ2G
 
A board is a JavaScript file primarily containing the following:
 
- The board array (aka "bingoList"), containing all the level arrays.
- 25 level arrays, each representing the length of the goal on a scale of 1-25 (so goals in bingoList[1] are the shortest and those in bingoList[25] are the longest).
- Some number of goal objects containing a "name" string and "types" array. Each level can contain any number of goals.
 
On Types: An array of arbitrary strings. They can be anything you set, as they are only used for calculating row synergy with other goals. Goals that have matching types are much less likely to appear in the same row. The more types in common the less chance of them appearing together.
 
On Short/Normal/Long Bingo: Basically, short bingo simply refocuses the algorithm to return goals in lower levels (same with long bingo and high level goals). If you do not have enough goals to distribute these well, it may be wise to request to have the short/long buttons removed.
 
On Number of Goals: Obviously a board requires a minimum of 25 goals to function. However, with only 25 every board would have the same goals. 50 is an acceptable starting point, but 100 is recommended. Note that the most popular bingo's often have upwards of 200. **Coming up with good goals and assigning types and levels properly is a long and difficult process, and should be done with as many runners as possible.**
