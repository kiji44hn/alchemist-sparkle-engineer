# Alchemist Sparkle – Vue × Three.jsによる構造型インタラクション表現

## プロジェクト概要

Alchemist Sparkleは、**Three.jsによる動的背景描画と、GSAP・Vue.jsによる構造的アニメーション演出**を組み合わせたインタラクティブ表現の検証プロジェクトです。  
幻想的な空間設計を、UI・UXの構造に落とし込む過程を通じて、**実装・設計力と情緒的誘導構造**の両面を提示しています。

---

## 実装ポイント・構造要素

- **動的背景描画**  
  - Three.jsを使用し、流星・錬金粒子をCanvas上に表現  
  - 頂点配置とアルファ制御により、幻想的かつリアルタイムな演出を構成

- **UI設計と導線構造**  
  - アトリエ風レイアウト：Vue.jsによる状態管理と条件分岐で演出  
  - Tailwind CSSを活用し、幻想性とミニマリズムを両立した画面設計を構築

- **アニメーション制御**  
  - GSAPによるページ遷移・要素出現の緩急調整  
  - DOM構造に依存しないトリガー型制御の設計

- **UX誘導の工夫**  
  - “静と動”のリズム変化を通じ、コンテンツへの没入を促進  
  - 利用者の操作介入なしで進行する受動体験構造

---

## 使用技術と選定理由

| 技術 | 用途 | 選定意図 |
|------|------|-----------|
| **Vue.js** | UIの構造設計・状態制御 | 情報の分離とコンポーネント管理に適しているため |
| **Three.js** | Canvasでの空間・星・粒子表現 | GPU描画による軽量かつ幻想的表現が可能 |
| **GSAP** | アニメーション演出 | 多段階アニメーションや非同期動作に柔軟に対応 |
| **Tailwind CSS** | UIスタイリング | コンポーネント単位で柔軟かつ可読性の高い設計が可能 |
| **TypeScript** | 型安全性・保守性 | 複雑な描画・構造整理の妥当性を担保するため

---

## 実行環境と導入方法

- **対応ブラウザ**：Chrome / Firefox / Edge / Safari（最新版）
- **レスポンシブ対応**：スマートフォン表示調整済み
- **ローカル起動**：

```bash
npm install
npm run dev
```

※Viteベースの開発環境を想定

## 備考
- 本READMEは、**技術検証・構造提示を目的とした内容構成**です
- 演出意図・物語設計は別途リポジトリ・ストーリーボードにて整理予定
- 技術職・演出職双方の視点からの構築力を示す内容になっています

## 著者について
UX設計・構造設計・VFX演出・構成文書制作までを一貫して担当。 **インタラクティブ表現を“構造と語り”両面から設計できる技術者・演出者**として、本リポジトリは技術的・美的両側面のポートフォリオを兼ねています。