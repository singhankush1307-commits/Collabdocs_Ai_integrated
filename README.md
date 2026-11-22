# Collabdocs_Ai_integrated
## About

CollabDocs is a real-time collaborative document editor, similar to Google Docs. Several people can write in the same document at the same time and see each other's changes and cursors instantly. It uses Yjs (a CRDT) over Socket.io, so edits never conflict, even when users work offline or at the same moment.

It also includes an AI assistant, powered by Gemini or OpenAI, that can summarize, rewrite, and transform selected text. Documents can be shared through links with different permission levels (Owner, Editor, Commenter, Viewer), and every document keeps a version history.

Built with React, Node.js, Express, and MongoDB.

## Run Locally

```bash
git clone https://github.com/<your-username>/collabdocs.git
cd collabdocs
docker compose up -d mongo
cp .env.example .env
npm install
npm run dev
```
