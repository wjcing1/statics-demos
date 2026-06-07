# Homework — Phase II: DSI & Trusses

**布置日期**：2026-06-07
**对应**：Phase II Task 1–4（study-plan）
**预计自学时长**：阅读 ~3h + 做题 ~1.5h = ~4.5h
**Source**：
- [Practical_notes_3.pdf](Statics_WeBeep/02_List_of_Exercises/Practical_notes_3.pdf) p.6–8（DSI 题目）
- [Practical_notes_4.pdf](Statics_WeBeep/02_List_of_Exercises/Practical_notes_4.pdf)（Trusses 题目 + p.6 起答案）
- [Pract_sheet_4_Ex_4.1_4.3_4.6_4.7.pdf](Statics_WeBeep/04_Solved_Exercises/Pract_sheet_4_Ex_4.1_4.3_4.6_4.7.pdf)（4.3 详细解答）

---

## 📨 给学生的版本（可直接复制）

### Step 1 — Read Class 5 (DSI) — ~60 min

Read: [Class_5_Degree_of_Static_Indeterminacy.pdf](Statics_WeBeep/01_Slides/2023_10_21_Class_5_Degree_of_Static_Indeterminacy.pdf)

读完关上 slides，默写：
1. DSI = ED + ID — 写出完整公式，解释每个字母
2. DSI > 0 / = 0 / < 0 分别叫什么？（hyperstatic / isostatic / hypostatic）
3. Hypostatic 时要画什么？（failure mechanism）

---

### Step 2 — DSI exercises

- ⬜ **Prob 3.7 (a–n)** — 14 个简单梁/结构，算 DSI，hypostatic 的画 mechanism
- ⬜ **Prob 3.8 (a–d)** — 带 internal hinge 的结构，注意 ID 怎么数

答案：Practical_notes_3.pdf 没有 3.7–3.8 的数值答案，见面时一起对。

---

### Step 3 — Read Class 6 + Class 7 — ~90 min

Read in order:
1. [Class_6_Method_of_joints.pdf](Statics_WeBeep/01_Slides/2024_10_28_Class_6_Method_of_joints.pdf)
2. [Class_7_Method_of_Ritter.pdf](Statics_WeBeep/01_Slides/2024_11_04_Class_7_Method_of_Ritter.pdf)

读完用一句话回答：
- Method of joints: 从哪种 node 开始？为什么？
- Method of Ritter: 切几根 bar？为什么？

---

### Step 4 — Truss exercises

- ⬜ **Prob 4.3** — 用 Ritter's method 求所有杆件内力
- ⬜ **Prob 4.4** — (a) Method of joints 求所有杆件；(b) Ritter 求 CD, BD, ED

答案：Practical_notes_4.pdf p.6 有图解答案；4.3 还有详细解答 [Pract_sheet_4_Ex_4.1_4.3_4.6_4.7.pdf](Statics_WeBeep/04_Solved_Exercises/Pract_sheet_4_Ex_4.1_4.3_4.6_4.7.pdf)

---

### Step 5 — 做完发我

简短一段，回答 3 件事：
1. DSI 公式能默写吗？3.7 错了几个？
2. 4.3 和 4.4 做出来了吗？哪一步卡了？
3. Method of joints vs Method of Ritter，用自己的话说区别

---

## 🧑‍🏫 Tutor 内部备注

### 为什么挑这些题

| 题 | 测什么 |
|---|---|
| 3.7 (a–n) | DSI 公式的纯肌肉记忆，14 个快速判断 |
| 3.8 (a–d) | internal hinge 对 ID 的影响，容易漏数 |
| 4.3 | Ritter 专练，结构小（7 nodes），有详细解答可自查 |
| 4.4 | 两种方法都用，(a) joints 全解 (b) Ritter 选 3 根，对比体感 |

### 见面要观察的点

- **3.7 全错一半以上** → DSI 公式没理解，不是没背，回头讲 Class 5
- **3.8 错在 ID** → internal hinge 的约束释放没搞懂，这是 oral exam P2 的核心
- **4.3 做不出** → Ritter 切割位置选不对，见面时画一遍
- **4.4 (a) 做出来 (b) 做不出** → joints 会但 Ritter 不会，正常，重点补 Ritter
- **4.4 (a)(b) 都做不出** → 回头确认 equilibrium 基础（Phase I）是否扎实

### 没有数值答案的题（3.7, 3.8）

DSI 题没有官方答案。见面时需要自己对，或提前算好一份 answer key。
