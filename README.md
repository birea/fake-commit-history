# fake-commit-history












>git clone "Project url"  
>git remote set-url origin " Your repo url"  
>  
>git filter-branch -f --env-filter "   
>GIT_AUTHOR_NAME='amTechie'  
>GIT_AUTHOR_EMAIL='alexlee.bizz@gmail.com'  
>GIT_COMMITTER_NAME='amTechie'   
>GIT_COMMITTER_EMAIL='alexlee.bizz@gmail.com'" HEAD  

