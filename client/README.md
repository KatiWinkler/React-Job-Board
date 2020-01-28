# React-Job-Board
-Used React, Material UI, JSON, Redis, Node.js, and Express to create this dynamic app to aid junior developers in their search for a job 
-I created this to refresh every hour with the help of cron, as well as used an algorithm to filter out senior position job openings 
-Future Improvements: 
1. CSS for better UI/UX
2. Add additional APIs 
3. Upgrade algorithm to be more accurate 

--To run the app before deployment:

Terminal 1: 
cd client 
yarn start 

Terminal 2:
redis-cli
get github

Terminal 3:
node worker/tasks/fetch-github.js

Terminal 4:
node api/index.js
