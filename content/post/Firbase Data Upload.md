---
title: "Firebase Data Upload"
date: 2021-03-20T20:03:58-05:00
draft: false
---
https://www.youtube.com/watch?v=Qg2_VFFcAI8
https://medium.com/@devesu/how-to-upload-data-to-firebase-firestore-cloud-database-63543d7b34c5
link to json uploader --> Make private file for personal records that are git ignored
Tips
node uploader.js --> to run

-- remove lists that you have already uploaded from the "files" folder

-- if you run into errors running the uploader delete .DS_store file in the "files folder"

--SyntaxError: Invalid or unexpected token
    at Object.compileFunction (node:vm:355:18)
    at wrapSafe (node:internal/modules/cjs/loader:1022:15)
    at Module._compile (node:internal/modules/cjs/loader:1056:27)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1121:10)
    at Module.load (node:internal/modules/cjs/loader:972:32)
    at Function.Module._load (node:internal/modules/cjs/loader:813:14)
    at Module.require (node:internal/modules/cjs/loader:996:19)
    at require (node:internal/modules/cjs/helpers:92:18)
    at /Users/littlewhelan/Documents/Code/JSON/uploader.js:22:16
    at Array.forEach (<anonymous>)
