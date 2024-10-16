# LLM-GPT

**1-Overview:**

This project integrates the Gmail API to fetch emails, preprocesses the text data, and uses OpenAI’s language models for classification tasks. The goal is to demonstrate how AI can be leveraged to automate email categorization.
(Turkish: Bu proje, Gmail API'si ile e-postaları çeker, metin verilerini işler ve OpenAI'nin dil modellerini kullanarak sınıflandırma görevlerini gerçekleştirir. Kodlarda scikit-llm kütüphanesi de kullanılarak **veriseti olmadan** tahminleme / sınıflandırma yapılması üzerine bir model kurulmuştur. **Asıl amaç scikit-learn ile llm' i bir araya getiren **scikit-llm** modülünün verimli kullanımına örnek oluşturmaktır.** )

**2-Prerequisites:**

Python 3.7+
OpenAI API Key
Google credentials file (credentials.json)
Required Python libraries: openai, google-auth, scikit-learn, pandas, nltk
(Turkish: Gereksinimler: Python 3.7+, OpenAI API Anahtarı, Google kimlik bilgileri, gerekli Python kütüphaneleri)

**3-Resources:**

OpenAI API Documentation
Gmail API Documentation
https://skllm.beastbyte.ai/
