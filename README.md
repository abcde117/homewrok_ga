# 📘 Genetic Learning Simulation - 遺伝的学習シミュレーション

This project is a genetic algorithm simulation where multiple students improve their academic abilities over generations by studying textbooks, simulating exams, and adapting based on feedback.

このプロジェクトは、複数の学生が教科書を使って勉強し、模擬試験を通じて能力を高め、フィードバックに基づいて進化していく遺伝的アルゴリズム・シミュレーションです。

---

## 📌 Overview - 概要

### EN

This simulation models how students evolve by studying different textbooks through:

- Self-assessment (self-check)
- Simulated answering of questions
- Fitness evaluation based on learning outcomes
- Selection of suitable textbooks per student
- Learning ability update
- Knowledge exchange (crossover)
- Random mutation for diversity

After multiple generations, students converge toward optimal abilities matching the content.

### JP

本シミュレーションでは、学生たちは以下のプロセスを通じて進化していきます：

- 自己診断（self-check）
- 問題への模擬回答
- 学習成果に基づく適応度評価
- 各学生に最も合う教科書の選定
- 能力アップデート（学習成果反映）
- 知識の交叉（crossover）
- 多様性を保つための突然変異（mutation）

複数の世代を通じて、学生の能力は教科書の内容に適合する方向へと収束していきます。

---

## 🧪 Core Modules - 主要モジュール

| Function 名 | Description - 説明 |
|-------------|--------------------|
| `importance(q_size)` | Generate question importance weights - 問題の重要度を生成 |
| `self_check_total(...)` | Simulate self-check behavior - 自己チェック動作のシミュレーション |
| `question_anser_total(...)` | Simulate student answering per subject - 学生の模擬回答 |
| `fittness_func(...)` | Evaluate fitness between student and textbook - 適応度計算 |
| `selection(...)` | Select the best textbook for each student - 最適な教科書の選定 |
| `update_ablity_peronal(...)` | Update learning ability - 能力アップデート |
| `crossover_total(...)` | Simulate knowledge sharing between students - 交叉学習 |
| `mutation_total(...)` | Add random mutations - 突然変異の導入 |
| `ga(...)` | Run the full generational loop - GA世代ループ |
| `main()` | Entry point with random initialization - 初期化と実行開始 |

---

## 🧬 Algorithm Flow - アルゴリズムの流れ

