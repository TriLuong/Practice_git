Summary about git command

----------------
Create a repo to store all source

	git init

Add source to repo

	git add <source_name>

Add a commit

	git commit -s

Push source code to server

	git push origin <branch/tag_name>

Fetch source from repo

	git clone <directory or url of repo>

Pull all new updated source from repo (after fetching source from repo)

	git pull

Create a branch 
	
	git branch <branch_name>

Create a tag (annotated tag)
	
	git tag -a <tag_name> -m '<type content of tag>'

-----------------
To type username and password when pushing to git ONE TIME

	git config credential.helper store

-----------------	
