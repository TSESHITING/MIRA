# 🔮 MIRA: AI-Powered 2D Idiom Fortune-Telling Game

<p align="center">
  <a href="https://youtu.be/P1Hsdz9zPrU">
    <img src="https://img.shields.io/badge/YouTube-Watch%20Video-red?style=for-the-badge&logo=youtube" alt="YouTube Video">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Unity-2022.3+-blue.svg?style=flat&logo=unity" alt="Unity">
  <img src="https://img.shields.io/badge/API-Google%20Gemini-orange.svg" alt="API">
  <img src="https://img.shields.io/badge/Language-C%23-green.svg" alt="C#">
</p>

> **"Unveil your destiny through the power of idioms and Generative AI."**
> 
> Developed as the final project for the **Intelligent Human-Computer Interaction** course. `MIRA` is an innovative Unity 2D game that gamifies traditional Chinese idiom learning by combining it with psychological fortune-telling and modern Generative AI (**Google Gemini API**).

---

## 🎮 Game Concept & Mechanics

The game transforms tedious idiom learning into an engaging, story-driven fortune-telling experience based on four classic elements: **Water (水), Wood (木), Fire (火), and Earth (土)**.

### 👥 Interactive Characters
Players interact with four distinct, trope-defined characters based on their fortune-telling results:
* **The Dominant CEO (霸道總裁)**: Intense yet rewarding feedback loops.
* **The Rich Young Lady (大小姐)**: Proud, tsundere, and humorous dialogue.
* **The Innocent Younger Boy / "Puppy" (小奶狗)**: Sweet, caring, and comforting companionship.
* **The Wise Sage (智者)**: Calm, philosophical guidance.

### ⚡ AI-Driven Core Loop
1. **Idiom Challenges:** Idiom card series are generated based on the four element choices.
2. **Real-time AI Image Generation:** After successfully completing each idiom card challenge, the **Gemini API** is triggered to generate a unique visual image representing that idiom.
3. **The Grand Finale (Image Fusion):** Once all 4 element cards are cleared, the system instructs Gemini to **merge and fuse the 4 generated images** into one final, customized masterpiece that reflects the player's ultimate fortune destiny.

---

## 🛠️ Technical Implementation

* **Unity 2D & UI Canvas:** Built a responsive, multi-character state machine and interactive UI flow in Unity.
* **Google Gemini API Integration:** Handled asynchronous WebRequests (C# `UnityWebRequest`) to communicate with the Gemini API for prompt engineering and dynamic response parsing.
* **Dynamic Image Generation & Composition:** Implemented runtime texture loading to display AI-generated imagery and synthesized the final 4-in-1 fused output.

---

## 👥 Acknowledgments & References
* **API Framework Reference:** The Google Gemini API connection architecture and C# parsing flow in this project were inspired and referenced from the open-source repository `Gemini_Chat_Avatar` by my university senior. 


---
---

# 🔮 MIRA：結合 Gemini API 的 AI 驅動 2D 成語占卜遊戲

> **這是一款在大學「智慧人機互動（Intelligent Human-Computer Interaction）」課程中完成的期末創新專案。**

`MIRA` 是一款將**傳統成語學習**與**心理占卜**、**現代生成式 AI（Google Gemini API）** 完美結合的 Unity 2D 遊戲。我們改變了以往枯燥乏味的死記硬背，透過充滿樂趣與故事性的玩法，讓玩家在互動中輕鬆學習成語。

---

## 🎮 遊戲核心概念與玩法機制

遊戲圍繞著四大經典元素：**水、木、火、土** 展開一場奇幻的成語占卜之旅。

### 👥 豐富的互動角色
根據玩家的占卜選擇與狀態，遊戲中設計了四個極具特色、深受大眾喜愛的動漫/小說設定角色來與玩家互動：
* **霸道總裁**：冷酷卻充滿張力的互動反饋。
* **大小姐**：高傲、傲嬌但趣味十足的對話。
* **小奶狗**：貼心、可愛的療癒系陪伴。
* **智者**：沉穩、充滿哲理的引導者。

### ⚡ AI 驅動的核心遊戲循環 (Core Loop)
1. **成語挑戰**：玩家選擇不同的元素（水木火土）後，系統會觸發相對應的成語卡片系列任務。
2. **實時 AI 生圖**：當玩家成功回答並完成每一張成語卡片的挑戰時，遊戲後台會立即調用 **Google Gemini API**，根據該成語的意境，實時生成一張獨一無二的視覺圖片。
3. **終極圖片融合 (Image Fusion)**：當四大元素卡片全部通關後，系統會下達進階 Prompt，**命令 Gemini 將前面生成的 4 張獨立圖片融合成一張最終的「命運大圖」**，作為屬於玩家個人的專屬占卜結局！

---

## 🛠️ 技術實作亮點

* **Unity 2D & 狀態機 UI 系統**：使用 Unity 建立流暢的多角色狀態切換與響應式 Canvas UI 系統。
* **Google Gemini API 深度整合**：在 C# 腳本中使用 `UnityWebRequest` 處理非同步網路請求，進行動態的 Prompt Engineering（提示詞工程）優化，並精準解析 AI 回傳的 JSON 資料。
* **動態紋理加載與圖像合成**：實作運行時（Runtime）動態加載 AI 生成的圖片紋理，並處理最終的 4 合 1 圖像融合輸出。

---

## 👥 專案誌謝與技術參考
* **API 架構參考**：本專案中關於 Google Gemini API 的網路串接架構與 C# 資料解析流程，參考並借鑑了課堂學姐的開源專案 `Gemini_Chat_Avatar`。
### 相关资源
本项目的数据集和大型模型权重已上传至云端：
- [下载数据集 (Google Drive)]([https://drive.google.com/drive/folders/1zusmcRZbIPxdZtNjt7FlKaN5_8XWm2q6?usp=drive_link])

