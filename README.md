# ⚡ TechStudents Landing Page

A hands-on practice project for learning Git & GitHub workflows as a 4-member team.

## 🗂️ Project Structure

```
student-website/
├── index.html                  ← Main HTML (Person 1)
├── css/
│   ├── style.css               ← Base styles + Navbar + Hero (Person 1)
│   ├── team.css                ← Team & Skills sections (Person 2 & 3)
│   └── contact.css             ← Contact section (Person 4)
├── person2-team-cards.html     ← Person 2's snippet to paste into index.html
├── person3-skill-cards.html    ← Person 3's snippet to paste into index.html
├── person4-contact-form.html   ← Person 4's snippet to paste into index.html
└── README.md                   ← This file (Person 4 maintains it)
```

## 👥 Team Roles

| Person | Role | Their Section | Branch Name |
|--------|------|--------------|-------------|
| Person 1 | Lead Developer | Navbar + Hero + Footer | Sets up repo |
| Person 2 | Frontend Dev | Team Section cards | `feature/team-section` |
| Person 3 | Backend Dev | Skills Section cards | `feature/skills-section` |
| Person 4 | Tester & Docs | Contact Form | `feature/contact-section` |

## 🚀 How to Run

Just open `index.html` in your browser — no server needed!

## 🌿 Branch Workflow

```
main
  └── develop
        ├── feature/team-section      ← Person 2
        ├── feature/skills-section    ← Person 3
        └── feature/contact-section   ← Person 4
```

## ✅ Practice Goals

- [ ] Person 1: Create repo, develop branch, invite team
- [ ] All: Clone repo, switch to develop
- [ ] Person 2: Add team cards → commit → push → PR
- [ ] Person 3: Add skill cards → commit → push → PR
- [ ] Person 4: Add contact form → commit → push → PR
- [ ] Person 1: Review all PRs → merge each one
- [ ] All: Sync develop after each merge
- [ ] Person 1: Final merge develop → main
