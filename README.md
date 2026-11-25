# პროექტის დასახელება - Corporate Landing Page Git Workflow

## პროექტის მიმოხილვა
პროექტი წარმოადგენს კორპორატიული ვებსაიტის (`index.html` და `style.css`) მარტივ სტრუქტურას, რომელზეც შესრულებულია ლოკალური და დისტანციური ვერსიების კონტროლი Git-ისა და GitHub-ის გამოყენებით, ბრენჩების შექმნით, გაერთიანებითა და Merge Conflict-ის მოგვარებით.

---

## გუნდის წევრები და Git როლები
* **გუნდის ნომერი:** ინდივიდუალური / გადაბარება (1 სტუდენტი)
* **სტუდენტი 1 (Repo Owner / გადაბარება):** ლუკა ჯანელიძე — Branch: `main`, `feature/header`, `feature/header-update`

---

## გამოყენებული Git ბრძანებები (Git Commands Used)
* `git init` / `git clone` — საცავის ინიციალიზაცია და კლონირება
* `git branch` / `git checkout -b` — შტოების შექმნა და გადართვა
* `git add .` / `git commit -m ""` — ცვლილებების ფიქსაცია
* `git push origin <branch>` — ცვლილებების ატვირთვა GitHub-ზე
* `git pull origin main` / `git merge` — ცვლილებების ჩამოქაჩვა და გაერთიანება
* `git status` / `git log --graph` — ისტორიის და სტატუსის მონიტორინგი

---

## Merge Conflict-ის მოგვარების ანგარიში
* **კონფლიქტური ფაილი:** `index.html`
* **კონფლიქტის მიზეზი:** `main` და `feature/header-update` შტოებში ერთდროულად შეიცვალა `<h1>` სათაურის ერთი და იგივე ხაზი.
* **მოგვარების გზა:** `git merge feature/header-update`-ის შემდეგ `index.html`-ში ამოიშალა `<<<<<<<`, `=======` და `>>>>>>>` მარკერები, დარჩა შეთანხმებული სათაური და შესრულდა `git add index.html` + `git commit` + `git push origin main`.

---

## მნიშვნელოვანი ბმულები
* **GitHub Repository:** https://github.com/ljanelidze007-sudo/corporate-landing-git-workflow
* **ჩემი ინდივიდუალური Branch:** `feature/header` და `feature/header-update`
* **ჩემი ბოლო Commit-ის ჰეში (Hash):** `<ჩასვით_ბოლო_commit_hash>`
