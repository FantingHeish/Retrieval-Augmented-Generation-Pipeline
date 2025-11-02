# 檢索增強生成系統 (Retrieval-Augmented Generation Pipeline)

## 專案簡介
本專案以 Retrieval-Augmented Generation 架構為核心，整合內部文件的檢索、語意切分、重新排序 (Reranking) 以及事實驗證模組。  
結合 LangChain、OpenAI API 與重新排序模組的 RAG 系統，透過 LLM-as-a-Judge 與 Retrieval Grader 評估準確率，整體回覆正確率提升約 20%。

## 技術架構
- **開發框架：** LangChain、OpenAI API、Pydantic  
- **核心模組：** Retrieval、Reranking、Semantic Search、Fact Verification  
- **評估方法：** LLM-as-a-Judge、Retrieval Grader  

## 專案檔案說明
- `adaptive_rag.py`：主要 RAG 流程與邏輯 
