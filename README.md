# Module 1 Urban Design Quiz

A responsive, static multiple-choice quiz for Module 1: Introduction to Urban Design.

## Deploy to Vercel

### Option 1: Deploy with the Vercel website
1. Create a GitHub repository and upload `index.html`, `vercel.json`, and this README.
2. Sign in to Vercel and choose **Add New → Project**.
3. Import the GitHub repository.
4. Choose **Other** as the framework preset if Vercel asks.
5. Leave the build command and output directory empty (or use the project root as the output directory).
6. Click **Deploy**.

### Option 2: Deploy with Vercel CLI
1. Install Node.js and the Vercel CLI.
2. Open a terminal in this folder.
3. Run `vercel` and follow the prompts.
4. For a production deployment, run `vercel --prod`.

No build step or environment variables are required. The site is a static HTML/CSS/JavaScript project.

## Quiz behaviour
- Welcome screen says “Welcome, Maryam”.
- 20 multiple-choice questions, shown one at a time.
- Immediate feedback and a short explanation after each answer.
- Progress indicator, back/next navigation, final score, answer review and retry.
- Questions cover Module 1 topics only.
