# sky-jone
Denoでしりとり

今回は以下の仕様を目標にして作成した。

直前の単語を、表示できるようにした。
任意の単語を、入力できるようにした。
直前の単語の末尾と、入力した単語の先頭を比較して、同じ場合だけ単語を更新する。違う場合は、エラーを表示するようにした。
末尾が「ん」で終わる単語が入力されたら、ゲームを終了する。
過去に使用した単語が入力されたら、ゲームを終了する。
ゲーム中や終了後に、最初からやり直せるリセット機能をつけた。

それに加えて、最初の単語がランダムに決まるようにした。
　　　　　　　ひらがな以外は入力できないようにした。
       　　　絵文字などのしりとりとして不適切な単語は入力できないようにした。
