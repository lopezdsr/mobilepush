---

copyright:
 years: 2015, 2017

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}

# 通知のモニター 
{: #push_monitoring}
最終更新日: 2017 年 10 月 30 日
{: .last-updated}


IBM {{site.data.keyword.mobilepushshort}} サービスの機能が拡張され、ユーザー・データからグラフを生成することにより、プッシュのパフォーマンスをモニターできるようになりました。 ユーティリティーを使用して、すべての送信プッシュ通知をリストするか、すべての登録デバイスをリストして、日次、週次、または月次ベースで情報を分析できます。

すべての送信通知のレポートを生成するには、[REST API](https://imfpush.{DomainName}/imfpush/#!/messages/get_apps_applicationId_messages_report){: new_window} で Push Messages GET レポート・メソッドを使用します。 
	![送信通知レポート](images/monitoring_messages.jpg)


すべての登録デバイスのレポートを生成するには、[REST API](https://imfpush.{DomainName}/imfpush/#!/devices/get_apps_applicationId_devices_report){: new_window} で Push Device Registrations GET レポート・メソッドを使用します。
	![登録デバイス・レポート](images/monitoring_devices.jpg)

モニタリング・ユーティリティーを有効にする方法については、ご使用のプラットフォームに応じて以下を参照してください。

 - [Android デバイスでのプッシュ通知のモニター](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-android-push/tree/Doc#monitoring).
 - [iOS アプリケーションでのプッシュ通知のモニター](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-swift-push/tree/Doc#enable-monitoring).

注:

1. {{site.data.keyword.mobilepushshort}} のモニタリング・タブには分析データは表示されません。
2. REST API を使用して生成されたレポートは、キャッシュに入れられて、キャッシュは 30 分間維持されます。また、グラフに表されるデータがキャッシュ・データから生成されます。
 



 
