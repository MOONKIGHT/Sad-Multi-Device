worker: npx pm2 start npm --node-args="--optimize_for_size --max_old_space_size=460" -- run db && npx pm2 logs
worker1: npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs
worker2: npm start
worker3: npm i -g forever && forever index.js
worker4: npm i ffmpeg@latest && npm i @adiwajshing/baileys@3.5.3 && npm i -g forever && forever index.js
