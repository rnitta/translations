---
# jp title missing
title: Protecting your code signing files
menu:
  ios-code-signing:
    weight: 9
---
コード署名ファイルを`Protected`モードに設定することができます。これにより、[bitrise.io](https://www.bitrise.io)アカウントからダウンロードすることはできなくなります。ビルドではもちろん、これらの保護されたファイルを使えます。しかし、ファイルを保護すると、誰もそれを見ることはできません。上書きする唯一の方法は、現在のファイルを削除して新しいファイルを作成することです。

1. `Dashboard`でアプリを選択してください。
2. `Workflow`タブを選択します。
3. `Code Signing`タブを選択します。
4. 保護するファイルを探し、ドロップダウンメニューを開きます。

     ![コード署名ファイルを保護する](/img/code-signing/ios-code-signing/provisioning-and-certificate-protect.png)
5. `Make protected`オプションを選択します。

    ポップアップウィンドウが表示されたら、この変更は確認後元に戻すことができません。 変更を個別に保存する必要はありません。

完了後、ファイルのドロップダウンメニューの唯一のオプションは `Delete`になります。
