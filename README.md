# TouchDesigner

## roulette
3つのテキストを順番に表示するルーレット。  
ボタンを押したらルーレットがゆっくりとまる。

## barGraph
カウントした値を棒グラフで見る。  
overTOPでふたつのconstantTOPの位置をぴったり合わせた状態で合成し、countの数によって位置を動かすことで棒グラフを再現。  
横幅があまり必要ない場合は、それぞれの色のcontainerの中で黒い下地を作って大きさを調整するのが早くて簡単かも。  
Mathのrangeで入力値を何にするのかを決めると、画面に対して良い感じの高さになる。

## changeText
textをswitchで変更する。

## countAccelVal
OSCで取得したAccelの値をカウントし、4マスに並べる。
