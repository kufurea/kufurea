## Hi there 👋

<!--
**kufurea/kufurea** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
地球物理学（地球惑星科学）を専攻している大学院生です。
コアダイナモ（流体金属外核の熱対流・磁場生成メカニズム）の数値シミュレーションや、古地磁気進化のデータ解析を中心に研究を行っています。

学術的な流体・電磁気学の知識と、Python/C/Javaを用いたシミュレーション・自動化インフラの開発力を融合させた、R&D（研究開発）やバックエンドの領域に強みを持っています。

---

## 🌌 Research & Interests（研究・関心のある分野）

* **地球深部ダイナミクス・古地磁気学**
  * コア-マントル境界（CMB）の熱・化学的条件が外核対流に与える影響の解明
  * 数値ダイナモシミュレーション（MagIC等）を用いた制御パラメータの chronological な遷移の導出
* **自動化インフラ・データサイエンス**
  * LLM（Gemini API）や各種Web APIを用いた自律型情報収集システムの構築
  * 大規模データ、物理シミュレーション結果の統計解析・可視化

---

## 🛠️ Skills（技術スタック）

### 🧑‍💻 Programming Languages
* **Python**
* **C** 
* **Java** 

### ⚙️ DevOps & Tools
* **Git / GitHub** （バージョン管理、ポートフォリオ公開）
* **GitHub Actions** （Cronジョブによるクラウド全自動化、CI/CD）
* **Linux / Bash** （研究用サーバーの運用、シェルスクリプトによる自動化）
* **Raspberry Pi** （IoT機器を用いたローカル環境のモニタリング・電子工作）

---

## 🚀 Featured Projects（主要プロジェクト）

### 🔹 [Geomag Summary System](https://github.com/kufurea/geomag-summary)
**arXiv & 主要地球物理誌（JGR, EPSL, GJI, PEPI）論文全自動要約インフラ**
* **概要**: 世界中の主要ジャーナルから地磁気・ダイナモ関連の最新論文を自動抽出し、Gemini APIを用いて高度な専門用語を網羅した日本語要約と査読級の重要度判定（A/B/C）を生成するシステム。
* **技術**: Python / Google GenAI SDK / feedparser / GitHub Actions / Discord Webhook
* **工夫点**: 
  * 出版社のスクレイピング対策を User-Agent 偽装および SSL コンテキストの最適化で完全突破。
  * プレビュー版APIのタイムアウトバグや429エラーを、ロジックのリセットとFlashモデルへの強固なフォールバック機構で解決。
  * GitHub Actionsを用いてPCの起動不要な「完全クラウド全自動運行（毎朝通知）」を実現。

---

## 📬 Contact（連絡先）

* **Portfolio**: https://kufurea.github.io/my-page/

---

## 📊 GitHub Stats

![Ryota's GitHub stats](https://github-readme-stats.vercel.app/api?username=kufurea&show_icons=true&theme=radial)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=kufurea&layout=compact&theme=radial)
