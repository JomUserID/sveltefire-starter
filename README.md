# SvelteFire Starter

Starter template for full-stack serverless web applications using SvelteKit, Firebase, Tailwind CSS, DaisyUI, and SvelteFire.

## Tech Stack

- [SvelteKit](https://kit.svelte.dev/)
- [Firebase](https://firebase.google.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [DaisyUI](https://daisyui.com/) - UI component library for Tailwind CSS
- [SvelteFire](https://sveltefire.fireship.io/) - Use realtime Firebase data using Svelte components and stores!

## How to Use This

This is intended to be an easy starter template for projects using this tech stack.


1. Clone the repository:

```bash
git clone https://github.com/JomUserID/sveltefire-starter/
```

2. Remove the Git origin:

```bash
cd sveltefire-starter
git remote remove origin
```

3. Give it a new name:

```bash
cd ..
mv sveltefire-starter your-project-name
cd your-project-name
```

You should also replace all instances `"sveltefire-starter"` with `"your-project-name"` in `package.json` and `package-lock.json`.

4. Install the dependencies:
```bash
npm install
```

5. Hook it up to a Firebase project and app:

Head over to [Firebase](https://console.firebase.google.com/) to either create a new project and application or connect it to an existing one. 

6. (Optional) Set up a new GitHub repository and add it as the new origin:

```bash
git init
git add .
git commit -m "Initial commit"

git remote add origin https://github.com/your-username/your-project-name/
git push -u origin main
```