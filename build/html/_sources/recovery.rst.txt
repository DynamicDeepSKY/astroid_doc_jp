.. _recovery:

リカバリー手順
====================

リカバリーを始める前に、ライセンスおよびキャリブレーションファイルをバックアップしてください。

1. ライセンスファイルをダウンロード

.. figure:: /images/license_download.png
   :width: 400
   :alt: ライセンスダウンロード
   :align: center
   
2. レンズキャリブレーションファイルをダウンロード

.. figure:: /images/calibration_download.png
   :width: 400
   :alt: キャリブレーションダウンロード
   :align: center
   
デバイスが起動せず、これらのファイルをダウンロードできない場合は、info@dynamicdeepsky.com にご連絡ください。できるだけ早くこれらのファイルをお送りします。
   
以下の手順に従ってデバイスを工場出荷時の設定に復元します。

1. dynamicdeepsky.comのサポートページからAstroid OSイメージをダウンロードします。
2. https://www.raspberrypi.org/software/ からRaspberry Pi Imagerをダウンロードします。
3. AstroidからOS SDカードを取り出し、SDカードUSBアダプターまたは内蔵SDカードリーダーを使ってコンピュータに接続します。
4. ダウンロードしたイメージでSDカードに書き込みます。
5. SDカードを再びAstroidに戻し、電源を接続します。
6. WIFIリストに「RPiHotspot」が表示されるまで5～10分待ちます。

.. admonition:: 重要

    「RPiHotspot」が表示される前に電源を切ると、3番目のステップからやり直す必要があります。
    

7. RPiHotspotに接続し、ウェブブラウザに以下を入力してシリアル番号を設定します:  

**http://10.10.10.10/setserial/YOUR_SERIALNUMBER**

例えば、シリアル番号が1030001の場合は次のようにします。

http://10.10.10.10/setserial/1030001

.. figure:: /images/set_serial.png
   :width: 400
   :alt: シリアル設定
   :align: center
   
シリアル番号を入力すると、デバイスのWIFI IDがDDS_DIRECT_1030001に変更されます。

8. 次に、ライセンスとシリアルを設定します。「System Setting」->「License Management」の下にある「License Code File」ボタンをクリックし、リセット前にダウンロードしたファイルを選択します。

.. figure:: /images/license_upload.png
   :width: 400
   :alt: ライセンスアップロード
   :align: center

9. 「System Setting」->「Calibration」の下にある「Load Calibration」ボタンをクリックし、リセット前にダウンロードしたファイルを選択します。

.. figure:: /images/calibration_upload.png
   :width: 400
   :alt: キャリブレーションアップロード
   :align: center
   
10. ShowInfoウィンドウでシステムバージョンを確認し、古い場合はアップデートを実行してください。詳細は :ref:`System Update <systemupdate>` を参照してください。

