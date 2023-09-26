# CloudWatch AgentでEC2のカスタムメトリクスとログ取得
## 構成
* SSMのRun Commandを使用してCloudWatch Agentのダウンロード
* SSMのパラメータストアにCloudWatch Agentの設定ファイルを保存
* SSMのRun Commandを使用してCloudWatch Agentのインストール

![sc-cfn-dev04](https://github.com/Toru-Kubota/AWS-CFn-Dev04/assets/102895466/89d70322-9cb6-4e97-a767-e53710c520fd)


## 備考
* ※Run Commandの箇所は手動実行   
* [CloudWatch エージェントをダウンロードして設定する](https://docs.aws.amazon.com/ja_jp/AmazonCloudWatch/latest/monitoring/download-CloudWatch-Agent-on-EC2-Instance-SSM-first.html)
* [エージェント設定を使用した EC2 インスタンスへの CloudWatch エージェントのインストール](https://docs.aws.amazon.com/ja_jp/AmazonCloudWatch/latest/monitoring/install-CloudWatch-Agent-on-EC2-Instance-fleet.html)
