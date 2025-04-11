# 📚 examvault

**examvault** is a community-powered, open-source question bank for students preparing for **O Level**, **A Level**, **AS Level**, and **IGCSE** exams.

We aim to make exam prep accessible and organized through a structured repository of past paper-style questions — categorized by board, subject, paper, and topic.

## 🗂️ Repository Structure

```
examvault
└── CAIE
    └── O-Level
        └── 5054-Physics
            ├── Paper-1
            │   ├── images
            │   │   └── 5054_w24_qp_11_Fig_1_2.png
            │   ├── 5054_w24_qp_11.md
            │   └── 5054_w24_qp_12.md
            └── Paper-2
                ├── images
                └── 5054_w24_qp_21.md
```

- Each `.md` file = a past paper or variant
- Questions are written in Markdown with embedded LaTeX
- Figures are stored in the `images/` directory for reference

## ✍️ Naming Convention

We follow a strict naming format for clarity and scalability:

| Type         | Format                                 | Example                          |
|--------------|----------------------------------------|----------------------------------|
| Question File| `<code>_<session>_qp_<paper><var>.md`  | `5054_w24_qp_11.md`              |
| Image File   | `<code>_<session>_qp_<paper>_Fig_x_y`  | `5054_w24_qp_11_Fig_1_2.png`     |

- `5054` = Subject Code (e.g., Physics)
- `w24` = Session (e.g., Winter 2024)
- `qp` = Question Paper
- `11` = Paper 1, Variant 1
- `Fig_x_y` = Usually question figure formats `Fig. 1.2` 

## 🤝 How to Contribute

1. Fork the repo & clone it locally
2. Navigate to the subject folder or create a new one
3. Add your questions using Markdown + LaTeX formatting
4. Save related images in the `images/` folder
5. Follow naming conventions
6. Open a Pull Request 🚀

For detailed rules and question formatting, see our  
📘 [Contribution Guide](https://github.com/fam007e/examvault/wiki/CONTRIBUTING)

## 🧪 Features Coming Soon

- 🔄 Mock test generator (topic-wise, paper-wise, random)
- 🧠 Interactive web-based quiz platform (LaTeX rendering)
- 🗃️ Taggable and filterable questions by difficulty, topic
- 🏅 Contribution leaderboard for the community

## 🌐 Join the Community

Get involved, ask questions, or share ideas on our subreddit:  
[📎 r/examprepvault](https://www.reddit.com/r/examprepvault)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE)  
