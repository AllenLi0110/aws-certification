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

4.Which of the following statements are CORRECT regarding the AWS VPC service? (Select two)

```
A Security Group can have allow rules only
Security Group 只能「允許」，不能顯式拒絕（deny）。
A Network Address Translation gateway (NAT gateway) is managed by AWS
NAT Gateway 是一種由 AWS 管理的服務，可讓私有子網的實例存取外部網際網路（例如下載套件）。
```

5.Which of the following is the MOST **cost-effective** option to purchase an **EC2 Reserved Instance (RI)**?

```
Partial upfront payment option with standard 3-years term
標準 3 年期 + 部分預付款 提供良好折扣，又不會像全額付款一樣一次支出太大，實務上被視為最具成本效益。
```

6.Which AWS Support plan provides **architectural guidance** contextual to your **specific use-cases**?

```
AWS Business Support
沒提到大企業等級 → 選 Business Support 最合適。
```

7.A unicorn startup is building an analytics application with support for a speech-based interface. The application will accept **speech-based input** from users and then convey results **via speech**. As a Cloud Practitioner, which solution would you recommend for the given use-case?

```
Use Amazon Transcribe to convert speech to text for downstream analysis. Then use Amazon Polly to convey the text results via speech
語音 ➜ 文字：Amazon Transcribe
文字 ➜ 語音：Amazon Poll
```

8.An IT company is planning to **migrate from an on-premises environment to AWS Cloud**. Which of the following expense areas would result in **cost savings** when the company moves to AWS Cloud? (Select two)

```
Data center hardware infrastructure expenditure
Data center physical security expenditure
不用再自己管理硬體與設施，軟體和服務層還是要付費。
```

9.Which of the following AWS services should be used to **automatically distribute incoming traffic** across **multiple targets**?

```
AWS Elastic Load Balancing(ELB)
ELB 可以根據流量負載，自動分發請求到多個後端目標（如 EC2 實例、容器、Lambda 函數），提升系統可用性與彈性。
```

10.Which tool/service will help you **access AWS services** using **programming language-specific APIs**?

```
AWS Software Developer Kit(SDK)
AWS SDK 提供多種程式語言（如 Python、JavaScript、Java、C# 等）的 API 介面，方便開發者寫程式直接操作 AWS 服務。
```

11.A medical research startup wants to understand the **compliance** of AWS services concerning **HIPAA guidelines**. Which AWS service can be used to **review the HIPAA compliance and governance-related documents** on AWS?

```
AWS Artifact
AWS Artifact 是 AWS 的合規文件管理平台，可以查閱 AWS 的安全與合規報告、認證文件（如 HIPAA、SOC、PCI 等），幫助企業了解 AWS 合規狀況。
```

12.A data analytics company is running a proprietary **batch analytics application** on AWS and wants to use a storage service which would **be accessed by hundreds of EC2 instances simultaneously** to **append data to existing files**. As a Cloud Practitioner, which AWS service would you suggest for this use-case?

```
Amazon Elastic File System (Amazon EFS)
是一種共享檔案系統，可以被多個 EC2 同時掛載，支援檔案系統操作（讀寫、附加等），非常適合需要並行存取和寫入的應用。
```

13.A web application stores all of its data on Amazon S3 buckets. A client has mandated that data **be encrypted before sending it** to Amazon S3. Which of the following is the right technique for encrypting data as needed by the customer?

```
Enable client-side encryption using AWS encryption SDK
表示資料在本地就已經加密，上傳時是密文，完全符合客戶的需求。
```

14.Which of the following AWS services support **reservations** to **optimize costs**? (Select three)

```
Amazon Relational Database Service (Amazon RDS)
支援多種 DB 引擎（Aurora, MySQL 等）以 RI 方式付款，可節省長期成本。
Amazon DynamoDB
預測好讀寫容量需求可預約保留，節省成本。
Amazon Elastic Compute Cloud (Amazon EC2)
事先保留 EC2 實例容量，並比隨需更便宜。
```

15.A multi-national corporation wants to get **expert professional advice** on **migrating to AWS** and **managing their applications** on AWS Cloud. Which of the following entities would you recommend for this engagement?

```
Amazon Consulting Partner
這家公司要的是「顧問級專業建議」，針對遷移和管理應用程式。
```

16.A company uses **reserved EC2 instances** across **multiple units with each unit having its own AWS account**. However, some of the units **under-utilize** their reserved instances while other units need more reserved instances. As a Cloud Practitioner, which of the following would you recommend as the most **cost-optimal** solution?

```
Use AWS Organizations to manage AWS accounts of all units and then share the reserved EC2 instances amongst all units
最省錢的方式就是用 AWS Organizations 把所有帳號管理在一個組織中，這樣 EC2 Reserved Instances（預留實例）就可以在所有帳號之間共享，避免浪費。
```

17. A startup wants to provision an EC2 instance for the **lowest possible cost** for a **long-term duration** but needs to make sure that the instance would **never be interrupted**. As a Cloud Practitioner, which of the following options would you recommend?

```
EC2 Reserved Instance (RI)
便宜、穩定，適合長期使用（符合兩個關鍵需求）。
```

18.An organization is currently **operating MySQL databases on its own on-premises servers**. To **reduce the operational** burden of database maintenance and management, the organization wants to move to a **fully managed AWS database** offering. Which migration strategy best aligns with this goal?

```
Replatform
把應用或資料庫搬到新的平台，但不重寫程式碼，比如從自管 MySQL 搬到 AWS RDS MySQL，達到減少管理工作目的。
```

19.Which of the following AWS services has **encryption enabled by default**?

```
AWS CloudTrail Logs
```

20.The DevOps team at an e-commerce company is trying to **debug performance issues** for its **serverless application** built using a **microservices architecture**. As a Cloud Practitioner, which AWS service would you recommend addressing this use-case?

```
AWS X-Ray
用來分析、追蹤及偵錯微服務與無伺服器應用效能問題的服務，可以追蹤請求的流程和瓶頸，找出延遲原因。
```

21.The DevOps team at an IT company is moving 500 GB of data from an **EC2 instance to an S3 bucket** in the **same region**. Which of the following scenario captures the correct **charges** for this **data transfer**?

```
The company would not be charged for this data transfer
同區域 EC2 → S3 資料傳輸免費，不會有額外費用。
```

22.Which AWS Service can be used to mitigate a **Distributed Denial of Service (DDoS) attack**?

```
AWS Shield
AWS Shield 是 AWS 提供的 DDoS 緩解服務。
```

23.Which of the following AWS Support plans provide access to **only core checks** from the **AWS Trusted Advisor** Best Practice Checks? (Select two)

```
AWS Basic Support
AWS Developer Support
只有 Basic 和 Developer 層級的帳號是「入門」等級，只能用 core checks。Business/Enterprise 類的支援，才有「完整功能」。
```

24.**AWS Shield Advanced** provides expanded **DDoS attack** **protection for web applications** running on which of the following resources? (Select two)

```
AWS Global Accelerator
AWS Global Accelerator：提供應用流量全域加速，Shield Advanced 提供擴展的 DDoS 保護。
Amazon Route 53
Amazon Route 53：保護 DNS 層級，對應 L3/L4 攻擊。
```

25.What are the **advantages** that AWS Cloud offers over a traditional on-premises IT infrastructure? (Select two)

```
Eliminate guessing on your infrastructure capacity needs
AWS 提供彈性擴展（Auto Scaling、按需資源），讓你只需為實際使用量付費，避免資源浪費。
Trade capital expense for variable expense
使用 AWS，你按用量付費，是 營運支出（OpEx），不需前期大筆投入，風險與負擔更低。
```

26.A Project Manager, working on AWS for the first time, is confused about how credits are used in AWS. There are two credits available in the manager's account. **Credit one is for $100, expires July 2022**, and can be used for either Amazon S3 or Amazon EC2. **Credit two is for $50, expires December 2022**, and can be used only for Amazon EC2. The manager's AWS account has incurred two charges: $1000 for Amazon EC2 and $500 for Amazon S3. What will be the outcome on the overall bill once the credits are used? (Select two)

```
Credit one is applied, which expires in July, to the Amazon EC2 charge which leaves you with a $900 Amazon EC2 charge and a $500 Amazon S3 charge
Then, credit two is applied to the remaining $900 of Amazon EC2 usage
步驟 1：套用 Credit 1（$100，可用於 EC2 或 S3）
AWS 會將 Credit 1 用在 EC2（更高金額的費用，以最大化節省）
EC2 減少為 $900，S3 仍為 $500
步驟 2：套用 Credit 2（$50，只能用於 EC2）
剩下的 EC2 是 $900 → 套用 $50
EC2 最終變成 $850，S3 還是 $500
```

27.Under the **AWS Shared Responsibility Model**, which of the following is a shared responsibility of **both AWS and the customer**?

```
Configuration Management
這是共享責任：
AWS 提供工具（如 EC2 Systems Manager、Elastic Beanstalk、RDS 等）
客戶負責設定應用程式、作業系統、安裝更新、套用安全性政策等
```

28.A multi-national company has just **moved its infrastructure from its on-premises data center to AWS Cloud**. As part of the shared responsibility model, **AWS is responsible for** which of the following?

```
Physical and Environmental controls
AWS 的責任範圍（Infrastructure 層級）
```

29.Which of the following **Amazon S3 storage classes** takes **the most time** to **retrieve data** (also known as first byte latency)?

```
Amazon S3 Glacier Deep Archive
S3 Glacier Deep Archive 是 S3 中 最便宜的儲存類別，但它需要最多的時間來取回資料。
```

30.Which of the following are correct statements regarding the **AWS Global Infrastructure**? (Select two)

```
Each Availability Zone (AZ) consists of one or more discrete data centers
每個 AZ 至少一個、通常多個資料中心，而且這些資料中心彼此距離夠遠以防故障傳播，但又夠近以低延遲連接。
Each AWS Region consists of a minimum of three Availability Zones (AZ)
雖然早期有些區域只有兩個 AZ，但目前 AWS 在建立新區域時，標準是至少三個 AZ，以提升高可用性和容錯性。
```

31.Which of the following are the **advantages of cloud computing**? (Select three)

```
Trade capital expense for variable expense
資本支出轉為可變支出，無需購買實體硬體（如伺服器、機房），只需根據實際使用情況付費。
Benefit from massive economies of scale
AWS 集中採購、集中運營，讓你以更低的成本使用高品質資源。
Go global in minutes and deploy applications in multiple regions around the world with just a few clicks
透過 AWS 的全球基礎設施，你可以輕鬆部署應用程式到多個區域（Regions），滿足全球使用者的需求並降低延遲。
```

32.Which of the following is an **AWS database service**?

```
Amazon Redshift
Amazon Redshift 是一種由 AWS 提供的完全託管式資料倉儲服務，專門用來執行分析型查詢和大規模資料報告作業。
```

33.Which of the following AWS services support **VPC Gateway Endpoint** for a **private connection** from a VPC? (Select two)

```
S3
DynamoDB
VPC Gateway Endpoint 是 AWS 提供的一種連線方式，允許你從你的 VPC 私下連接到支援的 AWS 服務，不經過公網（Internet）。
VPC Gateway Endpoints 只支援：
Amazon S3
Amazon DynamoDB
```

34.Which of the following is CORRECT regarding **removing an AWS account from AWS Organizations**?

```
The AWS account must be able to operate as a standalone account. Only then it can be removed from AWS organizations
在將 AWS 帳號從 AWS Organizations 中移除之前，你必須先確保該帳號可以獨立運作，也就是配置好所有必要的設定與付款方式。這是正確也是唯一的操作方式。
```

35.Which of the following statements are CORRECT **regarding the Availability Zone (AZ) specific characteristics of Amazon Elastic Block Store (EBS)** and **Amazon Elastic File System (Amazon EFS) storage types**?

```
EBS volume can be attached to a single instance in the same Availability Zone (AZ) whereas EFS file system can be mounted on instances across multiple Availability Zones (AZ)
EBS 是區域性資源（scoped to AZ）
EFS 是區域級別的網路檔案系統，可以跨 AZ 同時掛載
```

36.Which option is a common stakeholder role for the AWS Cloud Adoption Framework (AWS CAF) platform **perspective**? (Select two)

```
Engineer
Chief Technology Officer(CTO)

Engineer	實作與維運雲端平台，設計技術解決方案
Chief Technology Officer (CTO)	技術總監，負責雲端採用策略與技術路線圖
```

37.Which of the following AWS services can be used to connect a **company's on-premises environment to a VPC without using the public internet**?

```
AWS Direct Connect
AWS Direct Connect 是一項專用網路服務，可以讓公司透過專線直接連接到 AWS VPC，不經由公共網際網路，因此連線更穩定、安全且延遲低。
```

38.Which security service of AWS is enabled for all AWS customers, **by default**, at **no additional cost**?

```
AWS Shield Standard
AWS Shield Standard 是 AWS 提供的 免費且預設啟用 的 DDoS 防護服務，適用於所有 AWS 客戶。它自動保護你的網站和應用程式免受常見的 DDoS 攻擊，無需額外設定或費用。
```

39.A silicon valley based healthcare startup stores **anonymized patient health data** **on Amazon S3**. The CTO further wants to ensure that **any sensitive data** on S3 is discovered and identified to **prevent any sensitive data leaks**. As a Cloud Practitioner, which AWS service would you recommend addressing this use-case?

```
Amazon Macie
Amazon Macie 是一項安全服務，專門用來自動識別、分類和保護存放在 Amazon S3 中的敏感數據（例如個人識別信息 PII、健康數據等）。它利用機器學習來檢測敏感數據並提供資料安全風險的可視化報告，幫助企業防止資料洩漏。
```

40.A company runs an application on a fleet of **EC2 instances**. The company wants to **automate the traditional maintenance job** of running **timely assessments and checking** for OS vulnerabilities. As a Cloud Practitioner, which service will you suggest for this use case?

```
Amazon Inspector
Amazon Inspector 專門用來自動化安全漏洞掃描和合規性評估，適合這種需求。
```

41.A company needs a **storage solution** for a project wherein the data is **accessed less frequently** but needs rapid access when required. Which S3 storage class is the **MOST cost-effective** for the given use-case?

```
Amazon S3 Standard-Infrequent Access(S3 Standard-IA)

accessed less frequently（不常被存取）
needs rapid access when required（需要時能快速存取）
MOST cost-effective（最具成本效益）

Amazon S3 Standard-Infrequent Access (S3 Standard-IA)
理由如下：
專為不常訪問但需要快速存取的資料設計。
相對於 S3 Standard 成本較低，但仍提供毫秒級存取時間。
比 Glacier 或 Glacier Deep Archive 提供更快的讀取速度，適合立即讀取需求。
```

42.A company wants to improve the resiliency of its flagship application so it wants to move from its traditional database system to a **managed AWS NoSQL database service** to support **active-active configuration** in **both the East and West US AWS regions**. The active-active configuration with **cross-region support** is the prime criteria for any database solution that the company considers. Which AWS database service is the right fit for this requirement?

```
Amazon DynamoDB with global tables
Global tables 支援 多區域自動同步與多主模式（active-active）部署。
```

43.A **financial services company** wants to ensure that its **AWS account activity** meets the **governance**, **compliance** and **auditing norms**. As a Cloud Practitioner, which AWS service would you recommend for this use-case?

```
AWS CloudTrail
AWS CloudTrail 可記錄、監控並保留 AWS 帳戶中的所有 API 調用與活動歷程。
```

44.A research group wants to use **EC2 instances** to run a **scientific computation application** that has a **fault tolerant architecture**. The application needs **high-performance hardware disks** that provide **fast I/O performance**. As a Cloud Practitioner, which of the following storage options would you recommend as the **MOST cost-effective solution**?

```
Instance Store
若目的是要兼顧 高 I/O 性能 + 成本效益，而又能容忍資料非持久性，Instance Store 是最適合的選項。
```

45.A big data analytics company is moving its IT infrastructure **from an on-premises data center to AWS Cloud**. The company has some **server-bound software licenses** that it wants to use on AWS. As a Cloud Practitioner, which of the following EC2 instance types would you recommend to the company?

```
Dedicated Host
server-bound software licenses: 這表示該公司有一些綁定在特定伺服器硬體（如 CPU ID、主機板序號等）的授權機制，這在雲端動態資源（如共享虛擬機）上通常無法運作。
需要使用 綁定實體伺服器授權的軟體，選擇 Amazon EC2 Dedicated Host 是正確且合規的選擇。這樣可以確保你的軟體授權能夠在雲端合法運作，並避免合約違規問題。
```

46.Which of the following AWS Support plans provide access to **guidance, configuration, and troubleshooting of AWS interoperability with third-party software**? (Select two)

```
AWS Business Support
AWS Enterprise Support
要獲得AWS 與第三方軟體整合支援（例如 MySQL、Windows、Apache、Docker 等），你需要至少：
AWS Business Support
AWS Enterprise Support
這兩者都涵蓋該層級的技術支援。
```

47.Which of the following entities **applies patches to the underlying OS for Amazon Aurora**?

```
The AWS Product Team automatically
Aurora 是託管型服務，AWS 負責所有底層 patch。
```

48.A cyber forensics team has detected that **AWS owned IP-addresses** are being used to carry out **malicious attacks**. As this constitutes **prohibited** use of AWS services, which of the following is the correct solution to address this issue?

```
Contact AWS Abuse Team
AWS Abuse Team 專門負責處理這種事件，如果你偵測到來自 AWS IP 的攻擊行為，必須聯繫 AWS Abuse Team。他們會追蹤來源帳號、暫停服務，甚至封鎖帳戶。
```

49.A company wants to have **control over creating and using its own keys** for **encryption on AWS services**. Which of the following can be used for this use-case?

```
customer managed key (CMK)
Customer Managed Key (CMK)允許使用者自行建立與管理金鑰，包括設定權限、輪換策略和使用控制。
```

50.A startup wants to set up its IT infrastructure on AWS Cloud. The CTO would like to get an **estimate** of the **monthly AWS bill** based on the **AWS services that the startup wants to use**. As a Cloud Practitioner, which AWS service would you suggest for this use-case?

```
AWS Pricing Calculator
因為題目提到要預估 AWS 每月帳單，所以應選 AWS Pricing Calculator，它專門用來估算 AWS 成本。
```

51.A company wants to **identify the optimal AWS resource configuration** for its workloads so that the company can **reduce costs** and **increase workload performance**. Which of the following services can be used to meet this requirement?

```
AWS Compute Optimizer
AWS Compute Optimizer 利用機器學習幫助公司找到最適合的資源配置，從而降低成本並提升效能。
```

52.An organization needs to **securely access AWS services** and establish **private connectivity** between its **Virtual Private Clouds (VPCs)** and supported AWS services **without using the public internet**. Which AWS services can meet this requirement? (Select two)

```
AWS Transit Gateway
AWS PrivateLink
AWS PrivateLink 和 AWS Transit Gateway 都可以實現 VPC 與 AWS 服務之間的私有連接，避免經過公共網路。
```

53.According to the **AWS Shared Responsibility Model**, which of the following are responsibilities of AWS? (Select two)

```
Operating the infrastructure layer, the operating system and the platform for the Amazon S3 service
Replacing faulty hardware of Amazon EC2 instances
AWS 負責管理基礎設施和服務平台（如 S3 的作業系統）以及更換故障硬體，這些是 AWS 的責任範圍。
```

54.Which of the following is a recommended way to provide **programmatic access** to AWS resources?

```
Use Access Key ID and Secret Access Key to access AWS resources programmatically
使用 Access Key ID 和 Secret Access Key 是推薦的方式，讓應用程式或腳本能安全地以程式化方式存取 AWS 資源。
```

55.Which of the following AWS services support **reservations** to **optimize costs**? (Select three)

```
Amazon RDS
Amazon DynamoDB
Amazon EC2
Amazon EC2、Amazon RDS 和 Amazon DynamoDB 都支援保留容量（Reserved Instances 或 Reserved Capacity），可用來降低長期使用成本。
```

56.An online gaming company wants to **block users** from **certain geographies** from **accessing its content**. Which AWS service can be used to accomplish this task?

```
AWS Web Application Firewall (AWS WAF)
AWS WAF 可用來設定地理封鎖規則，從而阻止特定國家或地區的使用者存取網站內容。
```

57.What are the **fundamental drivers of cost** with **AWS Cloud**?

```
Compute, Storage and Outbound Data Transfer
在 AWS 中，主要成本來自於運算資源（Compute）、儲存空間（Storage）以及資料傳輸至網際網路（Outbound Data Transfer）。
```

58.As per the **AWS Shared Responsibility Model**, which of the following is a **responsibility of AWS** from a **security and compliance** point of view?

```
Edge Location Management
根據 AWS 的共享責任模型，AWS 負責管理邊緣位置（Edge Locations）的實體安全和基礎設施維運，這屬於雲端供應商的責任範圍。
```

59.Which of the following are examples of **Horizontal Scalability** (aka Elasticity)? (Select two)

```
Read Replicas in Amazon Relational Database Service (Amazon RDS)
Elastic Load Balancing (ELB)
水平擴展（Horizontal Scalability） 是透過增加更多的實例來分散負載，例如使用 RDS Read Replicas 擴展讀取能力，以及使用 ELB 分發流量到多個 EC2 實例來處理更多請求。
```

60.Which AWS service publishes **up-to-the-minute information** on the general **status and availability** of **all AWS services** in **all the Regions** of AWS Cloud?

```
AWS Health Dashboard - service health
AWS Health Dashboard - service health 提供即時更新的 AWS 服務狀態資訊，涵蓋所有區域的服務可用性和事件通知。
```

61.As per the **AWS Shared Responsibility Model**, which of the following is a **responsibility of the customer** from a **security and compliance** point of view?

```
Managing patches of the guest operating system on Amazon Elastic Compute Cloud (Amazon EC2)
根據 AWS 共用責任模型，客戶負責管理 EC2 執行個體內部的作業系統，包括修補更新與安全設定。
```

62.An organization has a **complex IT architecture** involving a lot of system dependencies and it wants to **track the history of changes** to each resource. Which AWS service will help the organization track **the history of configuration changes** for all the **resources**?

```
AWS Config
AWS Config 可幫助追蹤 AWS 資源的設定變更歷史，並提供審計與合規所需的詳細記錄。
```

63.A gaming company is looking at a technology/service that can deliver a consistent **low-latency gameplay** to ensure a **great user experience** for **end-users in various locations**. Which AWS technology/service will provide the necessary low-latency access to the end-users?

```
AWS Local Zones
AWS Local Zones 將計算、儲存等服務部署在靠近終端用戶的地理位置，以降低延遲、提升使用者體驗，特別適合遊戲等對即時反應要求高的應用。
```

64.Which of the following statements are correct about the **AWS root user account**? (Select two)

```
It is highly recommended to enable Multi-Factor Authentication (MFA) for root user account
Root user access credentials are the email address and password used to create the AWS account
Root 使用者擁有帳戶的完全存取權限，為了安全應啟用 MFA，而其登入憑證是建立 AWS 帳戶時所用的電子郵件地址與密碼。
```

65.Which tool will help you **review your workloads** against current AWS **best practices** for **cost optimization**, **security**, and **performance improvement** and then obtain advice to **architect them better**?

```
AWS Trusted Advisor
AWS Trusted Advisor 會根據 AWS 最佳實踐，提供關於成本、安全性、效能等方面的檢查與建議，協助改善工作負載的架構。
```

66.The **AWS Cloud Adoption Framework (AWS CAF)** recommends four iterative and incremental **cloud transformation phases**. Which cloud transformation journey phase of the AWS Cloud Adoption Framework (AWS CAF) focuses on **demonstrating how the cloud will help accelerate your business outcomes**?

```
Envision
Envision 階段的重點是展示雲端如何協助企業加速實現業務成果，是 AWS CAF 轉型旅程的第一步。
```

67.**Access Key ID** and **Secret Access Key** are **tied to which of the following AWS Identity** and Access Management (AWS IAM) entities?

```
IAM User
Access Key ID 和 Secret Access Key 是專屬於 IAM User 的憑證，用來程式化地存取 AWS 資源。
```

68.Which AWS service can be used to **provision resources** to run **big data workloads** on **Hadoop clusters**?

```
Amazon EMR
Amazon EMR (Elastic MapReduce) 是 AWS 上的托管 Hadoop 框架，可快速且輕鬆地部署 Hadoop 叢集以處理大數據工作負載。
```

69.An IT company wants to **run a log backup process** **every Monday at 2 AM**. The usual **runtime of the process is 5 minutes**. As a Cloud Practitioner, which AWS services would you recommend to build a **serverless solution** for this use-case? (Select two)

```
Amazon Eventbridge
AWS Lambda
使用 Amazon EventBridge 設定排程事件觸發器，並透過 AWS Lambda 執行備份程式，可建構無伺服器的定時自動備份解決方案。
```

70.Which AWS support plan provides access to a designated **Technical Account Manager** (TAM)?

```
AWS Enterprise Support
AWS Enterprise Support 提供專屬的 Technical Account Manager (TAM)，協助客戶規劃與最佳化其 AWS 環境。
```

71.AWS **Compute Optimizer** delivers **recommendations** for which of the following **AWS resources**? (Select two)

```
Amazon Elastic Block Store (Amazon EBS), AWS Lambda functions
Amazon Elastic Compute Cloud (Amazon EC2) instances, Amazon EC2 Auto Scaling groups
AWS Compute Optimizer 提供針對 EC2 實例與 Auto Scaling 群組 的資源配置建議，幫助優化效能與成本。
```

72.Which policy describes **prohibited uses** of the **web services** offered by **Amazon Web Services**?

```
AWS Acceptable Use Policy
AWS Acceptable Use Policy 說明了客戶在使用 AWS 服務時 禁止的行為與用途，例如非法活動、濫用資源等。
```

73.Which AWS service can be used to **store**, **manage**, and **deploy Docker container images**?

```
Amazon Elastic Container Registry (Amazon ECR)
Amazon ECR 是一項 AWS 管理服務，可安全地儲存、管理與部署 Docker 映像檔，並與 ECS、EKS 等容器服務整合使用。
```

74.Which of the following AWS services allows a database to have **flexible schema** and **supports document data models**?

```
Amazon DynamoDB
Amazon DynamoDB 是一種 NoSQL 資料庫服務，支援彈性 schema，可儲存和查詢文件型資料模型如 JSON 格式的資料。
```

75.Which of the following solutions can you use to **connect your on-premises network** with AWS Cloud (Select two)?

```
AWS Direct Connect
AWS Virtual Private Network (VPN)
這兩項服務都可以安全地將本地資料中心連接到 AWS，Direct Connect 提供專線連接，VPN 則透過加密網路隧道連線。
```

76.The AWS Well-Architected Framework provides guidance on building cloud based applications using AWS best practices. Which of the following options are the **pillars mentioned in the AWS Well-Architected Framework**? (Select two)

```
Reliability
確保系統在錯誤發生後能快速恢復，具備彈性與容錯能力。
Cost Optimization
避免不必要支出，達成成本效益最大化。

AWS Well-Architected Framework 的五大支柱（Pillars
Operational Excellence
Security
Reliability
Performance Efficiency
Cost Optimization
```

77.A fleet of Amazon **EC2 instances spread across different Availability Zones (AZ)** needs to access, edit and share **file-based data stored** centrally on a system. As a Cloud Practitioner, which AWS service would you recommend for this use-case?

```
Amazon Elastic File System (Amazon EFS)
EFS 是最佳選擇，當你要讓多個 EC2 跨 AZ 共用可編輯的檔案系統。
```

78.Which Amazon Elastic Compute Cloud (Amazon EC2) pricing model is the **most cost-effective and flexible** with **no requirement for a long term resource commitment or upfront payment** but still guarantees that **instance would not be interrupted**?

```
On-demand Instance
On-Demand Instance 提供最大靈活性，無需預付費或長期承諾，且不會被中斷，非常適合不可預測或短期的工作負載。
```

79.What **foundational capability** under the **operations perspective** is part of the **AWS Cloud Adoption Framework (AWS CAF)**?

```
Performance and capacity management
在 AWS CAF 的 Operations Perspective 中，Performance and capacity management 是一項基礎能力，幫助企業確保資源運行效率與容量符合業務需求。
```

80.According to the AWS Shared Responsibility Model, which of the following are **responsibilities of the customer** for Amazon RDS?

```
Database encryption
在 Amazon RDS 中，客戶需負責資料加密與存取管理，而 AWS 則處理作業系統與資料庫平台的更新與硬體維運。
```

81.Which AWS service helps with **global application availability** and **performance** using the **AWS global network**?

```
AWS Global Accelerator
AWS Global Accelerator 利用 AWS 全球網路優化流量路由，提升應用的可用性與效能，確保使用者連線低延遲且穩定。
```

82.An organization is planning to move its infrastructure from the on-premises datacenter to AWS Cloud. As a Cloud Practitioner, which options would you **recommend** so that the organization can **identify the right AWS services** to **build solutions on AWS Cloud** (Select two)?

```
AWS Service Catalog
AWS Partner Network (APN)
AWS Service Catalog 幫助組織選擇和管理符合規範的 AWS 服務組合，AWS Partner Network 則提供專業合作夥伴協助選擇合適方案。
```

83.An e-commerce company wants to **assess its applications** deployed on **Amazon Elastic Compute Cloud (Amazon EC2)** instances for **vulnerabilities** and deviations from AWS **best practices**. Which AWS service can be used to facilitate this?

```
Amazon Inspector
Amazon Inspector 可自動掃描 EC2 實例中的應用程式，找出潛在漏洞與未符合 AWS 最佳實踐的地方
```

84.Which of the following statement is correct for a **Security Group** and a **Network Access Control List (Network ACL)**?

```
Security Group acts as a firewall at the instance level whereas Network Access Control List (Network ACL) acts as a firewall at the subnet level
Security Group 是作用在 單一 EC2 實例層級 的防火牆，而 Network ACL 是作用在 子網路層級 的防火牆。
```

85.Which Amazon **Route 53** **routing policy** would you use to **improve the performance** for your customers by routing the requests to the AWS endpoint that provides the fastest experience?

```
Latency-based routing
Latency-based routing 根據使用者到各區域 AWS 端點的延遲，將請求導向延遲最低的端點，以提供最佳效能。
```

86.Which of the following is the correct statement regarding the **AWS Storage services**?

```
Amazon Simple Storage Service (Amazon S3) is object based storage, Amazon Elastic Block Store (Amazon EBS) is block based storage and Amazon Elastic File System (Amazon EFS) is file based storage
S3、EBS 和 EFS 分別對應到物件、區塊與檔案儲存類型，這是 AWS 三大主要儲存服務的標準分類方式。
```

87.Due to regulatory and compliance reasons, an organization is supposed to use a **hardware device** for any **data encryption** operations in the cloud. Which AWS service can be used to meet this **compliance requirement**?

```
AWS CloudHSM
AWS CloudHSM 提供符合合規需求的硬體安全模組 (HSM)，可用於執行加密操作，確保資料加密在實體硬體上進行。
```

88.Which AWS service would you use to **send alerts** when the **costs for your AWS account exceed** your **budgeted amount**?

```
AWS Budgets
AWS Budgets 可讓你設定成本或使用量的預算，並在超出預算時自動發送警報通知。
```

89.Which of the following statement is correct regarding the **AWS pricing policy** for **data transfer** charges **into or out of** an AWS Region?

```
Only outbound data transfer is charged
AWS 僅對「從 AWS 雲端傳出的資料」收取費用，傳入資料（Inbound）一般是免費的。
```

90.Which AWS technology/service helps you to **scale your resources** to **match supply with demand** while still keeping your cloud solution **cost-effective**?

```
AWS Auto Scaling
AWS Auto Scaling 可根據需求自動增加或減少資源，確保應用程式效能並控制成本。
```

91.Which of the following AWS services is essential for **implementing** **security of resources** in AWS Cloud?

```
AWS Identity and Access Management (IAM)
IAM 可讓你控制誰可以存取 AWS 資源及其可執行的操作，是實現雲端資源安全性的核心服務。
```

92.A company is using a **message broker** service on its **on-premises** application and wants to **move this messaging functionality to AWS Cloud**. Which of the following AWS services is the right choice to move the existing functionality easily?

```
Amazon MQ
Amazon MQ 支援常見的開源訊息代理（如 ActiveMQ 和 RabbitMQ），可輕鬆遷移本地應用的訊息功能到 AWS，無需大量重構程式碼。
```

93.A startup is looking for **24x7 phone based technical support** for its AWS account. Which of the following is the **MOST cost-effective** AWS support plan for this use-case?

```
AWS Business Support
AWS Business Support 是提供 24x7 電話技術支援的最低層級方案，對需要全年無休協助的初創公司來說是最具成本效益的選擇。
```

94.**Multi-AZ deployment** is an example of which of the following?

```
High Availability
Multi-AZ（多可用區）部署透過在多個可用區間自動複製資料，確保在單一區域故障時服務仍可持續運行，是實現高可用性（High Availability）的典型方式。
```

95.Which of the following AWS services are **global in scope**? (Select two)

```
AWS Identity and Access Management (AWS IAM)
Amazon CloudFront
IAM 和 CloudFront 是全域服務，IAM 的身分與權限可在所有區域中使用，而 CloudFront 是全球內容交付網路（CDN），能將內容分發到世界各地的邊緣位置。
```

96.Which of the following AWS services can be used to **prevent Distributed Denial-of-Service (DDoS) attack**? (Select three)

```
AWS Shield
AWS Web Application Firewall (AWS WAF)
Amazon CloudFront with Amazon Route 53
AWS Shield 提供 DDoS 保護，WAF 可過濾惡意請求，而 CloudFront 與 Route 53 有助於分散流量、降低攻擊影響，共同構成多層防禦機制。
```

97.Which AWS service enables users to **find, buy, and immediately start using software solutions in their AWS environment**?

```
AWS Marketplace
AWS Marketplace 是一個線上市集，讓使用者可以輕鬆尋找、購買並快速在 AWS 環境中部署軟體解決方案。
```

98.Which of the following AWS services comes under the **Software as a Service (SaaS)** **Cloud Computing Type**?

```
Amazon Rekognition
Amazon Rekognition 是一項 SaaS 服務，讓開發者透過 API 直接使用影像和影片分析功能，無需管理底層基礎設施或訓練機器學習模型。
```

99.Which characteristic of Cloud Computing imparts the ability to **acquire resources as you need** and **release when you no longer need them**?

```
Elasticity
Elasticity 是雲端運算的特性，允許根據需求自動擴展或縮減資源，達到高效且具成本效益的運算資源管理。
```

100.A photo sharing web application wants to store thumbnails of user-uploaded images on Amazon Simple Storage Service (Amazon S3). The thumbnails are **rarely used** but need to be **immediately accessible** from the web application. The thumbnails **can be regenerated easily** if they are lost. Which is the **most cost-effective** way to store these thumbnails on Amazon Simple Storage Service (Amazon S3)?

```
Use Amazon S3 One Zone-Infrequent Access (S3 One Zone-IA) to store the thumbnails
Amazon S3 One Zone-IA 提供低成本儲存，適用於不常使用但仍需即時存取、且資料可輕易重建的場景，非常適合用來儲存可再生的縮圖。
```

101.A customer has created a VPC and a subnet within AWS Cloud. Which of the following statements is correct?

```
An Amazon Virtual Private Cloud (Amazon VPC) spans all of the Availability Zones (AZ) in the Region whereas a subnet spans only one Availability Zone (AZ) in the Region
VPC 是整個區域內的虛擬網路，可跨多個可用區域，而子網路（Subnet）則限制在特定的單一可用區域內。
```

102.The engineering team at an IT company wants to **monitor the CPU utilization** for its fleet of Amazon Elastic Compute Cloud (Amazon EC2) instances and **send an email** to the administrator if the utilization exceeds 80%. As a Cloud Practitioner, which AWS services would you recommend to build this solution? (Select two)

```
Amazon Simple Notification Service (SNS)
Amazon CloudWatch
使用 CloudWatch 監控 EC2 CPU 使用率，當超過門檻時觸發警報，並透過 SNS 發送電子郵件通知管理員。
```

103.Which AWS compute service provides the **EASIEST way to access resizable compute capacity** in the cloud with support for **per-second billing** and **access to the underlying OS**?

```
Amazon Elastic Compute Cloud (Amazon EC2)
Amazon EC2 提供彈性可調整的計算資源，支援按秒計費，並允許使用者存取並管理底層作業系統。
```

104.A company wants a **fully managed**, **flexible**, and **scalable file storage system**, with **low latency access**, for its **Windows-based applications**. Which AWS service is the right choice for the company?

```
Amazon FSx for Windows File Server
Amazon FSx for Windows File Server 是專為 Windows 應用設計的全託管、高彈性、低延遲的檔案儲存服務。
```

105.A data analytics company stores its data on **Amazon Simple Storage Service (Amazon S3)** and wants to do **SQL based analysis** on this data with **minimum effort**. As a Cloud Practitioner, which of the following AWS services will you suggest for this use case?

```
Amazon Athena
Amazon Athena 是一項互動式查詢服務，可讓使用者用 SQL 直接查詢儲存在 Amazon S3 上的資料，無需設定伺服器，簡單又高效。
```

106.Which of the following statements are true about **AWS Lambda**? (Select two)

```
AWS Lambda lets you run code without provisioning or managing servers
You pay for the compute time you consume for AWS Lambda
AWS Lambda 是無伺服器運算服務，用戶只需撰寫程式碼即可執行，費用依實際使用的運算時間計費，無需預先佈建資源。
```

107.A social media company wants to **protect its web application** from common web exploits such as **SQL injection** and **cross-site scripting**. Which of the following AWS services can be used to address this use-case?

```
AWS Web Application Firewall (AWS WAF)
AWS WAF 可協助保護 Web 應用程式免於常見的攻擊，例如 SQL 注入與跨站腳本（XSS），強化應用程式安全性。
```

108.Which AWS service should be used when you want to **run container applications**, but want to **avoid the operational** **overhead of scaling, patching, securing, and managing servers**?`

```
Amazon Elastic Container Service (Amazon ECS) - Fargate launch type
Amazon ECS 的 Fargate 啟動類型讓你無需管理伺服器即可執行容器，省去擴展、修補與維護的作業負擔。
```

109.A retail company has **multiple AWS accounts** for each of its departments. Which of the following AWS services can be used to set up **consolidated billing** and a **single payment method** for these AWS accounts?

```
AWS Organizations
AWS Organizations 可讓你集中管理多個 AWS 帳號，支援合併帳單與統一付款方式，方便成本控管與帳號治理。
```

110.What is the primary benefit of deploying an Amazon RDS **Multi-AZ database** with **one standby**?

```
Amazon RDS Multi-AZ enhances database availability
Amazon RDS Multi-AZ 在主可用區失效時自動切換到備援資料庫，確保高可用性並減少應用程式中斷。
```

111.A company's flagship application runs on a fleet of Amazon Elastic Compute Cloud (Amazon EC2) instances. As per the new policies, the system administrators are looking for the best way to **provide secure shell access** to Amazon Elastic Compute Cloud (Amazon EC2) instances **without opening new ports or using public IP addresses**. Which tool/service will help you achieve this requirement?

```
AWS Systems Manager Session Manager
Session Manager 提供安全的 shell 存取 EC2 實例功能，無需開啟埠口或使用公有 IP，符合零信任安全原則。
```

112.What are the different **gateway types** supported by **AWS Storage Gateway** service?

```
Tape Gateway, File Gateway and Volume Gateway
AWS Storage Gateway 支援三種閘道類型：Tape Gateway 用於備份整合、File Gateway 提供 NFS/SMB 存取 S3、Volume Gateway 用於區塊儲存與本地快取。
```

113.An organization deploys its IT infrastructure in a **combination** of its **on-premises data center** along with AWS Cloud. How would you categorize this deployment model?

```
Hybrid deployment
當組織同時使用本地資料中心與 AWS 雲端資源來部署其 IT 基礎設施時，這種模式稱為 Hybrid deployment（混合部署）。
```

114.Which of the following options can be used to **access and manage all AWS services** (Select three)?

```
AWS Software Development Kit (SDK)
AWS Command Line Interface (AWS CLI)
AWS Management Console
AWS 提供 SDK、CLI 和管理控制台三種主要方式，讓開發者或使用者能以程式碼、命令列或圖形介面來存取與管理所有 AWS 服務。
```

115.Which service gives a **personalized view** of the **status of the AWS services** that are part of your Cloud architecture so that you can quickly assess the **impact on your business** when AWS service(s) are experiencing issues?

```
AWS Health - Your Account Health Dashboard
AWS Health 提供針對您帳戶架構中使用的 AWS 服務狀態的個人化視圖，幫助您快速評估服務中斷對業務的影響。
```

116.A research group wants to provision an Amazon Elastic Compute Cloud (Amazon EC2) instance for a **flexible application** that **can be interrupted**. As a Cloud Practitioner, which of the following would you recommend as the MOST **cost-optimal** option?

```
Spot Instance
Spot Instance 可提供高達 90% 的成本節省，適合容許中斷的彈性工作負載，例如批次處理或研究運算，非常適合預算敏感的應用場景。
```

117.An IT company is on a **cost-optimization** spree and wants to **identify all Amazon Elastic Compute Cloud (Amazon EC2) instances that are under-utilized**. Which AWS services can be used off-the-shelf to address this use-case **without needing any manual configurations**? (Select two)

```
AWS Trusted Advisor
AWS Cost Explorer
AWS Trusted Advisor 提供最佳實踐建議，包括找出低使用率的 EC2 實例，而 AWS Cost Explorer 則可視覺化資源使用趨勢並分析成本，兩者都能無需手動設定即可協助節省資源。
```

118.An organization maintains separate Amazon Virtual Private Clouds (Amazon VPC) for each of its departments. With expanding business, the organization now wants to **connect all Amazon Virtual Private Clouds** (Amazon VPC) for better departmental collaboration. Which AWS service will help the organization tackle the issue effectively?

```
AWS Transit Gateway
AWS Transit Gateway 可讓多個 VPC 和本地網路經由一個集中的 gateway 相互連接，提供更簡潔、可擴展的網路架構，非常適合多部門或多帳號的環境。這樣可避免建立多條 VPC 對等連線（VPC Peering）造成的複雜性，提升跨部門協作的效率。
```

119.Which of the following AWS services specialize in **data migration** from **on-premises to AWS Cloud**? (Select two)

```
AWS Snowball
AWS Database Migration Service (AWS DMS)
AWS Snowball 用於大規模實體資料傳輸，而 AWS DMS 則專注於資料庫的遷移，兩者皆適用於將資料從本地移至 AWS 雲端。
```

120.A startup runs its proprietary application **on docker containers**. As a Cloud Practitioner, which AWS service would you recommend so that the startup can run containers and still have **access to the underlying servers**?

```
Amazon Elastic Container Service (Amazon ECS)
Amazon ECS 支援 Docker 容器的部署，並且允許你使用 EC2 launch type，讓開發人員能夠管理並存取底層伺服器。
```

121.Which Amazon **Route 53** **routing policy** would you use when you want to route your traffic in an **active-passive configuration**?

```
Failover routing
Failover routing policy 允許你設定主動（active）和被動（passive）的資源，在主要資源失效時自動將流量導向備援資源。
```

122.Which of the following is a part of the **AWS Global Infrastructure**?

```
AWS Region
AWS Region 是 AWS 全球基礎設施的一部分，每個 Region 包含多個可用區域（Availability Zones），用於部署應用並實現高可用性與容錯能力。
```

123.Which AWS service **protects your AWS account** by **monitoring malicious activity** and **detecting threats**?

```
Amazon GuardDuty
Amazon GuardDuty 是一項威脅偵測服務，能夠持續監控您的 AWS 環境以發現惡意活動和可疑行為，幫助您保護帳戶和資源安全。
```

124.An IT company has a **hybrid cloud architecture** and it wants to **centralize the server logs** for its **Amazon Elastic Compute Cloud (Amazon EC2) instances and on-premises servers**. Which of the following is the MOST effective for this use-case?

```
Use Amazon CloudWatch Logs for both the Amazon Elastic Compute Cloud (Amazon EC2) instance and the on-premises servers
Amazon CloudWatch Logs 支援從 AWS EC2 和本地伺服器收集與集中日誌資料，是集中管理混合雲環境日誌的最有效方式。
```

125.Which of the following **AWS services** are **regional in scope**? (Select two)

```
AWS Lambda
Amazon Rekognition
AWS Lambda 和 Amazon Rekognition 是 區域性 (regional) 服務，它們在特定的 AWS 區域內運作，使用時需選擇部署區域。
```

126.A financial services company must meet **compliance requirements** that mandate storing **multiple copies** of data in **geographically distant locations**. As the company uses **Amazon Simple Storage Service (Amazon S3)** as its main storage service, which of the following represents the MOST resource-efficient solution for this use-case?

```
Use S3 cross-region replication (S3 CRR) to replicate data between distant AWS Regions
S3 Cross-Region Replication（CRR）可自動將資料從一個 AWS 區域的 S3 儲存桶複製到另一個區域，滿足合規要求並實現地理冗餘。
```

127.An IT company would like to **move its IT resources** (including any data and applications) from **an AWS Region in the US to another AWS Region in Europe**. Which of the following represents the correct solution for this use-case?

```
The company should just start creating new resources in the destination AWS Region and then migrate the relevant data and applications into this new AWS Region
AWS 資源是區域性（regional）的，無法直接跨區域移動，正確做法是手動在目標區域重建資源並遷移資料和應用程式。
```
