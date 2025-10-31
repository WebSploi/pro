# Vercel Memory Repo Host (Demo)

This is a demo Next.js app that lets you upload a `.zip` repository in the browser,
unpacks it client-side, and sends the files to the server which stores them in-memory.
You can then browse the repo and copy raw links like:

`/api/raw/<repoId>/<path/to/file>`

**Limitations**
- Storage is in-memory and ephemeral. Use Supabase/S3 for persistence.
- Not for production. No auth. Don't upload secrets.

**Run locally**
```
npm install
npm run dev
```
Open http://localhost:3000
