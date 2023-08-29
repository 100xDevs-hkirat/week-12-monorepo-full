### Monorepo
The monorepo contains
 - An express backend
 - A React frontend
 - A Next frontend


 ## Initial deploy
 
 ```
    pm2 start npm --name "react" -- run "start:react"
 ```

 ```
    pm2 start npm --name "next" -- run "start:next"
 ```

 ```
    pm2 start npm --name "express" -- run "start:express"
 ```
