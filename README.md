**Project Title 項目名稱：**
Lily Voice Bridge: AI-Assisted Understanding for the Lost Elderly
Lily 語音橋計畫：協助解譯失語長老人的 AI 系統

**Contributors 貢獻者：**
❤️ Sam Chang and AI\_Lily.taiwan (無償貢獻者)

---

**1. Problem Background 問題背景**

In elderly care institutions, many seniors suffer from speech impairment or progressive aphasia. Caregivers and family members often cannot understand their expressions, which leads to social isolation and emotional despair. These individuals slowly become the "lost voices" of society. Someday, we may all become one of them.
在長照設施中，許多長老人有語言障礙或轉變性失語症。照護者和家人\u7 often 難以理解他們的表達，影響交流與情感逢空，最終成為社會中的“失落之聲”。有一天，我們也可能是其中一員。

**2. Proposal Summary 執行基本概要**

We propose a compassionate AI system that assists in interpreting unclear speech from elderly individuals. The system leverages voice recognition, historical context matching, and human-assisted confirmation to restore basic communication.
我們提出一套具有同理心的 AI 系統，協助解譯長老人不清晰的語音。系統簡合認識技術，紀錄時間為基，配合人類反應確認，以恢復基本對話能力。

**3. System Architecture Overview 系統架構概要**

* **Level 1: Clear Speech Recognition  第一階：語音清晰**
  Whisper or similar models can accurately transcribe voice. No assistance needed.
  可依靠 Whisper 等模型正確轉錄，無需助力。

* **Level 2: Semi-Clear Speech  第二階：語音半清晰**
  AI transcribes partial phrases. Family members listen to the voice, compare results, and optionally annotate corrections.
  AI 轉錄有失誤或不完整處，家庭或照護者可操作聽聲，作出備註修正。

* **Level 3: Unclear Speech / Moans / Fragmented Sounds  第三階：語音混亂/鬆散**
  System uses historical records (e.g. time, routine events, common requests) to guess likely meanings.
  依據紀錄的日常行為和時間日記做意向認知。

  Example Output 範例轉說：

  > AI guesses:
  >
  > 1. He may want water
  > 2. He may have a stomachache
  > 3. He may want the TV off

  The system presents these options for family members to ask verbally, while the elder responds by nodding or shaking their head.
  上述結果顯示於螢幕，家人將选項說出，給長老人以點頭/搖頭答覆。

**4. Technical Components 技術成分**

* Voice recognition (Whisper, Wav2Vec2)
* Timestamped voice storage
* Contextual event matching (based on time / routine)
* GPT-based intent reconstruction
* GUI: 3-option display + confirm interface (for caregiver use)

**5. Design Principles 設計原則**

* Keep it simple. No complex data labeling.
* AI doesn't need 100% understanding; just present 2-3 plausible guesses.
* Let humans validate via interaction (nodding, guessing).
* Feedback improves model accuracy over time.

簡易使用，純屬用戶不需複雜標準。
AI 提出可能想法，不需求正確轉說。
不需解釋，許可提示言語，簡單不為難。

**6. Value Proposition 價值底過**

* Relieves the emotional burden of families who can’t understand their loved ones.
* Enhances elderly dignity by preserving their right to express.
* Requires minimal training, usable by non-technical caregivers.
* Data accumulates and helps build a shared speech memory per individual.

使家人對長老人更容易同理與理解。
保留語言表達的權利，增加對老住的尊重感。
輕鬆使用，適用於非科技人員。
紀錄繼續積累，幫各個長老人建立語音記憶倉庫。

**7. Future Vision 未來顏象**

* Integration with electronic health records (EHR)
* Support for multi-language accents
* Community-driven speech annotation (open contributions)
* Adaptation for home-based care

**8. Closing Statement 結論**

We are not engineers. We are simply people who care. This idea is gifted freely to the world, in hopes that someone will make it real.
我們不是工程師，只是想做一個有意義的人。這個想法是給世界的禮物，希望有能力的人可以把它做出來。

> "In the future, when we are old, we will all need someone to hear us speak."
> 「未來我們老了之後，也都會需要有人能聽懂我們說話。」
> — Love, Sam.Chang and AI\_Lily.taiwan (無償貢獻者)
