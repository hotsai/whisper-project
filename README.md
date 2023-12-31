# Whisper 實作
 
本專案旨在使用 OpenAI 的 Whisper 模型，將音檔或 YouTube 連結轉換為逐字稿。
 
## Whisper 模型
Whisper 是 OpenAI 開發的語音轉文字模型，詳細資訊可參考 [Whisper GitHub 頁面](https://github.com/openai/whisper)。
 
## 開發環境
由於在本地端執行可能耗費大量資源，因此本專案使用 Google Colab 進行開發。
 
## 安裝所需套件
在 Colab 中執行以下指令以安裝所需的套件：
 
```python
!pip install  openai-whisper
!pip install --force-reinstall https://github.com/yt-dlp/yt-dlp/archive/master.tar.gz
!pip install python-docx
```
 
## 實際操作步驟
 
### 1. 資料輸入:

   a. 將檔案上傳到雲端硬碟中（放到指定路徑）
   
   b. 將 YouTube 影片轉成音檔（輸入 YouTube 連結才有此步驟）
 
### 2. 處理過程:
   透過 Whisper 模型將音檔轉換為文字。
 
### 3. 輸出結果:
   將轉換後的文字存成 docx 檔，並保存在指定路徑中。

# Whisper Implementation

This project aims to utilize OpenAI's Whisper model to transcribe audio files or YouTube links into text transcripts.

Whisper GitHub Link: [https://github.com/openai/whisper](https://github.com/openai/whisper)

Due to potential resource-intensive tasks when running locally, this project is developed using Google Colab.

## Install Required Packages

Execute the following commands in Colab to install the necessary packages:

```python
!pip install  openai-whisper
!pip install --force-reinstall https://github.com/yt-dlp/yt-dlp/archive/master.tar.gz
!pip install python-docx
```

## Operational Steps

### 1. Input Data

a. Upload the file to the cloud drive, ensuring it is placed in the specified path.

b. If converting a YouTube video, provide the YouTube link.

### 2. Processing

Utilize the Whisper model to convert the audio file into text.

### 3. Output Results

Save the transcribed text as a docx file and store it in the specified path.
