.. _basic:

Web Interface
========================

User Interface Layout
------------------------

.. figure:: /images/screen_component.png
   :width: 700
   :alt: Finder align 
   :align: center

1. カメラ画像
2. クイックコントロールアイコンバー
3. ステータスアイコン
4. ARZoom画像
5. クイックメニュー
6. 検索
7. 検索結果

Status Icons
--------------

|bolt_green| 電源正常

|bolt_red| 電源不安定

|eye_green| 空が認識された

|eye_red| 空の認識に失敗

|eject_red| USBを取り出さないでください

|update| システム更新中

|satellite_green| GPS有効

|satellite_red| GPS入力が必要

|save_green| Inave保存オン

|temp_green| CPU温度は正常範囲内

|temp_red| CPUが過熱しています

|usbmemory_green| USB認識済み


.. |bolt_green| image:: /images/bolt_green.png
                :scale: 50 %
.. |bolt_red| image:: /images/bolt_red.png
                :scale: 50 %

.. |eye_green| image:: /images/eye_green.png
                :scale: 50 %
.. |eye_red| image:: /images/eye_red.png
                :scale: 50 %


.. |eject_red| image:: /images/eject_red.png
                :scale: 50 %
.. |update| image:: /images/update.png
                :scale: 50 %


.. |satellite_green| image:: /images/satellite_green.png
                :scale: 50 %
.. |satellite_red| image:: /images/satellite_red.png
                :scale: 50 %


.. |save_green| image:: /images/save_green.png
                :scale: 50 %
.. |save_red| image:: /images/save_red.png
                :scale: 50 %


.. |temp_green| image:: /images/temp_green.png
                :scale: 50 %
.. |temp_red| image:: /images/temp_red.png
                :scale: 50 %


.. |usbmemory_green| image:: /images/usbmemory_green.png
                :scale: 50 %
.. |usbmemory_red| image:: /images/usbmemory_red.png
                :scale: 50 %




Quick control icons
-------------------------


|lock| 画面ロック/ロック解除

.. |lock| image:: /images/lock.png
                :scale: 60 %


|plus| ズームイン

.. |plus| image:: /images/plus.png
                :scale: 60 %



|minus| ズームアウト

.. |minus| image:: /images/minus.png
                :scale: 60 %



|imgrot| 画像回転

.. |imgrot| image:: /images/imgrot.png
                :scale: 60 %



|setting| 高度な設定メニューの開閉

.. |setting| image:: /images/setting.png
                :scale: 60 %
                
|liveps| ライブスカイ認識オン/オフ

.. |liveps| image:: /images/liveps.png
                :scale: 60 %

|stack| スタッカーのオン/オフ

.. |stack| image:: /images/stack.png
                :scale: 60 %

|search| 星検索

.. |search| image:: /images/search.png
                :scale: 60 %

|starlist| 星リストの開閉 

.. |starlist| image:: /images/starlist.png
                :scale: 60 %

|dgs_align| メイン望遠鏡に対するカメラアラインモードのオン/オフ 

.. |dgs_align| image:: /images/dgs_align.png
                :scale: 60 %
                
|AR| 拡張現実モードのオン/オフ       
                
.. |AR| image:: /images/AR.png
                :scale: 15 %
                
|showstar| 星表示のオン/オフ                     
                
.. |showstar| image:: /images/showstar.png
                :scale: 60 %
                
|showdso| DSO表示のオン/オフ                   
                
.. |showdso| image:: /images/showdso.png
                :scale: 60 %
                
|autodso_search| 最も近いDSO自動表示のオン/オフ        
                
.. |autodso_search| image:: /images/autodso_search.png
                :scale: 60 %
                
|const| 星座表示のオン/オフ        
                       
.. |const| image:: /images/const.png
                :scale: 60 %
                
|timelapse| タイムラプスの開始/終了       
                
.. |timelapse| image:: /images/timelapse.png
                :scale: 60 %
                
|nightmode| ナイトモードのオン/オフ  
                
.. |nightmode| image:: /images/nightmode.png
                :scale: 60 %
                
|eclgrid| 楕円形グリッドのオン/オフ  

.. |eclgrid| image:: /images/eclgrid.png
                :scale: 60 %
                
|azigrid| 方位グリッドのオン/オフ  
                
.. |azigrid| image:: /images/azigrid.png
                :scale: 60 %
                
|fullscreen| フルスクリーンモード（Androidおよびデスクトップのみ）
                
.. |fullscreen| image:: /images/fullscreen.png
                :scale: 60 %
                
|polaralign| 極位置合わせモード開始
             
.. |polaralign| image:: /images/polaralign.png
                :scale: 60 %
                
|imgdown| 画像ダウンロード
                
.. |imgdown| image:: /images/imgdown.png
                :scale: 60 %
                
|ejectmain| USBメモリを取り出す
                
.. |ejectmain| image:: /images/ejectmain.png
                :scale: 60 %
                
|refresh| 画面を更新
                
.. |refresh| image:: /images/refresh.png
                :scale: 60 %
                
|power| 電源オフ
                
.. |power| image:: /images/power.png
                :scale: 60 %



Camera Control Menu
---------------------


.. figure:: /images/menu_cam_setting.png
   :alt: Finder align 
   :align: center



Auto Mode: 自動露出モードの選択。AUTOGAIN は露出を固定し、ゲインのみ調整します。

Brightness: センサーの自動露出レベル。この値に合わせてゲインまたは露出が自動調整されます。

Exposure: センサーの露光時間（秒）。

Gain: センサーのゲイン。

Image Quality: JPG画像の品質（パーセント）。値が高いほどファイルサイズと画像品質は向上しますが、フレーム転送速度は遅くなります。

ZoomMode: このオプションをオンにすると、より高速なフレームレートでクロップされた画像を受信します。このオプションはフォーカス調整時に役立ちます。

ZoomSize: ピクセル単位の画像サイズ。

Mean Subtraction: このオプションをチェックすると、画像から平均ピクセル値が差し引かれます。これは画像から光害を除去するために使用できます。

Mean Low Cut: 平均差し引きレベル。

Light Pollution Removal: 光害によるグラデーションを除去します。上記の平均差し引き機能ではグラデーションのある光害は処理できません。

No IR-CUT: IR-CUTフィルターが取り外されている場合にチェックします。誤った色補正を無効にします。

AUTO WB: 自動ホワイトバランス。IR-CUTフィルターが取り外された場合に選択してください。システムはIR-CUTフィルターなしでホワイトバランスを調整しようとします。

PNG Format: PNG形式の画像ダウンロード。

TIFF Format: RAW形式の画像ダウンロード。



Astro Tools Menu
---------------------


.. figure:: /images/menu_astro_tools.png
   :alt: Finder align 
   :align: center

Detector: 星検出方法の選択。

Longitude: 現在地の経度。

Latitude: 現在地の緯度。

Time Adjust: 指定した時間の空をプレビューするためにシステム時間を調整できます。

Show Mini Map: ミニ画像のオン/オフ

Show Image: 赤い円マーカーだけを見たい場合は、このオプションのチェックを外してください。

Show Finder Mark: 赤い円マーカーを削除したい場合は、このオプションのチェックを外してください。

Marker Size: メイン望遠鏡と同じ赤い円マーカーのサイズを調整するには、このスライダーを調整します。

Show Names: すべての名前を非表示にしたい場合はチェックを外してください。

Guide Line: ガイドモードで方位と高度のガイドラインを見たい場合は、このオプションをチェックしてください。

Catalog: 自動で最も近い星を検索する際に使用する星カタログです。

Min/Max Size: これより大きい/小さいDSOは自動検索されません。メイン望遠鏡の視野に合わせて最小/最大値を調整してください。

Max Distance: 検索範囲。値が大きいほど広い範囲を検索します。

Min/Max Mag: これより暗い/明るいDSOは自動検索されません。好みに応じて最小/最大値を調整してください。

Sort By: 星リストで自動検索ボタンをクリックすると、見つかった星はこのオプションでソートされます。

RA(h:m:s), DEC(h:m:s): 彗星などのカスタムRA、DEC位置。「リストに追加」ボタンをクリックしてカスタム位置を星リストに追加します。


Timelapse Menu
---------------------


.. figure:: /images/menu_timelapse.png
   :alt: Finder align 
   :align: center

タイムラプス画像保存機能のために、異なる形式を選択できます。タイムラプスアイコン |timelapse_small| を押すと、システムは上で選択した形式で画像の記録を開始します。
                
.. |timelapse_small| image:: /images/timelapse.png
                :scale: 40 %


Tiff および png 形式は RAW 画像を保存し、「注釈付き保存」はメイン望遠鏡の方向などの追加情報を含む画像を保存します。


System Setting Menu
---------------------


.. figure:: /images/menu_systemsetting.png
   :alt: Finder align 
   :align: center

Support Mode: このオプションをチェックすると、サポートチームがリモートでデバイスを診断できます。このオプションを使用する前に、まずサポートチームにご相談ください。

ID: 外部Wi-FiのSSID

Pass: 外部Wi-Fiのパスワード

Email: ネットワーク接続時にデバイスのIPアドレスを受信するメールをここに入力します。Astroidからのメールは迷惑メールフォルダに振り分けられることがあります。

.. figure:: /images/wifi_email.png
   :width: 400
   :alt: メールによるWi-Fi通知
   :align: center


Phone: 国際形式で電話番号を入力してIPアドレスを受信します。メッセージは1日1回のみ送信されます。

.. list-table:: ダイヤルコード
   :align: center
   :widths: 50 25
   :header-rows: 1   

   * - 地域
     - 番号
   * - 日本
     - +61
   * - 韓国
     - +81
   * - オーストラリア
     - +82     
     
例えば、オーストラリアで 0401 123 456 という番号でデバイスを接続する場合、次のように入力します。

.. figure:: /images/wifi_phone.png
   :width: 400
   :alt: 電話によるWi-Fi通知
   :align: center


Get License File: このボタンをクリックしてライセンスファイルをダウンロードできます。ダウンロードしたライセンスファイルは、システム復旧後にライセンス設定を復元するために使用できます。ライセンスファイルを保存していない場合は、「Get System ID」をクリックしてシステムIDを取得し、ご連絡ください。




Collimation Menu
---------------------


.. figure:: /images/menu_collimation.png
   :alt: Finder align 
   :align: center

Camera: 現在、内部カメラのみサポートされています。

Focus: 外部オートフォーカスカメラのフォーカスコントロール

X Offset: 円をX軸方向に移動

Y Offset: 円をY軸方向に移動



Setting Up License
-----------------------

Astroidの基本システムとアプリは、ハードウェアライセンスキーで保護されています。そのため、回復イメージからデバイスを復旧する場合は、ライセンスも復旧する必要があります。これにはライセンスファイルをウェブインターフェースにアップロードする必要があります。ライセンスファイルは、システム設定メニューの「Get License File」ボタンをクリックしてダウンロードできます。デバイスを受け取ったら、一度ライセンスファイルをダウンロードしてコンピュータに保存しておくことをお勧めします。

ライセンスファイルをアップロードするには、システム設定メニューに移動し、**License Code File** ボタンをクリックして、コンピュータに保存したライセンスファイルを選択します。

ライセンスファイルにアクセスできない場合は、システムIDとシリアル番号を送ってください。スタッフができるだけ早くライセンスファイルを送ります。


また、Raspberry Pi 4を交換すると、元のライセンスコードは動作しません。したがって、Raspberry Piに関連する問題がある場合は、自分でRaspberry Piを交換するのではなく、当社にご連絡ください。
 

Hot Pixel Correction
--------------------

ホットピクセルの数は時間とともに自然に増加します。特にトラッキングオプションをオンにしたEAAスタッカーを実行する場合、これらのホットピクセルが特に目立ちます。Astroidには内蔵のホットピクセル検出・修正機能があります。しかし、ホットピクセルを修正するには、手動でホットピクセル検出器を有効にする必要があります。以下の手順に従ってホットピクセルを検出し、修正してください。 

1. 付属のセンサーカバーを使用してセンサーを完全に遮断します。部屋中の明かりをすべて消し、部屋を完全に暗くします。
2. カメラ設定に移動し、露出を1秒に、ゲインを150に設定します。
3. システムメニューに移動し、ホットピクセルレベルを調整します。値が低いほど多くのホットピクセルが検出されます。
4. ホットピクセル修正ボタンをクリックします。
5. EAAスタッカーを実行し、ホットピクセルが消えたか確認します。
6. デフォルト値で試しても弱いホットピクセルが残る場合は、値を下げて上記を満足するまで繰り返します。



Writing Images to USB Memory
------------------------------

1. DDS USB を用意します。DDS USB の作り方は次のセクションを参照してください。
2. USB を Astroid に挿入し、上部ステータスバーに USB アイコン |usbmemory_green| が表示されることを確認します。
3. タイムラプスボタンをクリックして録画を開始します。

.. |usbmemory_green| image:: /images/usbmemory_green.png
                :scale: 30 %




.. admonition:: Warning

    高速USBメモリーのみを使用してください。低速USBの場合、録画終了後もAstroidがファイルを書き込み続け、ファイル破損の可能性が大幅に高まります。
    

.. admonition:: How to eject

    USB は、取り出しボタンをクリックしてすべてのUSB関連アイコンが消えた後に取り出してください。そうしないとUSBが破損し、USB内のすべてのデータが失われます。
    

Making DDS USB
------------------------------

1. SanDisk 32GB Ultra Fit などを用意します。データ損失を防ぐために高速USBメモリーを強く推奨します。
2. ディスクをNTFS形式でフォーマットし、名前をDDSに変更します。
3. USBをAstroidに挿入し、上部にUSBアイコンが表示されることを確認します。

