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
