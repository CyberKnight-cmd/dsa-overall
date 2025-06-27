---

# DSA – Data Structures and Algorithms

Welcome to my **DSA repository**, containing all my structured notes, codes, and problem solutions in **C++, Java, and beyond**.

---

## 🗂️ **Folder Structure**

```
DSA/
├── CPP/                       # C++ codes for CP and DSA courses
├── JAVA/                      # Java Bootcamp codes (submodule)
├── solved-leetcode-problems/  # LeetCode solutions (submodule)
└── .github/workflows/         # GitHub Actions for automation
```

---

## 🔗 **Submodules**

This repository uses **Git submodules** to include external repositories cleanly:

| Submodule                                                                               | Description                                  |
| --------------------------------------------------------------------------------------- | -------------------------------------------- |
| [C++](https://github.com/CyberKnight-cmd/cpp-dsa)                                                                   | C++ DSA and CP codes.                        |
| [Java Bootcamp](https://github.com/CyberKnight-cmd/DSA-Bootcamp-Java)                                                         | Contains Java DSA course codes               |
| [Solved LeetCode Problems](https://github.com/CyberKnight-cmd/solved-leetcode-problems) | Auto-pushed LeetCode solutions using LeetHub |

---

### ⚠️ **Using Submodules**

✅ **Clone with submodules**

```bash
git clone --recurse-submodules https://github.com/CyberKnight-cmd/dsa-overall.git
```

✅ **Initialize submodules after clone**

```bash
git submodule update --init --recursive
```

✅ **Update submodules manually**

```bash
git submodule update --remote --merge
git add .
git commit -m "Update submodules"
git push origin main
```

---

## 🤖 **Automation**

✔️ **GitHub Actions workflow** updates submodules daily at **12 AM IST** and commits any changes automatically.

To trigger manually:

* Go to **Actions tab → Update Submodules → Run workflow**

---

## 🚀 **Current Goals**

* [x] Setup clean repo structure
* [x] Add Java Bootcamp submodule
* [x] Integrate LeetHub automated repo
* [x] Configure GitHub Actions for daily updates
* [ ] Add Python DSA folder
* [ ] Integrate DSA written notes
* [ ] Integrate Pseudocode

---

## 💡 **Technologies Used**

* C++ (Competitive Programming)
* Java (DSA Bootcamp)
* Git, GitHub Actions
* VS Code

---

## 📝 **Notes**

This repository acts as my **single source of truth for DSA and CP preparation**, maintaining:

✔️ Clean folder organization
✔️ Automation for consistency
✔️ Scalability for upcoming ML, OS, and core CS topics

---

### 🔄 **Notes Going Forward**

⚠️ **When working with submodules:**

* To **clone the repository with all submodules**:

  ```bash
  git clone --recurse-submodules <repo-url>
  ```

* If cloned without `--recurse-submodules`, initialize submodules with:

  ```bash
  git submodule update --init --recursive
  ```

* To **update all submodules manually**:

  ```bash
  git submodule update --remote --merge
  git add .
  git commit -m "Update submodules"
  git push origin main
  ```

---

## ✨ **Contact**

If you have suggestions or want to collaborate on structured note-making or DSA resources:

📧 [aryagupta164@gmail.com](mailto:aryagupta164@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/aryagupta2304/)

---

### 🔖 **License**

This repository is **private for personal learning and practice**. Contact for curated resource sharing if needed.

---

### ✅ **End**

> **"Code every day, even if it’s a single line. Consistency compounds."**

---

✅ **Instructions**

1. Replace all `link-if-public` and `<repo-url>` placeholders as needed.
2. Save as **README.md** and push:

```bash
git add README.md
git commit -m "Add Notes Going Forward section to README"
git push origin main
```

---

Let me know once done. Next, we will plan your **ML repo setup strategy** and workflows in tomorrow’s focused session.
