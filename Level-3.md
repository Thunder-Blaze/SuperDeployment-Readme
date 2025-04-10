## Level 3

**Render** - https://superdeployment-level-3.onrender.com/todos/

**Railway** - https://level04.thunderblaze.tech/todos/

- All services provide continous CD
- *Didn't deploy previous levels on Railway because I have hosted my dicord bot (Cp_Discord_bot) for last 2 months and have exhausted almost half of the credits and didn't wanted to exhaust more*
- Didn't deployed on vercel since vercel is serverless and also it will not retains the db file when it is redeployed
- Had to fix the folder not found error by creating that folder if it doesn't exist using fs module
- Also there were many minor mistakes in the sql syntax and variable names
- Added Dockerfile so that I could easily deploy it on railway
