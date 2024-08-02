## React 19 / Next 15 Streaming Bug

Step 1: Start the server

```
npm run dev
```

Step 2: Go to http://localhost:3000/completion-rsc

Step 3: Enter longer completion text e.g. "tell me about berlin" and press enter

Step 4: Wait, completion gets rendered after a while in one go. It should have been streamed.
