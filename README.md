# Hello GitHub Actions Skill 🎉

You completed GitHub Skills' **Hello GitHub Actions** course—nice work! This repository captures the finished state of the exercise so you (or anyone else) can revisit what a working solution looks like.

## What you built

| Path | Why it matters |
| --- | --- |
| `.github/workflows/welcome.yml` | The learner-authored workflow. It posts a friendly comment to every newly opened pull request using the `gh` CLI and the automatically provided `GITHUB_TOKEN`. |
| `.github/workflows/0-start-exercise.yml` → `.github/workflows/5-step.yml` | A scaffold of facilitator workflows that drive the tutorial: they open the guidance issue, watch your progress, unlock each next challenge, and wrap up the course once the pull request is merged. |
| `.github/steps/*.md` | The step-by-step instructions the bot posts back to you. Each Markdown file explains a core Actions concept and includes the copy-pasteable YAML used in the checks above. |
| `.github/dependabot.yml` | Keeps the Actions used in this repository up to date on a monthly cadence. |
| `README.md` | This recap—share it with teammates who want a quick tour of the finished project. |

## How the automation flows

1. **Step 0** kicks off when the repository is initialized. It opens your guidance issue, publishes the first instructions, and enables the Step 1 validator.
2. **Steps 1–3** monitor pushes to your working branch. They confirm the workflow file exists, validate each addition (triggers, jobs, and steps), and post encouragement as you go.
3. **Step 4** waits for you to open a pull request into `main`, then guides you through reviewing and merging your changes.
4. **Step 5** celebrates the merge, posts the retrospective summary from `x-review.md`, and calls the shared “finish exercise” workflow.

All of these facilitator workflows are reusable building blocks from [`skills/exercise-toolkit`](https://github.com/skills/exercise-toolkit), so you can peek at those references to see how GitHub orchestrates multi-step learning experiences.

## Try the skill yourself

Want to repeat the exercise or help a teammate get started?

1. Visit [skills.github.com](https://skills.github.com/) and launch **Hello GitHub Actions**.
2. Follow the prompts to create a new copy of the course repository.
3. Work through the guidance issue—each comment links to the relevant Markdown file in `.github/steps/` for quick reference.
4. Merge your pull request and watch the welcome workflow run in the “Actions” tab.

## Keep leveling up

- Explore additional courses on [GitHub Skills](https://skills.github.com/).
- Browse the [GitHub Actions documentation](https://docs.github.com/actions) for deeper automation examples.
- Reuse the `welcome.yml` workflow in your own repositories to greet new contributors.

## Share your success

Let the world know you completed the course:

- [Share on X](https://twitter.com/intent/tweet?text=I%20just%20completed%20the%20%22Hello%20GitHub%20Actions%22%20GitHub%20Skills%20hands-on%20exercise!%20%F0%9F%8E%89%0A%0Ahttps%3A%2F%2Fgithub.com%2FMjWierzb%2Fskills-hello-github-actions%0A%0A%23GitHubSkills%20%23OpenSource%20%23GitHubLearn%0A)
- [Share on Bluesky](https://bsky.app/intent/compose?text=I%20just%20completed%20the%20%22Hello%20GitHub%20Actions%22%20GitHub%20Skills%20hands-on%20exercise!%20%F0%9F%8E%89%0A%0Ahttps%3A%2F%2Fgithub.com%2FMjWierzb%2Fskills-hello-github-actions%0A%0A%23GitHubSkills%20%23OpenSource%20%23GitHubLearn%0A)
- [Share on LinkedIn](https://www.linkedin.com/feed/?shareActive=true&text=I%20just%20completed%20the%20%22Hello%20GitHub%20Actions%22%20GitHub%20Skills%20hands-on%20exercise!%20%F0%9F%8E%89%0A%0Ahttps%3A%2F%2Fgithub.com%2FMjWierzb%2Fskills-hello-github-actions%0A%0A%23GitHubSkills%20%23OpenSource%20%23GitHubLearn%0A)

---

&copy; 2025 GitHub • [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) • [MIT License](https://gh.io/mit)
