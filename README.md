# nightmare-app  
■サービス概要  
悪夢を記録し、その内容を解決することでスッキリとした一日を過ごせることを目的としたアプリ。  
悪夢の内容を記述⇒その内容をAIに読み込ませて、解決した内容を結果画面に表示させる。  
（例　「蜂に刺された」夢を見る　⇒　「あなたを刺した蜂は巣ごと駆除されました」という結果が表示される  

■ このサービスへの思い・作りたい理由  
体質的に悪夢を見る機会が多く、日中にその内容を思い出して気分が下がってしまうことが悩みだった。  
そんな折に、イメージリハーサル療法（IRT）という手法を知った。  
内容は、悪夢から目覚める⇒内容をメモをする⇒その内容を夢物語として書き記し結末を変える、というものである。  
自身で試してみたところ、無理やり悪夢を改変することで多少スッキリした気分で一日を過ごすことができたと同時に、  
夢日記のようで少し面白い方法だとも思った。  
この一連のプロセスをアプリ化すればユニークなものが作成できるのではと思い、サービス作成へと至った。

■ ユーザー層について  
悪夢を見てしまって、モヤモヤした気分になっている人たちを対象とする。（年齢性別などは問わない）  
真剣に悪夢に悩んでいて、切実に解消したいと思っている人たちについては、専門的な対処が必要であると考えているため、現時点で対象とはしない。

■サービスの利用イメージ  
悪夢で目が覚めてしまう⇒手が空いてる時間（電車通勤時間など）にアプリに内容を記録⇒良化した結末を表示させ、ユーザーの気分を晴らす。  
また、過去の悪夢やその解消結果も履歴データとして残して、あとから見返すことができるようにしておく。  
なお、夢日記に没頭すると、夢と現実の区別がつかなくなるというデメリットが存在するようなので、アプリ起動時などに適度な利用を促す注意書きを表示させようと考えている。

■ ユーザーの獲得について  
悪夢はだれしも見るものだと考えているため、特にターゲットは絞らず、X(Twitter)で宣伝してフォロワーに試してもらったり、友人や家族に紹介して使用してもらうことを想定している。

■ サービスの差別化ポイント・推しポイント  
調べる限り、睡眠時に振動を発生させて悪夢を見ないようにするアプリは存在するようだが、悪夢の内容まで踏み込んだアプリは現時点で存在していない認識。  
悪夢の内容を良い結末に改変してくれるというユニークな点を推しポイントとしていきたい。

■ 機能候補  
MVPリリース時  
・会員登録  
・ログイン  
・悪夢入力（登録機能）  
・悪夢改変（AIモデル実装）  
・改変結果表示  
  
本リリース時  
・ステップ入力・確認画面  
・投稿機能  
・悪夢内容を公開する機能  

■ 機能の実装方針予定  
AI実装を実現するため、「ChatGPT API」を導入することを検討している。

### 画面遷移図  
Figma：https://www.figma.com/design/qHvHitUf4rFl4CmhCdOwBV/Nigthmare?node-id=0-1&t=t4BGFFaDuiKO6wS0-1  

### ER図  
draw.io：https://drive.google.com/file/d/1wDsllV8_UTm5XuKgTc5IrvRKsSzWKKbh/view?usp=sharing
