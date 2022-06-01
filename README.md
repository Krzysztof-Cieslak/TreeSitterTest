1. `nvm install v18.2`
2. `node -v` (should output `v18.2.0`)
3. `npm install`
4. `npx tree-sitter build-wasm node_modules/tree-sitter-javascript`
5. `node index.js`
6. Observe failoure
7. `nvm install v18.0`
8. `node -v` (should output `v18.0.0`)
9. `node index.js`
10. Success
