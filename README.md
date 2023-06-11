# Siv3D_WheelSimulator

## シュミレーションアプリケーションの使い方

_ロボットの表示形式_

- チェックマークを入れると、画面中央にロボットが固定されます。

- チェックマークをのけると、ロボットが入力に応じて移動するようになります。

/assets/images/robot_simulation.png

_ロボットスピード_

- ロボットの各タイヤの最大ベクトルの速度を設定します。
- 0 から 255 までの数値を設定できることができます。
- オムニホイールと独立ステアリング制御での最大速度の差を実感することができると思います。

_入力モード_

- キーボード入力モード

  - W,A,S,D によって、前後左右の移動を行い、右矢印、左矢印により、旋回の入力をすることができます。

- PS5 コントローラ入力モード
  - コントローラの左スティックの入力により、前後左右の入力を行い、右スティックの入力によって旋回を行います。

_ロボットの計算モード_

- Omni-Mode

  - 4 輪オムニホイールのベクトル計算を行います。

- Steering-Mode

  - 独立 4 輪ステアリング機構のベクトル計算を行います。
