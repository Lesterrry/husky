# 🦴 Husky
Your friendly neighborhood websocket messenger
<!-- ![Screenshot](https://user-images.githubusercontent.com/45698501/162725458-45244245-66b2-4820-922f-7c25e93d3c20.png) -->
![Screenrec](https://user-images.githubusercontent.com/45698501/164934110-f6177815-7e6c-4902-b6d1-db1bbaefd206.gif)

## What's this?
Husky is a combination of frontend and backend services made to provide websocket message exchange with encryption (todo) and no trace on server.

## How to use?
1. Clone the repo
2. Place `server.php` on your server to run as daemon
3. Modify `preconnect.php` following the comments inside  and place on the root path of the server
4. Modify `secure.php` following the comments inside (`USER_KEYS` are `username:password` formatted) and place it in the same path as `server.php`
5. Modify `secure.rs` following the comments inside
6. Build [Rust](https://www.rust-lang.org/tools/install) client app

## Recent activity [![Time period](https://images.repography.com/25115173/Lesterrry/husky/recent-activity/3a0bd8bf5820178f29f09247f5fca1d2_badge.svg)](https://repography.com)
[![Timeline graph](https://images.repography.com/25115173/Lesterrry/husky/recent-activity/3a0bd8bf5820178f29f09247f5fca1d2_timeline.svg)](https://github.com/Lesterrry/husky/commits)
[![Issue status graph](https://images.repography.com/25115173/Lesterrry/husky/recent-activity/3a0bd8bf5820178f29f09247f5fca1d2_issues.svg)](https://github.com/Lesterrry/husky/issues)
