# Tailwind JIT issue

Created using steps here: https://tailwindcss.com/docs/guides/create-react-app
Then enabling JIT using: https://tailwindcss.com/docs/just-in-time-mode
Then changed dependency to use 2.2.7 specifically.

1. `npm install`
2. `npm start`
3. Add a class in `App.js` like:

```
  <p className="text-red-700">
    Edit <code>src/App.js</code> and save to reload.
  </p>
```

4. See there is no color change.
5. Undo code change dependency to 2.1.4
6. Repeat 1-3
7. See color change.
