LLMCOSPLAY-RAG-TTS-

歡迎來到實現LLMCOSPLAY的筆記本
首先我必須要非常感謝Artrajz的vits-simple-api程式碼
有他的API介面省了非常多的時間


前置作業
GOOGLE_API_KEY = gemini api的金鑰
HF_TOKEN = huggingface的金鑰
接下來請到他的API介面
https://colab.research.google.com/drive/1uBkMy0UjLE3C1zvxZ7NPPc3K74v4B6zw

運行完會拿到類似像API_URL = "https://4cf4-54-157-39-105.ngrok-free.app/voice/vits"  
這樣的分享連接


如果還沒有訓練聲音模型的 推薦用Plachtaa/VITS-fast-fine-tuning
https://colab.research.google.com/drive/1pn1xnFfdLK63gVXDwV4zCXfVeo8c-I-0?usp=sharing

最後為了實現llmcosplay 需要一個類似像這樣結構的json檔案 
也可以在colab內自己慢慢打


[
  {
    "title": "全名",
    "content": "長崎そよ"
  }
]
