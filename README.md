# Gen Z Banking Innovators Git Workshop

Добре дошли в работилницата по Git чрез играта **Gen Z Banking Innovators**! В този репозиториум ще създаваме маркетинг текст за **FlexiZ**, иновативно banking приложение за Gen Z, и ще практикуваме ключови Git-команди и процеси.

---

## 🎯 Цел на упражнението
- Усвояване на основни Git-концепции: branching, committing, pushing, pull requests, merging и конфликтно разрешаване.
- Колаборативно създаване на маркетинг текст чрез рундове на добавяне и ревизия.
- Развиване на умения за peer review и code collaboration.

---

## 📝 Файлове и структура
- `marketing.md` – шаблон с раздели за **Round 1** и **Round 2**, където ще добавяте вашите изречения.

---

## 👥 Екипи и роли
- **Team A** (branch: `team-a`) – създава съдържание
- **Team B** (branch: `team-b`) – създава съдържание
- **Team Main** (branch: `main`) – преглежда Pull Request-и, мержва, разрешава конфликти и поддържа финалната версия

---

## ⏱️ Таймлайн и итерации
1. **Round 1 (5 мин)**
   - Team A и Team B добавят **3 изречения** в секцията `Round 1` на `marketing.txt`
2. **Merge & Review (5 мин)**
   - Team Main преглежда PR-овете, коментира, мержва и разрешава конфликти при нужда
3. **Round 2 (5 мин)**
   - Team A и B добавят още **3 изречения** в секцията `Round 2`
4. **Final Merge & Presentation (5 мин)**
   - Team Main прави финално сливане и представя крайния текст

> **Общо време:** ~20 минути

---

## 🚀 Workflow стъпки за Team A & B

1. **Fork/Clone**:
   ```bash
   git clone <YOUR_REPO_URL>
   cd <REPO_FOLDER>
   ```

2. **Създайте branch** според екипа си:
   ```bash
   git checkout -b team-a   # или team-b
   ```

3. **Добавете изречения** във файла `marketing.txt`

4. **Commit & Push**:
   ```bash
   git add marketing.txt
   git commit -m "Team A: Add Round 1 sentences"
   git push -u origin team-a
   ```

5. **Създайте Pull Request към `main`** в GitHub

---

## 🔍 Workflow за Team Main

1. Следи за нови PR-и от team-a и team-b
2. Преглежда съдържанието, правопис и идеи
3. Коментира при нужда за промени
4. Мержва PR-и и разрешава конфликти
5. След финалното сливане – представя финалния `marketing.txt`

---

## 💡 Правила за добри практики
- **Branch имена:** `team-a`, `team-b`, `main`
- **Commit messages:** Формат `Team A: <описание>`
- **По 3 изречения на рунд.**
- **Не модифицирайте чужд раздел.**

---

## 🛠️ Полезни Git команди
- `git checkout -b <branch>` – създаване и смяна на branch
- `git add <file>` – добавяне за commit
- `git commit -m "<message>"` – commit с описание
- `git push -u origin <branch>` – push на branch
- `git merge <branch>` – сливане на branch
- `git revert <commit-hash>` – връщане към предишно състояние

---

## 🎉 Успех и приятно Git-ване!

> “Git е повече от инструмент – той е философия на съвместна креативност в дигиталната ера.”

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/HhZNnQ4h)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=19730074&assignment_repo_type=AssignmentRepo)
