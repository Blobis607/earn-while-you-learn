# Earn While You Learn

A community where young people in Nigeria learn job skills, earn naira doing small paid tasks for local businesses, and build a profile that proves what they can do.

**Live demo:** https://blobis607.github.io/earn-while-you-learn/
**Demo video:** _add your YouTube link here_

![Home page](screenshots/home.png)

## The problem

Many young Nigerians want digital skills but can't afford to spend months learning without earning. Even after learning, they have no work history to show employers. Meanwhile, small businesses need simple digital work, like flyers, spreadsheets and social media posts, but can't afford agencies.

## The solution

1. **Learn:** short lessons that work on a phone and use little data (graphic design, data entry, social media, basic coding).
2. **Earn:** pass a quick skill quiz to unlock small paid tasks posted by local businesses, then get paid in naira when the business approves the work.
3. **Grow:** every finished task, rating and badge goes on the learner's profile. Experienced learners earn tutoring fees by helping others in the community.

## Features in this prototype

| Page | What you can do |
|---|---|
| Home | See how it works and an example learner's earnings |
| Paid tasks | Filter tasks by skill and apply for one |
| Community | Post a message and like other posts |
| My profile | See skills, earnings, level and badges, and edit your profile |

Applying for a task updates the earnings and XP on your profile. Your profile is saved in your browser with `localStorage`.

> All people, tasks and amounts are sample data. No real payments happen in this prototype.

![Paid tasks](screenshots/paid-tasks.png)
![Profile](screenshots/profile.png)

## Built with

- HTML, CSS and JavaScript (no frameworks, no build step)
- Google Fonts (Bricolage Grotesque and Inter)
- Claude, an AI assistant, helped build the prototype

The site works on phones and supports light and dark mode.

## Run it locally

1. Download or clone this repository:
   ```
   git clone https://github.com/Blobis607/earn-while-you-learn.git
   ```
2. Open `index.html` in any web browser. That's it.

### Put it online for free (GitHub Pages)

1. In this repository on GitHub, go to **Settings → Pages**.
2. Under **Source**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then click **Save**.
3. After a minute, your site is live at `https://Blobis607.github.io/earn-while-you-learn/`.

## Project structure

```
earn-while-you-learn/
├── index.html      # the whole app: layout, styles and scripts
├── screenshots/    # images used in this README
├── README.md
└── LICENSE
```

## What's next

- Real payments through Paystack
- AI-generated lessons and quizzes
- AI matching learners to tasks that fit their skills and level
- Accounts and a real database so profiles and posts are shared

## Team

- _Your name_: idea, design decisions, voiceover
- _Teammate name_: _role_

## License

MIT. See [LICENSE](LICENSE).
