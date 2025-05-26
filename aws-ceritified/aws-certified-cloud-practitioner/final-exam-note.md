1.A startup wants to **migrate** its data and applications from the **on-premises data center** to AWS Cloud. Which of the following options can be used by the startup to help with this **migration**? (Select two)

```
Utilize AWS Partner Network(APN) to build a custom solution for this infrastructure migration
APN 合作夥伴可提供專業知識與遷移方案，幫助客戶進行基礎設施遷移，特別適合缺乏 AWS 專業技能的初創公司。
Leverage AWS Professional Services to accelerate the infrastructure migration
AWS Professional Services 是 AWS 的官方顧問團隊，專門支援客戶進行快速、有效的雲端遷移，並能提供實作建議和技術支援。
```

2.An e-commerce company has deployed an RDS database in a **single Availability Zone (AZ)**. The engineering team wants to ensure that in case of an AZ outage, the database should **continue working on the same endpoint** **without any manual administrative intervention**. Which of the following solutions can address this use-case?

```
Configure the database in RDS Multi-AZ deployment with automatic failover to the standby
RDS 的 Multi-AZ 部署會在另一個 AZ 自動建立一個同步的備援資料庫實例。當主實例的 AZ 發生故障時，AWS 會自動進行 failover 到備援實例，而且客戶端會繼續使用相同的 endpoint，不需要人工介入，完全符合題目要求。
```

3.Which AWS services can be used to **decouple components** of **a microservices based application** **on AWS Cloud**? (Select two)

```
Amazon Simple Notification Service(SNS)
SNS 是發布/訂閱（Pub/Sub）服務，讓一個服務傳送訊息給多個接收端，有效解耦發布者與訂閱者。
Amazon Simple Queue Service(SQS)
SQS 是排隊服務，用來暫存訊息直到接收方準備好處理，常用於非同步處理與服務間解耦。
```
