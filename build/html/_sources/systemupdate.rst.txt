.. _systemupdate:

システムアップデート
============================


システムバージョンの確認
----------------------------

システム設定に移動し、「System info」をクリックしてシステム情報ウィンドウを開きます。システムバージョンが当社ホームページ上のバージョンより古い場合、システムをアップデートできます。

.. figure:: /images/systeminfo.png
   :width: 400
   :alt: バージョン確認
   :align: center

.. figure:: /images/version_check.png
   :width: 400
   :alt: バージョン確認
   :align: center


オンラインシステムアップデート
---------------------

1. イーサネットケーブルまたは外部WIFIを通じてデバイスをインターネットに接続します。システム設定メニューでメールアドレスまたは電話番号を登録している場合、デバイスのIPアドレスがメッセージで送られてきます。
2. ウェブインターフェースを開き、設定メニュー -> 「System Setting」へ移動し、「Check system update」をクリックします。新しいバージョンがある場合、システムアップデートが自動で開始され、上部にUSBアイコン |usbmemory_green| が表示されます。システムログで進行状況を確認できます。システムログを見るには、「System Setting」メニューの下にある「Show System Log」をクリックします。

.. figure:: /images/start_update.png
   :width: 400
   :alt: バージョン確認
   :align: center

4. アップデートアイコン |update| が消えるまで待ちます。
5. システムを再起動します。
6. システムバージョンが最新になっていることを確認します。

オフラインシステムアップデート
---------------------

1. DynamicDeepSKY.comのサポートタブからアップデートファイルをダウンロードします。
2. ダウンロードしたファイルをDDS USBにコピーします。DDS USBがない場合は、詳細については :ref:`Making a DDS USB <basic>` を参照してください。
3. USBをAstroidに挿入します。上部にUSBアイコン |usbmemory_green| が表示されます。
4. アップデートアイコン |update| が消えるまで待ちます。
5. システムを再起動します。
6. システムバージョンが最新であることを確認します。

.. |update| image:: /images/update.png
                :scale: 30 %

.. |usbmemory_green| image:: /images/usbmemory_green.png
                :scale: 30 %

