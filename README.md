## English

### 📝 Project Overview
This repository contains a **Retrieval-Augmented Generation (RAG)** based chatbot application developed using **LangChain** and **Google Colab**. The project utilizes the **IBM Granite** model (`granite-embedding-small-english-r2`) locally to convert budget and financial tip documents into vector embeddings and store them in a **Chroma** vector database. 

The main goal is to prevent AI hallucinations by ensuring the chatbot answers user queries strictly based on the provided domain-specific documents.

### 🏗️ Architecture Workflow
1. **Data Ingestion:** Document loading and splitting into manageable text chunks.
2. **Embedding Generation:** Transforming text chunks into vector representations using the local `ibm-granite` model via Hugging Face.
3. **Vector Database:** Indexing and storing embeddings into `Chroma DB`.
4. **Retrieval & Generation:** Fetching relevant context based on user queries and generating precise answers.

### 🛠️ Tech Stack & Libraries
* **Framework:** LangChain (`langchain-huggingface`, `langchain-chroma`)
* **Embedding Model:** `ibm-granite/granite-embedding-small-english-r2`
* **Vector Store:** Chroma DB
* **Environment:** Google Colab / Python

### 🚀 Quick Start
To run this project locally or on Google Colab, install the required dependencies first:

Bash
pip install langchain-huggingface transformers sentence-transformers langchain-chroma


## **Türkçe**

### **📝 Proje Özeti**

Bu depo, LangChain ve Google Colab kullanılarak geliştirilmiş Geri Alma Destekli Üretim (RAG) tabanlı bir chatbot uygulamasını içermektedir. Proje, bütçeleme ve finansal ipucu dökümanlarını vektör embedding'lerine (sayısal dizilere) dönüştürmek için yerel olarak çalışan IBM Granite (granite-embedding-small-english-r2) modelini kullanır ve bu verileri Chroma vektör veri tabanında saklar.

Ana amaç, chatbot'un kullanıcı sorularına doğrudan yüklenen dökümanlara sadık kalarak, doğru ve halüsinasyon görmeden (uydurmadan) cevap vermesini sağlamaktır.

### **🏗️ Mimari İş Akışı**
1. **Veri Hazırlığı (Ingestion):** Belgelerin yüklenmesi ve anlamlı metin parçalarına (chunks) bölünmesi.
2. **Embedding Üretimi:** Metin parçalarının Hugging Face üzerinden yerel ibm-granite modeliyle vektörlere dönüştürülmesi.
3. **Vektör Veri Tabanı:** Vektörlerin arama yapılabilmesi için Chroma DB üzerinde indekslenmesi ve saklanması.
4. **Geri Alma ve Üretim (RAG):** Kullanıcı sorusuna en uygun kaynak metinlerin bulunması ve yapay zekanın bu kaynaklara göre cevap üretmesi.


### **🛠️ Kullanılan Teknolojiler**
• **Çerçeve (Framework):** LangChain (langchain-huggingface, langchain-chroma)
• **Embedding Modeli:** ibm-granite/granite-embedding-small-english-r2
• **Vektör Veri Tabanı:** Chroma DB
• **Geliştirme Ortamı:** Google Colab / Python

### **🚀 Hızlı Başlangıç**
Bu projeyi kendi ortamınızda veya Google Colab üzerinde çalıştırmak için önce gerekli kütüphaneleri yükleyin:

Bash
pip install langchain-huggingface transformers sentence-transformers langchain-chroma
