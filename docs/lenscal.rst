.. _lenscal:

レンズキャリブレーション
======================

正確なスカイ認識および極位置合わせのためには、レンズキャリブレーションが重要です。Astroidは工場出荷時に初期キャリブレーションが行われていますが、デバイスの落下などによる強い衝撃など、さまざまな理由でキャリブレーション品質が低下する可能性があります。

望遠鏡とAstroidの間のeFinderアライメントが正確でないと感じた場合、レンズキャリブレーション機能を使用してレンズをキャリブレーションすることができます。

必要条件
------------------------

1. 晴れて開けた空
2. 光害と月光のない空 


キャリブレーションは画像中の星の位置を使用します。Astroidが星をよく見ることができる場所でキャリブレーションを実行することを確認してください。そのような環境がなくてもキャリブレーションを行うことは可能ですが、キャリブレーションの品質は保証されません。

キャリブレーション手順
------------------------

1. 「System Setting」->「Calibration」内の「Clear Calib Img」をクリックして、以前のキャリブレーション画像をすべて消去します。

.. figure:: /images/calib_clear.png
   :width: 400
   :alt: Version check
   :align: center
   
2. Astroidを三脚に取り付け、三脚のヘッドを調整して、Astroidのレンズが上を向くようにします。この目的にはボールヘッド三脚が最適ですが、デバイスをテーブルに置くだけでも構いません。
3. 空が認識されるまで待ちます。
4. 空が認識されたら、設定メニューに移動し、「Save Calib Img」を押して画像を保存します。

.. figure:: /images/calib_save.png
   :width: 400
   :alt: Version check
   :align: center
   
5. カメラを約20度回転させ、ステップ3〜4を繰り返します。
6. ステップ3〜5を繰り返して20枚の写真を撮影し、「Start Calibration」ボタンを押します。

.. figure:: /images/calib_start.png
   :width: 400
   :alt: Version check
   :align: center
7. キャリブレーションレポートのメッセージが表示されるまで待ちます。   
8. デバイスを望遠鏡に再び合わせて、アライメントが良好か確認します。

