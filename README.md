---

## **1. Хиймэл оюун (AI) ба Том Хэлний Моделиуд (LLM)**

**Чиглэл:** Үндсэн AI, LLM-д суурилсан системүүд

* Сургуулиуд, эмнэлэг, чатбот хөгжүүлэх систем
* Хэрэглэгчийн өгөгдөл дээр тулгуурлаж хүний сэтгэл, хөдөлгөөнийг тодорхойлох
* Хувийн мэдээллийг алдалгүйгээр хэрэглэгчийн өгөгдлийг хуваалцах Distributed ML
* Quantum LM симулятор
* Нэйчрал Лэнгвич Просессинг (NLP) ашиглан:

  * Online store-д хэрэглэгчдэд бараа санал болгох
  * Олон хэл дээр асуулт-ажилбар систем үүсгэх

---

## **2. Машин Сургагч (Machine Learning) ба Урьдчилсан Таамаглал**

**Чиглэл:** Эрүүл мэнд, байгаль орчин, санхүү, хот төлөвлөлт

* Эмнэлгийн оношлогоо, өвчний таамаглал
* Ургамал, малын өвчин таамаглах
* Санхүүгийн залилан илрүүлэх (Big Data + Real-time)
* Хотын хөдөлгөөн, замын түгжрэл, агаарын бохирдол, барилга байгууламжийн эрчим хүчний хэрэглээг урьдчилан таамаглах
* Нар, салхи зэрэг эрчим хүчний урьдчилсан таамаглал
* Гэмтэл, халдлага таамаглах (Real-time)

---

## **3. Компьютер Вижн (Computer Vision)**

**Чиглэл:** Хөдөлгөөн, объект таних, 3D модел

* Дүрс таних, дүрс ангилах (Transformer ашиглан)
* 3D объект үүсгэх
* Видео хэмжээг багасгах (Machine Learning)
* Гар, биеийн хөдөлгөөн таних
* BR эмнэлгийн чиглэлийн системийг автоматжуулах
* Орчны нөхцлийг хяналт (утасгүй сенсор, агаарын цэвэр байдал)
* Хараа муутай, сонсгол муутай хүний туслах AI

---

## **4. Роботик ба Эрчим хүч**

**Чиглэл:** DRL, автоматжуулалт

* Робот гар, бутыг DRL алгоритмаар оновчлох
* Бүрэн автоматжуулалт (гэр, байр, орон сууц)

---

## **5. Сүлжээ, Граф ба Газарзүйн мэдээлэл (GNN, Graph)**

**Чиглэл:** Нууцлал, хөдөлгөөн, таамаглал

* Social network граф анализ
* GNN ашиглан нууцлалын тайлбар
* Геомэдээлэл дээр үндэслэн замын түгжрэл, урсгал таамаглах (Real-time)

---

## **6. Big Data ба Өгөгдлийн Анализ**

**Чиглэл:** Өгөгдлийн хурд, хэмжээс, ангилал

* Өгөгдлийн тооцоолол хурдсгах
* Хог ангилан ялгах систем
* Байгаль орчны өгөгдлийг хянах (утаа, температур, салхи)
* Урьдчилсан таамаглал хийх (санхүү, эрчим хүч, хөдөлгөөн)

---

## **7. Нарийн технологи, Smart Systems**

**Чиглэл:** Smart City, сервергүй систем, микросервис

* Smart City: хотын эрчим хүч, хөдөлгөөн, агаарын чанар
* Serverless Web System
* Micro Service architecture Web System
* Nature Language Processing ашиглан мэдээлэл боловсруулалт

---

## **8. Байгалийн өв, соёл хадгалах**

**Чиглэл:** Урлаг, соёл, мал аж ахуй

* Machine Learning ашиглан өв соёлыг хадгалах
* Ургамал, малын өвчин таамаглах

---
---

## **1. AI, LLM чиглэл**

**Алгоритм ба шинжилгээ:**

* **Transformer, Attention** – Chatbot, сургууль/эмнэлгийн LLM-д суурилсан системд.

  * *Analysis:* Scale (tokens ↑ → memory ↑), Inference time, Fine-tuning хэрэгцээ.
* **Federated Learning / Distributed ML** – Хувийн өгөгдлийг алдалгүй сургалт.

  * *Analysis:* Communication overhead, convergence speed, security trade-offs.

---

## **2. Machine Learning / Prediction**

**Алгоритм ба шинжилгээ:**

* **Supervised Learning (Random Forest, XGBoost, Neural Networks)** – Эмнэлэг, мал/ургамлын өвчин таамаг, санхүүгийн fraud.

  * *Analysis:* Accuracy, overfitting, feature importance.
* **Time Series Forecasting (ARIMA, LSTM, Prophet)** – Хотын хөдөлгөөн, эрчим хүч, агаарын урьдчилсан таамаг.

  * *Analysis:* Prediction horizon, seasonal trends, real-time applicability.
* **Anomaly Detection (Isolation Forest, Autoencoder)** – Гэмтэл, халдлага, санхүүгийн залилан.

  * *Analysis:* False positive/negative rate, scalability.

---

## **3. Computer Vision**

**Алгоритм ба шинжилгээ:**

* **CNN / 3D CNN** – Дүрс таних, видео хэмжээг багасгах, 3D объект үүсгэх.

  * *Analysis:* FLOPs, inference latency, dataset size dependency.
* **Pose Estimation / OpenPose / MediaPipe** – Гар, биеийн хөдөлгөөн таних.

  * *Analysis:* Keypoint accuracy, multi-person support, lighting sensitivity.
* **Semantic Segmentation (U-Net, DeepLab)** – BR эмнэлгийн чиглэлийн автоматжуулалт.

  * *Analysis:* IoU (Intersection over Union), GPU memory usage.

---

## **4. Robotics / DRL**

**Алгоритм ба шинжилгээ:**

* **Deep Reinforcement Learning (DQN, PPO, SAC)** – Робот гар, бут, бүрэн автоматжуулалт.

  * *Analysis:* Sample efficiency, reward shaping, stability of training.
* **Inverse Kinematics / Motion Planning** – Роботын хөдөлгөөн оновчлох.

  * *Analysis:* Path smoothness, collision avoidance, computation time.

---

## **5. Graph / GNN / Social Network Analysis**

**Алгоритм ба шинжилгээ:**

* **Graph Neural Networks (GCN, GAT)** – Social network analysis, нууцлал тайлбар.

  * *Analysis:* Node/edge scalability, explainability, message passing iterations.
* **Community Detection (Louvain, Girvan-Newman)** – Social graphs, pattern discovery.

  * *Analysis:* Modularity, computational complexity, sparsity handling.

---

## **6. Big Data & Data Analysis**

**Алгоритм ба шинжилгээ:**

* **MapReduce / Spark / Dask** – Том өгөгдлийн тооцоолол, real-time analytics.

  * *Analysis:* Throughput, latency, fault tolerance.
* **Clustering / Classification (KMeans, DBSCAN, XGBoost)** – Хог ангилан ялгах, pattern discovery.

  * *Analysis:* Scalability, silhouette score, memory footprint.

---

## **7. Smart City / Environment Monitoring**

**Алгоритм ба шинжилгээ:**

* **Sensor Fusion Algorithms (Kalman Filter, Particle Filter)** – Орчны хяналт (утасгүй сенсор).

  * *Analysis:* Accuracy, noise robustness, real-time computation.
* **Graph-based Traffic Prediction (GNN, Spatio-Temporal GCN)** – Замын түгжрэл, хөдөлгөөн таамаг.

  * *Analysis:* Time complexity, spatial correlation, data sparsity.

---

## **8. NLP / Recommendation Systems**

**Алгоритм ба шинжилгээ:**

* **Collaborative Filtering / Matrix Factorization** – Online store recommendations.

  * *Analysis:* Cold-start problem, latent factors, scalability.
* **Text Classification / NER / Summarization** – Chatbot, smart system NLP.

  * *Analysis:* Accuracy, language coverage, inference time.

---
