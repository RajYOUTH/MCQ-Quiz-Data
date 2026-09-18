# MCQ-Quiz-Data

**YOUTH Academy — Free MCQ Question Bank**

A growing, structured database of multiple-choice questions for competitive exams, maintained by YOUTH Academy (Tamil Nadu, India).

## 🎯 Purpose

This repository powers YOUTH Academy's free online test series. Questions are:

- Authored and curated by experienced teachers
- Structured with rich metadata (exam, subject, topic, difficulty, source, etc.)
- Served as static JSON files to Blogger-based quiz pages
- Updated continuously as new tests are added

## 📚 Exams Covered

- TNPSC Group 2 & 2A
- TNPSC Group 4 & VAO
- TNUSRB (Police, Fire, Jail)
- SSC (CGL, CHSL, MTS)
- RRB (NTPC, Group D)
- More exams coming soon

## 📁 Repository Structure

MCQ-Quiz-Data/
├── LICENSE
├── README.md
├── test1.json
├── test2.json
├── test3.json
├── test4.json
├── test5.json
├── test6.json
├── test7.json
├── test8.json
├── test9.json
├── test10.json
└── exams/
    ├── tnpsc-g2.json
    ├── tnpsc-g4.json
    ├── tnusrb.json
    ├── ssc.json
    ├── rrb.json
    └── ...

## 🧩 Question Format

Each JSON file contains an array of questions in the following structure:

{
  "q": "Question text",
  "o": ["Option A", "Option B", "Option C", "Option D", "Option E"],
  "a": 0,
  "e": "Explanation text",
  "s": "tamil"
}

Field meanings:

- q = Question
- o = Options array (A to E)
- a = Correct answer index (0=A, 1=B, 2=C, 3=D, 4=E)
- e = Explanation
- s = Section (tamil, gs, maths)

## 🏛️ About YOUTH

YOUTH stands for YOUTH Organization for Universal Truth and Health — an initiative of YOUTH FOUNDATION, Tiruppur, Tamil Nadu, India.

Vision: YOUTH for TRUTH and HEALTH

YOUTH Academy provides free, high-quality education to aspirants preparing for competitive exams in Tamil Nadu and beyond.

## 📜 License

This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

You are free to:

- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material

Under the following terms:

- Attribution — Give appropriate credit to YOUTH Academy
- NonCommercial — No commercial use without permission
- ShareAlike — Derivatives must use the same license

See LICENSE for full text.

## 📞 Contact

- Website: youthtn.blogspot.com
- WhatsApp: bit.ly/YOUTHforTRUTH
- Telegram: t.me/YOUTHDOM
- Registration: forms.gle/K4CgirudWbEtNG3t6

with YOUTH for TRUTH we WIN
