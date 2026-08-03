# Lexicon - Git Demo
A github demo for Lexicon's course about frontend development and it stuff.

# 🚀 Git & GitHub – Gruppövning

## 🎯 Mål

Målet med övningen är att ni ska arbeta tillsammans precis som ett riktigt utvecklingsteam.

När övningen är klar ska ni ha tränat på att:

* Skapa ett GitHub-repository
* Klona ett repository
* Arbeta i egna branches
* Göra commits
* Pusha kod till GitHub
* Skapa Pull Requests
* Reviewa varandras kod
* Lösa merge conflicts

---

# 👥 Roller

Fördela rollerna inom gruppen.

* 👨‍💼 Projektledare
* 👩‍💻 Utvecklare 1
* 👨‍💻 Utvecklare 2
* 👩‍💻 Utvecklare 3

> **Projektledaren** ansvarar för repositoryt och hjälper gruppen att hålla ordning på arbetet.

---

# 🛠️ Del 1 – Skapa projektet

## Projektledaren

1. Skapa ett nytt **Public GitHub Repository**
2. Döp det till **git-demo**
3. Lägg till övriga gruppmedlemmar som **Collaborators**
4. Klona repositoryt
5. Skapa följande filer:

```text
index.html
style.css
```

Lägg in följande HTML:

```html
<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="UTF-8">
    <title>Git Demo</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<h1>Git Demo</h1>

</body>
</html>
```

Skapa den första commiten.

```bash
git add .
git commit -m "Initial commit"
git push
```

---

## Övriga gruppmedlemmar

Klona repositoryt.

```bash
git clone <repo-url>
```

Öppna projektet i VS Code.

---

# 🌿 Del 2 – Skapa en egen branch

Alla ska nu skapa en **egen branch**.

Exempel:

```text
feature-header
feature-footer
feature-button
feature-nav
```

Skapa och byt till branchen.

```bash
git switch -c feature-header
```

Kontrollera vilken branch du står på.

```bash
git branch
```

---

# 💻 Del 3 – Bygg webbsidan

Alla arbetar nu **självständigt** i sin egen branch.

## 👨‍💼 Projektledaren

Lägg till en `<nav>`.

---

## 👩‍💻 Utvecklare 1

Lägg till en `<header>`.

---

## 👨‍💻 Utvecklare 2

Lägg till en `<button>`.

---

## 👩‍💻 Utvecklare 3

Lägg till en `<footer>`.

---

När du är klar:

```bash
git add .
git commit -m "Beskriv vad du gjort"
git push
```

💡 Exempel på bra commit-meddelanden:

```text
Add navigation
Create page header
Add footer
Add CTA button
```

---

# 🔀 Del 4 – Pull Request

När din branch är pushad:

1. Skapa en **Pull Request**
2. Be en gruppmedlem granska den
3. Åtgärda eventuella kommentarer
4. Mergea Pull Requesten

> **Regel:** Ingen får mergea sin egen Pull Request innan någon annan har granskat den.

---

# ⚠️ Del 5 – Merge Conflict

Nu ska alla skapa en konflikt.

Alla ska ändra **samma rad** i `index.html`.

Original:

```html
<h1>Git Demo</h1>
```

Ändra till något eget.

Exempel:

```html
<h1>Frontendutvecklare</h1>
```

eller

```html
<h1>Git & GitHub</h1>
```

eller

```html
<h1>Grupp 3</h1>
```

Commita och pusha ändringen.

Försök sedan mergea Pull Requesten.

🎉 Minst en merge conflict ska uppstå.

---

# 🧩 Del 6 – Lös konflikten

När konflikten uppstår ska gruppen tillsammans:

* Identifiera konflikten
* Läsa konfliktmarkeringarna
* Diskutera vilken version som ska sparas
* Redigera filen
* Ta bort konfliktmarkeringarna
* Spara filen
* Köra:

```bash
git add .
git commit
git push
```

---

# ⭐ Bonusuppgifter

Om ni blir klara före de andra:

### 1. Visa historiken

```bash
git log --oneline
```

---

### 2. Se ändringarna

```bash
git diff
```

---

### 3. Byt mellan branches

```bash
git switch main
git switch feature-header
```

Vad händer med filerna?

---

### 4. Ångra en ändring

```bash
git restore .
```

---

# ✅ Checklista

När ni är klara ska ni kunna bocka av allt nedan.

* [ ] Alla har klonat repositoryt.
* [ ] Alla har arbetat i en egen branch.
* [ ] Alla har gjort minst en commit.
* [ ] Alla har pushat till GitHub.
* [ ] Alla har skapat en Pull Request.
* [ ] Alla har reviewat en annan persons Pull Request.
* [ ] Gruppen har löst minst en merge conflict.
* [ ] Alla ändringar finns i `main`.

---

# 💬 Diskussionsfrågor

Diskutera tillsammans innan ni är klara.

1. Varför arbetar man i egna branches istället för direkt i `main`?
2. Vad är syftet med en Pull Request?
3. Varför uppstår merge conflicts?
4. Hur kan man minska risken för merge conflicts?
5. Vad var svårast under övningen?
6. Vad tycker ni var den största fördelen med Git jämfört med att skicka filer mellan varandra?

---

# 🎉 Klart!

Om allt fungerat har ni nu arbetat ungefär på samma sätt som ett professionellt utvecklingsteam.

Bra jobbat! 🚀