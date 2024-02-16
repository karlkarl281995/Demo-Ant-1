# Demo-Ant-1
Integrate Ant with Jenkins

For Git you need to create the remote Repo, through Git Hub and include the readME file.

Once this is done, you need to copy the file path, //HTTPS 

1. Go to your local repo 
2. Create the Directory mkdir <name> ,, mkdir helloworld
3. cd helloworld
4. vi build.xml file
5. save build.xml file with wq!
6. Then run git init command, and make sure you are in correct directory (mkdir helloworld)
7. Run git add . Command
8. Run git commit -m “Add new files” command
9. Run git remote add origin <repository_url> command. (This includes your https repo)
10. Run git push -u origin master command or git push -u origin main command. (Depends on the name of your branch)

To Establish connection with local and repo and pass Authorization you need to generate a token

1. Go to settings, then Developer Settings
2. Generate Key Pair Token (classic) 
3. Select the First box in each category
4. Once you do this you need to save the token key pair, on a clipboard or notes file
5. When prompted during git push, enter this token into the password field. 
6. Success

* Key Takeaways
1. Make sure to choose the Branch Specifier as Master or Main, depending on the local repo configuration. 
2. Make sure Java is installed in your local repository

