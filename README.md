# Assessment 1 — Hello World

Your first git workflow, start to finish. Follow the five steps exactly.

## The assignment

1. **Clone this repo**
   ```
   git clone https://github.com/icstars-milwaukee/assessment-1.git
   cd assessment-1
   ```
2. **Create your own branch** — named `firstname-lastname`, all lowercase:
   ```
   git checkout -b firstname-lastname
   ```
3. **Edit `HelloWorld.md`** — add a section with your name as the heading and a
   hello-world message in your own words. Keep the example section intact.
4. **Commit your change** with a message that says what you did:
   ```
   git add HelloWorld.md
   git commit -m "Add my hello world section"
   ```
5. **Push your branch** (not main — main is locked):
   ```
   git push -u origin firstname-lastname
   ```

You are done when your branch shows on GitHub with your edit on it.

## Rules

- One branch per person, named after you.
- Do not push to `main` — it is protected and will refuse you.
- Do not edit anyone else's section.
