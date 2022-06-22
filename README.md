# fake-commit-history



Generate GitHub Commits
A command-line tool to generate your GitHub activity graph.

Does your profile look like you have stopped coding at all? No worries, this script will help you.

How it works
How To Use
Make sure you have Git and Node.js installed on your machine.
Generate your commits:
npx fake-git-history
It will create my-history folder, initialize git and generate commits for every day within the last year (0-3 commits per day).
Create a private repository in your GitHub called my-history and push the changes:
cd my-history
git remote add origin git@github.com:<USERNAME>/my-history.git 
git push -u origin master
Done! Go take a look at your GitHub profile 😉

Customizations
--commitsPerDay
Specify how many commits should be created for every single day. Default is 0,3 which means it will randomly make from 0 to 3 commits a day. Example:

npx fake-git-history --commitsPerDay "0,5"
--workdaysOnly
Use it if you don't want to commit on weekends. Example:

npx fake-git-history --workdaysOnly
--startDate and --endDate
By default, the script generates GitHub commits for every day within the last year. If you want to generate activity for a specific dates, then use these options:

npx fake-git-history --startDate "2020/09/01" --endDate "2020/09/30"








>git clone "Project url"  
>git remote set-url origin " Your repo url"  
>  
>git filter-branch -f --env-filter "   
>GIT_AUTHOR_NAME='amTechie'  
>GIT_AUTHOR_EMAIL='alexlee.bizz@gmail.com'  
>GIT_COMMITTER_NAME='amTechie'   
>GIT_COMMITTER_EMAIL='alexlee.bizz@gmail.com'" HEAD  

