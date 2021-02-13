git init <name>          #will make a directory with name <*****> in pwd. inside this name directory there will be a hidden directoyry with name .git in which
                         there will be lot of information 
                         # if you will type "git init" only it will start make a repository with name .git in pwd
                         # now cd to repository   cd <*****> then add there files. Please dont forget there already exist a hidden directory with name ".git"
                         #if you initialized repository with comand .."git init"  then in pwd .git directory exists and you can add fiels here itself
                         
git add <filename>    will add file to repository
                     
git rm  --cached <filename>  # to remove the file without befor making commit

git config --global user.email "you@example.com"    #add your email address to git repository(omit --global if you want to add this configuration to this 
git config --global user.name "yourname"            # repository only
                     
 
git commint -m "your commit message"               #commit messages are usedually red as : this commit is to "your commit message" 

git remote add origin <url>      #first crate a reapository on github(using browser) copythe url of repository and paste
                                 #if remote origin already exists then remove that origin by commad  $git remote rm origin
                                 #please mind origin is just a name you could use anotehr name(like peg_git)

git push origin master           #will push origin to master branch or remote server 
                                 #or git push peg_git master
                                 
