1.A company has petabytes of **unlabeled customer data** to use for an advertisement campaign. The company wants to classify its customers into tiers to advertise and promote the company's products. Which methodology should the company use to meet these requirements?

```
Unsupervised learning
沒有標籤（答案）時，就用無監督學習。
```

2.A company makes **forecasts** each quarter to decide how to optimize operations to meet expected demand. The company uses **ML models** to make these forecasts. An AI practitioner is writing a report about the trained ML models to provide transparency and explainability to company stakeholders. What should the AI practitioner include in the report to meet the **transparency** and **explainability** requirements?

```
Partial dependence plots (PDPs)
PDPs 解釋模型怎麼根據特徵做出預測，符合解釋需求。
```

3.An AI practitioner is using a **large language model (LLM)** to create content for marketing campaigns. The **generated content** **sounds plausible and factual but is incorrect**. Which problem is the LLM having?

```
Hallucination
這是 LLM 捏造資訊（幻覺) 的典型現象，看起來對其實是錯的。
```

4.A company is building an application that needs to **generate synthetic data** that is based on **existing data**. Which type of model can the company use to meet this requirement?

```
Generative adversarial network (GAN)
GAN 是專門用來根據現有資料生成逼真的新資料的模型。
```

5.What are tokens in the context of generative AI models?

```
Tokens are the basic units of input and output that a generative AI model operates on, representing words, subwords, or other linguistic units.
Tokens 是生成式 AI 模型運作的基本單位，可以是單詞、子詞或其他語言單位。
```

6.A company is using domain-specific models. The company wants to avoid creating new models from the beginning. The company instead wants to **adapt pre-trained models** to create models for new, related tasks. Which ML strategy meets these requirements?

```
Use transfer learning.
Transfer learning 是利用預訓練模型，將其調整應用到新任務，避免從零開始訓練模型。
```

7.A company built a deep learning model for object detection and deployed the model to production. Which AI process occurs when the model **analyzes a new image** to **identify objects**?

```
Inference
Inference 是模型在生產環境中使用時進行的過程，分析新資料並做出預測或識別
```

8.A company is developing a new model to predict the prices of specific items. The model performed well on the **training** dataset. When the company deployed the model to production, the model's **performance decreased** significantly. What should the company do to mitigate this problem?

```
Increase the volume of data that is used in training.
模型在生產環境表現不佳，通常是因為訓練資料不足，增加訓練資料量可以改善模型的泛化能力，從而提升預測效果。
```

9.A company is building a chatbot to improve user experience. The company is using a large language model (LLM) from Amazon Bedrock for intent detection. The company wants to use **few-shot learning** to improve intent detection accuracy. Which additional data does the company need to meet these requirements?

```
Pairs of user messages and correct user intents
Few-shot learning 需要用少量示例來學習，這些示例應該包含用戶消息和正確的用戶意圖，以提升意圖檢測的準確度。
```

10.A company is **training** a foundation model (FM). The company wants to increase the accuracy of the model up to a specific **acceptance** level. Which solution will meet these requirements?

```
Increase the epochs.
增加訓練輪次（epochs）可以讓模型訓練得更充分，通常能提高準確度。
```

11.A company wants to use **generative AI** to increase **developer productivity** and software development.The company wants to use Amazon Q Developer. What can Amazon Q Developer do to help the company meet these requirements?

```
Enable voice commands for coding and providing natural language search.
Amazon Q Developer 可以通過語音命令和自然語言搜尋來協助開發者，提高生產力和編程效率。
```

12.A law firm wants to build an AI application by using large language models (LLMs). The application will read legal documents and **extract key points** from the documents. Which solution meets these requirements?

```
Develop a summarization chatbot.
摘要型聊天機器人能夠提取法律文件中的關鍵信息並進行簡要概括，非常適合用於處理和理解法律文檔中的重點。
```

13.A company has terabytes of data in a database that the company can use for **business analysis**. The company wants to build an AI-based application that can **build a SQL query** from input text that employees provide. The employees have minimal experience with technology. Which solution meets these requirements?

```
Generative pre-trained transformers (GPT)
生成式預訓練轉換器（GPT）能根據員工的自然語言輸入自動生成 SQL 查詢，這對於技術經驗較少的員工非常有用。
```

14.A company manually reviews all submitted resumes in **PDF format**. As the company grows, the company expects the volume of resumes to exceed the company's review capacity. The company needs an automated system to convert the** PDF resumes** into plain text format for additional processing. Which AWS service meets this requirement?

```
Amazon Textract
Amazon Textract 是一個能夠自動提取文本和數據的服務，特別適合從 PDF 文檔中提取簡歷中的信息並轉換為純文本格式。
```

15.A medical company deployed a disease detection model on Amazon Bedrock. To comply with privacy policies, the company wants to prevent the model from including personal patient information in its responses. The company also wants to receive notification when policy violations occur. Which solution meets these requirements?

```
Use Guardrails for Amazon Bedrock to filter content. Set up Amazon CloudWatch alarms for notification of policy violations.
使用 Amazon Bedrock 的 Guardrails 來過濾內容並防止敏感資訊被模型包含，同時透過 Amazon CloudWatch 設定警報來通知政策違規。
```

16.An e-commerce company wants to build a solution to determine customer sentiments based on written customer reviews of products. Which AWS services meet these requirements? (Select TWO.)

```
Amazon Comprehend
Amazon Bedrock
Amazon Comprehend 能進行情緒分析，適合從客戶評論中提取情感；Amazon Bedrock 可幫助建立基於 AI 的解決方案，進一步優化情緒分析模型。
```

17.A company wants to use a large language model (LLM) on Amazon Bedrock for sentiment analysis. The company wants to classify the sentiment of text passages as positive or negative. Which prompt engineering strategy meets these requirements?

```
Provide examples of text passages with corresponding positive or negative labels in the prompt followed by the new text passage to be classified.
提供帶有正面或負面標籤的文本範例，讓模型理解如何分類情緒，並將新的文本段落進行分類。
```

18.A company has thousands of customer support interactions per day and wants to analyze these interactions to identify frequently asked questions and develop insights. Which AWS service can the company use to meet this requirement?

```
Amazon Comprehend
Amazon Comprehend 是用來進行自然語言處理的服務，能從文字中萃取關鍵字、情緒和主題，適合分析客服內容找出常見問題與洞察。
```

19.Which feature of Amazon OpenSearch Service gives companies the ability to build vector database applications?

```
Scalable index management and nearest neighbor search 建立向量資料庫應用需要最近鄰搜尋（Nearest Neighbor Search）和可擴展索引管理，這是實作語意搜尋或推薦系統的關鍵功能。
```

20.A company wants to find groups for its customers based on the customers’ demographics and buying patterns. Which algorithm should the company use to meet this requirement?

```
K-means
K-means 是常用的非監督式學習演算法，適合用來將資料依相似性分群，例如顧客分群（customer segmentation）。
```

21.An AI company periodically evaluates its systems and processes with the help of independent software vendors (ISVs). The company needs to receive email message notifications when an ISV's compliance reports become available. Which AWS service can the company use to meet this requirement?

```
AWS Artifact
AWS Artifact 是用來存取合規性報告與文件的服務，支援訂閱通知，能在報告更新時發送 Email。
```

22.A company wants to use a large language model (LLM) to develop a conversational agent. The company needs to prevent the LLM from being manipulated with common prompt engineering techniques to perform undesirable actions or expose sensitive information. Which action will reduce these risks?

```
Create a prompt template that teaches the LLM to detect attack patterns.
教導 LLM 偵測常見攻擊提示的模式，有助於提升其對 prompt injection 的抵抗力，是實作對話安全防護的策略之一。
```

23.A company is using the Generative AI Security Scoping Matrix to assess security responsibilities for its solutions. The company has identified four different solution scopes based on the matrix. Which solution scope gives the company the  **MOST** ownership of security responsibilities?

```
Building and training a generative AI model from scratch by using specific data that a customer **owns.**
從零開始訓練模型並使用自有資料，意味著公司需負責資料治理、模型安全、訓練環境與部署所有層面的安全，責任最大。
```

24.A company wants to create an application by using Amazon Bedrock. The company has a limited budget and prefers flexibility without long-term commitment. Which Amazon Bedrock pricing model meets these requirements?`

```
On-Demand
On-Demand 模式讓公司按使用量付費，無需預付費用或簽訂長期合約，是預算有限又重視彈性的首選方案。
```

25.An AI practitioner is building a model to generate images of humans in various professions. The AI practitioner discovered that the input data is biased and that specific attributes affect the image generation and create bias in the model. Which technique will solve the problem?

```
Data augmentation for imbalanced classes
資料增強（Data augmentation）可用於擴充欠缺樣本的類別，平衡訓練資料分布，進而降低模型偏見。
```

26.A medical company is customizing a foundation model (FM) for diagnostic purposes. The company needs the model to be transparent and explainable to meet regulatory requirements. Which solution will meet these requirements?

```
Generate simple metrics, reports, and examples by using Amazon SageMaker Clarify.
Amazon SageMaker Clarify 提供模型偏差偵測與可解釋性報告，協助滿足監管對透明度與解釋性的要求。
```

27.Which option is a use case for generative AI models?

```
Creating photorealistic images from text descriptions for digital marketing
生成式 AI 最常見的應用之一是根據文字描述生成逼真的圖像，廣泛用於數位行銷與內容創作。
```

28.A pharmaceutical company wants to analyze user reviews of new medications and provide a concise overview for each medication. Which solution meets these requirements?

```
Create medication review summaries by using Amazon Bedrock large language models (LLMs).
使用 Amazon Bedrock 的大型語言模型來自動摘要用戶評論，能快速產生精簡且準確的藥物概述。
```

29.A company wants to use large language models (LLMs) to produce code from natural language code comments. Which LLM feature meets these requirements?

```
B. Text generation
Text generation 是指從輸入的文字（如自然語言註解）生成新的文字內容（如程式碼），符合此需求。
```

30.A company is using Retrieval Augmented Generation (RAG) with Amazon Bedrock and Stable Diffusion to generate product images based on text descriptions. The results are often random and lack specific details. The company wants to increase the specificity of the generated images. Which solution meets these requirements?

```
Increase the classifier-free guidance (CFG) scale.
增加 CFG scale 可以讓模型更嚴格地遵循提示內容，提高圖像的細節和準確度，減少隨機性。
```

31.A company has documents that are missing some words because of a database error. The company wants to build an ML model that can suggest potential words to fill in the missing text. Which type of model meets this requirement?

```
BERT-based models
BERT 是預訓練的語言模型，擅長理解上下文並預測缺失詞彙，適合填補文本中的空缺。
```

32.A research company implemented a chatbot by using a foundation model (FM) from Amazon Bedrock. The chatbot searches for answers to questions from a large database of research papers. After multiple prompt engineering attempts, the company notices that the FM is performing poorly because of the complex scientific terms in the research papers. How can the company improve the performance of the chatbot?

```
Use domain adaptation fine-tuning to adapt the FM to complex scientific terms.
透過領域適應微調（domain adaptation fine-tuning）讓模型學習專業術語，提升其在該專業領域的理解和回答準確度。
```

33.Which term describes the numerical representations of real-world objects and concepts that AI and natural language processing (NLP) models use to improve understanding of textual information?

```
Embeddings
Embeddings 是將文字、物件或概念轉換成向量的數值表示，幫助模型更有效理解與處理語意。
```

34.A company is using a large language model (LLM) on Amazon Bedrock to build a chatbot. The chatbot processes customer support requests. To resolve a request, the customer and the chatbot must interact a few times. Which solution gives the LLM the ability to use content from previous customer messages?

```
B. Add messages to the model prompt.
將歷史訊息加入模型提示中，讓 LLM 能基於上下文持續對話，保持連貫。
```

35.A company is using few-shot prompting on a base model that is hosted on Amazon Bedrock. The model currently uses 10 examples in the prompt. The model is invoked once daily and is performing well. The company wants to lower the monthly cost. Which solution will meet these requirements?

```
Decrease the number of tokens in the prompt.
減少提示中的 token 數量可以直接降低計費，因為大多數 LLM 按輸入字元計費。
```

36.A company’s large language model (LLM) is experiencing hallucinations. How can the company decrease hallucinations?

```
Decrease the temperature inference parameter for the model.
降低 temperature 參數可以使模型生成結果更保守、穩定，減少不準確或虛構資訊（hallucinations）。C
```

37.An e-commerce company is using a generative AI chatbot to respond to customer inquiries. The company wants to measure the financial effect of the chatbot on the company’s operations. Which metric should the company use?

```
Cost for each customer conversation
直接衡量每次客戶對話成本，最能反映聊天機器人對財務的實際影響。
```

38.Which strategy will determine if a foundation model (FM) effectively meets business objectives?

```
Assess the model's alignment with specific use cases.
評估模型是否符合特定業務需求，才能確定它是否有效達成目標。
```

39.A software company builds tools for customers. The company wants to use AI to increase software development productivity. Which solution will meet these requirements?

```
Install code recommendation software in the company's developer tools.
直接在開發工具中安裝程式碼推薦軟體，能提升開發者效率和生產力。
```

40.A company wants to assess the costs that are associated with using a large language model (LLM) to generate inferences. The company wants to use Amazon Bedrock to build generative AI applications. Which factor will drive the inference costs?

```
Number of tokens consumed
推論成本通常依消耗的 token 數量計算，token 用越多，成本越高。
```

41.Which strategy evaluates the accuracy of a foundation model (FM) that is used in image classification tasks?

```
Measure the model's accuracy against a predefined benchmark dataset.
透過預先定義的基準資料集來衡量模型準確度，是評估影像分類模型效能的標準方法。
```

42.An education provider is building a question and answer application that uses a generative AI model to explain complex concepts. The education provider wants to automatically change the style of the model response depending on who is asking the question. The education provider will give the model the age range of the user who has asked the question. Which solution meets these requirements with the LEAST implementation effort?

```
Add a role description to the prompt context that instructs the model of the age range that the response should target.
透過在 prompt 裡加上角色描述告訴模型要對應哪個年齡層，成本最低且不需重新訓練模型。
```

43.A company wants to use a large language model (LLM) on Amazon Bedrock for sentiment analysis. The company needs the LLM to produce more consistent responses to the same input prompt. Which adjustment to an inference parameter should the company make to meet these requirements?

```
Decrease the temperature value.
降低 temperature 會減少隨機性，讓模型回應更穩定一致。
```

44.A data scientist has been running an Amazon SageMaker notebook instance for a few weeks. During this time, a new version of Jupyter Notebook was released along with additional software updates. The security team mandates that all running SageMaker notebook instances use the latest security and software updates provided by SageMaker. How can the data scientist meet this requirements?

```
Stop and then restart the SageMaker notebook instance
停止並重新啟動 Notebook instance，會自動載入最新的軟體和安全更新，是官方推薦方式。
```

45.A company uses Amazon SageMaker for its ML pipeline in a production environment. The company has large input data sizes up to 1 GB and processing times up to 1 hour. The company needs near real-time latency. Which SageMaker inference option meets these requirements?

```
Asynchronous inference
設計來處理較大資料量和較長處理時間的推理請求，客戶端送出請求後不需要等待結果，結果會透過輪詢或事件通知回傳。延遲比 Batch transform 低，更接近實時。
```

46.A company wants to build an ML model by using Amazon SageMaker. The company needs to share and manage variables for model development across multiple teams. Which SageMaker feature meets these requirements?

```
Amazon SageMaker Feature Store
這是用來集中管理和分享機器學習特徵（features）的服務，能讓多個團隊在模型訓練和推理時共享相同的特徵資料，符合題意。
```

47.A company wants to use generative AI to increase developer productivity and software development. The company wants to use Amazon Q Developer. What can Amazon Q Developer do to help the company meet these requirements?

```
Create software snippets, reference tracking, and open source license tracking.
這項功能和開發者寫程式有直接關係，能幫助快速生成程式碼片段，追蹤程式碼參考和管理開源授權，是提升軟體開發效率的好幫手。
```

48.A company is building a contact center application and wants to gain insights from customer conversations. The company wants to analyze and extract key information from the audio of the customer calls. Which solution meets these requirements?

```
Transcribe call recordings by using Amazon Transcribe.
這正是用來將語音轉成文字的服務，適合把通話錄音轉成文字稿，後續才能分析。
```

49.A company has developed an ML model for image classification. The company wants to deploy the model to production so that a web application can use the model. The company needs to implement a solution to host the model and serve predictions without managing any of the underlying infrastructure. Which solution will meet these requirements?

```
Use Amazon SageMaker Serverless Inference to deploy the model.
這是 SageMaker 提供的無伺服器推理服務，能夠在沒有管理伺服器的情況下部署和自動擴縮模型，非常適合需求。A
```

50.A company wants to use large language models (LLMs) with Amazon Bedrock to develop a chat interface for the company's product manuals. The manuals are stored as PDF files. Which solution meets these requirements MOST cost-effectively?

```
Upload PDF documents to an Amazon Bedrock knowledge base. Use the knowledge base to provide context when users submit prompts to Amazon Bedrock.
將 PDF 文件上傳到一個知識庫，然後在使用者提問時，模型能從知識庫檢索相關內容並作為上下文使用，這是典型的 Retrieval Augmented Generation (RAG) 模式，既節省成本又提升效能。
```

51.A company needs to build its own large language model (LLM) based on only the company's private data. The company is concerned about the environmental effect of the training process. Which Amazon EC2 instance type has the LEAST environmental effect when training LLMs?

```
Amazon EC2 Trn series
Amazon 專為機器學習訓練設計的定制晶片，功耗低、效能高，具備更好的能源效率和環保效益。
```

52.Which strategy evaluates the accuracy of a foundation model (FM) that is used in image classification tasks?

```
Measure the model's accuracy against a predefined benchmark dataset.
準確度的評估通常透過將模型在已標記的標準測試集（benchmark dataset）上進行推論，然後計算模型預測結果與真實標籤之間的一致性（accuracy、precision、recall等指標）來完成。
```

53.Which option is a benefit of ongoing pre-training when fine-tuning a foundation model (FM)?

```
Improves model performance over time
持續的預訓練能讓模型隨著新數據更新，提升其表現。
```

54.An AI practitioner wants to use a foundation model (FM) to design a search application. The search application must handle queries that have text and images. Which type of FM should the AI practitioner use to power the search application?

```
Multi-modal embedding model
多模態嵌入模型能同時處理文字和圖片，適合用於融合多種輸入的搜尋應用。
```

55.A company wants to make a chatbot to help customers. The chatbot will help solve technical problems without human intervention. The company chose a foundation model (FM) for the chatbot. The chatbot needs to produce responses that adhere to company tone. Which solution meets these requirements?

```
Experiment and refine the prompt until the FM produces the desired responses.
透過調整與優化提示詞（prompt），可以引導模型生成符合公司語調和風格的回答，達成定制化效果。
```

56.Which AWS service or feature can help an AI development team quickly deploy and consume a foundation model (FM) within the team's VPC?

```
Amazon SageMaker endpoints
SageMaker endpoints 可在團隊的 VPC 內快速部署並調用基礎模型 (FM)，支援安全且可擴展的模型推理服務。
```

57.A company wants to build a generative AI application by using Amazon Bedrock and needs to choose a foundation model (FM). The company wants to know how much information can fit into one prompt. Which consideration will inform the company's decision?

```
Context window
Context window 決定一次提示中可包含的最大 token 數量，直接影響能輸入多少資訊給模型
```

58.A company is implementing the Amazon Titan foundation model (FM) by using Amazon Bedrock. The company needs to supplement the model by using relevant data from the company's private data sources. Which solution will meet this requirement?

```
Create an Amazon Bedrock knowledge base
Knowledge base 可讓 FM 存取並參考公司私有資料，實現 RAG（retrieval-augmented generation）能力來補充回應內容。
```

59.A company uses a foundation model (FM) from Amazon Bedrock for an AI search tool. The company wants to fine-tune the model to be more accurate by using the company's data. Which strategy will successfully fine-tune the model?

```
Provide labeled data with the prompt field and the completion field.
微調（fine-tuning）需要結構化的訓練資料，其中每筆資料需包含 **prompt（輸入）** 與對應的 **completion（期望輸出）**，以幫助模型學習特定任務或語氣風格。
```

60.A company is using a pre-trained large language model (LLM) to build a chatbot for product recommendations. The company needs the LLM outputs to be short and written in a specific language. Which solution will align the LLM response quality with the company's expectations?

```
Adjust the prompt.
透過提示工程（prompt engineering）來明確要求輸出語言和字數限制，是控制 LLM 輸出風格與品質最直接有效的方法。
```

61.A company wants to use a large language model (LLM) on Amazon Bedrock for sentiment analysis. The company wants to classify the sentiment of text passages as positive or negative. Which prompt engineering strategy meets these requirements?

```
Provide examples of text passages with corresponding positive or negative labels in the prompt followed by the new text passage to be classified.
提供範例能幫助模型理解分類邏輯，提高準確率。
```

62.A marketing company wants to generate personalized product descriptions for an ecommerce client's website. Which prompt engineering technique will meet these requirements with the LEAST operational effort?

```
Zero-shot prompting without any examples.
Zero-shot 提示不需要準備訓練資料或範例，是操作最少的方式，適合快速產出初步內容。
```

63.A company wants to use a pre-trained generative AI model to generate content for its marketing campaigns. The company needs to ensure that the generated content aligns with the company's brand voice and messaging requirements. Which solution meets these requirements?

```
Create effective prompts that provide clear instructions and context to guide the model's generation.
使用明確的提示可直接控制生成內容風格與語調，無需重新訓練，既有效又省時。C
```

64.A company notices that its foundation model (FM) generates images that are unrelated to the prompts. The company wants to modify the prompt techniques to decrease unrelated images. Which solution meets these requirements?

```
Use negative prompts.
負面提示明確告訴模型「不要產生什麼」，可幫助排除不想要的內容，提升生成的相關性。
```

65.Which prompting technique can protect against prompt injection attacks?

```
Adversarial prompting
對抗式提示模擬潛在攻擊，幫助測試和強化模型對惡意輸入的抵抗力。
```

66.A company wants to use an LLM to generate step-by-step instructions for assembling a product. The model must reason through the process of assembly to generate logical instructions that align with each step. Which prompt engineering technique is best suited for this task?

```
Chain-of-thought prompting to guide the model through the reasoning process for each assembly step.
連鎖思考提示幫助模型分解複雜過程，確保生成的指示符合邏輯順序。
```

67.A company wants to use language models to create an application for inference on edge devices. The inference must have the lowest latency possible. Which solution will meet these requirements?

```
Deploy optimized small language models (SLMs) on edge devices.
小型語言模型體積小、運算快，適合在邊緣設備本地執行以降低延遲。
```

68.A company wants to implement a large language model (LLM) based chatbot to provide customer service agents with real-time contextual responses to customers' inquiries. The company will use the company's policies as the knowledge base. Which solution will meet these requirements MOST cost-effectively?

```
Implement Retrieval Augmented Generation (RAG) for in-context responses.
RAG 結合檢索和生成，不需昂貴的微調，能即時且精準回應，成本最低。
```

69.Which metric measures the runtime efficiency of operating AI models?

```
Average response time
平均回應時間直接反映模型在推論時的速度與效率，是衡量運行效率的關鍵指標。
```

70.A company wants to build a generative AI application by using Amazon Bedrock and needs to choose a foundation model (FM). The company wants to know how much information can fit into one prompt. Which consideration will inform the company's decision?

```
Context window
上下文視窗決定模型一次能處理的最大文字長度，也就是提示可容納的資訊量。B
```

71.A company is building a large language model (LLM) question answering chatbot. The company wants to decrease the number of actions call center employees need to take to respond to customer questions. Which business objective should the company use to evaluate the effect of the LLM chatbot?

```
Average call duration
平均通話時間縮短表示客服效率提升，反映聊天機器人減少客服工作負擔的效果。
```

72.A company needs to choose a model from Amazon Bedrock to use internally. The company must identify a model that generates responses in a style that the company's employees prefer. What should the company do to meet these requirements?

```
Evaluate the models by using a human workforce and custom prompt datasets.
人工評估搭配自訂資料能確保模型回應符合員工實際偏好，比純自動或公有排行榜更精準。
```

73.An AI practitioner has built a deep learning model to classify the types of materials in images. The AI practitioner now wants to measure the model performance. Which metric will help the AI practitioner evaluate the performance of the model?

```
Confusion matrix
混淆矩陣能顯示分類結果的正確率和錯誤分類情況，是分類任務評估的核心指標。
```

74.A company has built a solution by using generative AI. The solution uses large language models (LLMs) to translate training manuals from English into other languages. The company wants to evaluate the accuracy of the solution by examining the text generated for the manuals. Which model evaluation strategy meets these requirements?

```
Bilingual Evaluation Understudy (BLEU)
BLEU 是評估機器翻譯品質的標準指標，能量化翻譯文本與參考譯文的相似度。
```

75.A company has fine-tuned a large language model (LLM) to answer questions for a help desk. The company wants to determine if the fine-tuning has enhanced the model's accuracy. Which metric should the company use for the evaluation?

```
F1 score
F1 分數綜合考慮精確率與召回率，是衡量分類任務準確度提升的關鍵指標。
```

76.A company is developing a mobile ML app that uses a phone's camera to diagnose and treat insect bites. The company wants to train an image classification model by using a diverse dataset of insect bite photos from different genders, ethnicities, and geographic locations around the world. Which principle of responsible AI does the company demonstrate in this scenario?

```
Fairness
使用多元且包容的資料集，有助減少偏見，確保模型對所有族群公平。
```

77.A student at a university is copying content from generative AI to write essays. Which challenge of responsible generative AI does this scenario represent?

```
Plagiarism
直接複製 AI 生成內容作為自己作品，涉及抄襲倫理問題。
```

78.An accounting firm wants to implement a large language model (LLM) to automate document processing. The firm must proceed responsibly to avoid potential harms. What should the firm do when developing and deploying the LLM? (Choose two.)

```
Include fairness metrics for model evaluation.
Modify the training data to mitigate bias.
確保模型公平性與降低偏見是負責任部署的關鍵步驟。
```

79.A company is deploying a generative AI system that can assist in generating marketing copy for advertisements. The company has established policies to ensure the AI system does not generate harmful or discriminatory content.
Which principle of responsible AI does the company demonstrate in this scenario?

```
Governance
制定明確政策與管理機制確保 AI 系統符合倫理與合規要求，屬於治理原則。
```

80.A social media company wants to use a large language model (LLM) for content moderation. The company wants to evaluate the LLM outputs for bias and potential discrimination against specific groups or individuals. Which data source should the company use to evaluate the LLM outputs with the LEAST administrative effort?

```
Benchmark datasets
基準資料集通常已標註且設計好，可快速且省力用於偏見與歧視評估。
```

81.A company is building a solution to generate images for protective eyewear. The solution must have high accuracy and must minimize the risk of incorrect annotations. Which solution will meet these requirements?

```
Human-in-the-loop validation by using Amazon SageMaker Ground Truth Plus
Ground Truth Plus 透過人員輔助驗證標註，能有效提高標註準確性，降低錯誤風險。
```

82.A loan company is building a generative AI-based solution to offer new applicants discounts based on specific business criteria. The company wants to build and use an AI model responsibly to minimize bias that could negatively affect some customers. Which actions should the company take to meet these requirements? (Choose two.)

```
Detect imbalances or disparities in the data.
Evaluate the model's behavior so that the company can provide transparency to stakeholders.
檢查數據是否有偏差並評估模型行為，有助於識別和降低偏見，並確保透明度。
```

83.A social media platform is using an AI model to recommend posts to users based on their interests. The platform provides users with insights into why certain posts are recommended and how the recommendations are made.
Which principle of responsible AI does the company demonstrate in this scenario?

```
Explainability
向用戶說明推薦原因和過程，是 AI 可解釋性原則的體現，幫助用戶理解系統決策。
```

84.When designing an application using generative AI, what measure should developers take to prevent the model from generating harmful or inappropriate content?

```
Implement content filtering and monitoring mechanisms.
透過內容過濾和監控，可以即時攔截和管控不當輸出，保障應用安全。
```

85.Which functionality does Amazon SageMaker Clarify provide?

```
Identifies potential bias during data preparation
SageMaker Clarify 專注於在資料準備和模型訓練階段檢測偏差，幫助建立公平的 ML 模型。
```

86.An accounting firm wants to implement a large language model (LLM) to automate document processing. The firm must proceed responsibly to avoid potential harms. What should the firm do when developing and deploying the LLM? (Choose two.)

```
Include fairness metrics for model evaluation.
Modify the training data to mitigate bias.
透過公平性指標監控與調整訓練資料來減少偏差，有助於建立負責任且公平的模型。
```

87.A social media company wants to use a large language model (LLM) to summarize messages. The company has chosen a few LLMs that are available on Amazon SageMaker JumpStart. The company wants to compare the generated output toxicity of these models. Which strategy gives the company the ability to evaluate the LLMs with the LEAST operational overhead?

```
Automatic model evaluation
自動化評估不需要人工介入，減少人力與管理負擔，是最省成本且快速的方法。
```

88.An ML research team develops custom ML models. The model artifacts are shared with other teams for integration into products and services. The ML team retains the model training code and data. The ML team wants to build a mechanism that the ML team can use to audit models. Which solution should the ML team use when publishing the custom ML models?

```
Create Amazon SageMaker Model Cards with intended uses and training and inference details.
SageMaker Model Cards 是專門用來描述模型用途、訓練與推論細節的工具，方便審核和透明化管理。
```

89.A large retail bank wants to develop an ML system to help the risk management team decide on loan allocations for different demographics.
What must the bank do to develop an unbiased ML model?

```
Measure class imbalance on the training dataset. Adapt the training process accordingly.
不平衡的訓練資料會導致偏見，量測並調整類別不平衡是避免模型偏見的關鍵。
```

90.A financial institution is building an AI solution to make loan approval decisions by using a foundation model (FM). For security and audit purposes, the company needs the AI solution's decisions to be explainable. Which factor relates to the explainability of the AI solution's decisions?

```
Model complexity
模型越複雜，決策越難解釋；降低模型複雜度有助於提高決策的透明度和可解釋性。
```

91.Which technique can a company use to lower bias and toxicity in generative AI applications during the post-processing ML lifecycle?

```
Human-in-the-loop
在人機互動環節加入人工審核，能有效捕捉並減少偏見和有害內容，是降低毒性和偏見的關鍵方法。
```

92.A company wants to create a chatbot by using a foundation model (FM) on Amazon Bedrock. The FM needs to access encrypted data that is stored in an Amazon S3 bucket. The data is encrypted with Amazon S3 managed keys (SSE-S3). The FM encounters a failure when attempting to access the S3 bucket data.
Which solution will meet these requirements?

```
Ensure that the role that Amazon Bedrock assumes has permission to decrypt data with the correct encryption key.
Amazon Bedrock 需要的 IAM 角色必須擁有解密 SSE-S3 金鑰的權限，才能存取加密的 S3 資料。
```

93.A company needs to use Amazon SageMaker for model training and inference. The company must comply with regulatory requirements to run SageMaker jobs in an isolated environment without internet access. Which solution will meet these requirements?

```
Run SageMaker training and Inference by using network Isolation.
使用 SageMaker 的 network isolation 功能，可以阻止工作實例連接網際網路，符合隔離和安全合規需求。
```

94.A company wants to deploy a conversational chatbot to answer customer questions. The chatbot is based on a fine-tuned Amazon SageMaker JumpStart model. The application must comply with multiple regulatory frameworks. Which capabilities can the company show compliance for? (Choose two.)

```
Threat detection
Cost optimization
法規合規通常關注資安威脅偵測與資料保護，這兩項能力直接支持合規要求
```

95.A company is testing the security of a foundation model (FM). During testing, the company wants to get around the safety features and make harmful content. Which security technique is this an example of?

```
Jailbreak
Jailbreak 是指繞過模型內建的安全限制，以產生不當或有害輸出。
```

96.A company wants to use Amazon Bedrock. The company needs to review which security aspects the company is responsible for when using Amazon Bedrock. Which security aspect will the company be responsible for?

```
Securing the company's data in transit and at rest
使用 AWS 服務時，公司通常負責保護自己的資料安全，包括資料傳輸和儲存的加密與管理。C
```

97.An AI practitioner trained a custom model on Amazon Bedrock by using a training dataset that contains confidential data. The AI practitioner wants to ensure that the custom model does not generate inference responses based on confidential data. How should the AI practitioner prevent responses based on confidential data?

```
Delete the custom model. Remove the confidential data from the training dataset. Retrain the custom model.
模型已學習機密資料，必須刪除並重新訓練才能保證推論不含敏感資訊。
```

98.A hospital is developing an AI system to assist doctors in diagnosing diseases based on patient records and medical images. To comply with regulations, the sensitive patient data must not leave the country the data is located in. Which data governance strategy will ensure compliance and protect patient privacy?

```
Data residency
資料駐留（Data residency）策略確保資料儲存與處理在特定地理區域，符合法規和隱私要求。
```

99.A company wants to develop a large language model (LLM) application by using Amazon Bedrock and customer data that is uploaded to Amazon S3. The company's security policy states that each team can access data for only the team's own customers. Which solution will meet these requirements?

```
Create an Amazon Bedrock custom service role for each team that has access to only the team's customer data. Most Voted
為每個團隊建立自訂的 Bedrock 服務角色，並限制其只能存取該團隊的客戶資料，確保安全隔離與權限最小化。
```

100.An AI practitioner is using an Amazon Bedrock base model to summarize session chats from the customer service department. The AI practitioner wants to store invocation logs to monitor model input and output data.
Which strategy should the AI practitioner use?

```
Enable invocation logging in Amazon Bedrock.
Amazon Bedrock 提供直接開啟調用日誌的功能，方便追蹤模型輸入輸出，符合監控需求。
```

101.Which option is a characteristic of AI governance frameworks for building trust and deploying human-centered AI technologies?

```
Developing policies and guidelines for data, transparency, responsible AI, and compliance
AI 治理框架透過制定明確的政策和指引，涵蓋資料、透明度、負責任的 AI 及合規，來促進信任和負責任使用 AI。
```

102.A financial institution is using Amazon Bedrock to develop an AI application. The application is hosted in a VPC. To meet regulatory compliance standards, the VPC is not allowed access to any internet traffic. Which AWS service or feature will meet these requirements?

```
AWS PrivateLink
AWS PrivateLink 可讓 VPC 私下且安全地存取 AWS 服務，無需透過公開網際網路，符合無網路流量的合規要求。
```
