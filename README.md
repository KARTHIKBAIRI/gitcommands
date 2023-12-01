# gitcommands
this is the complete gitdemo

# give credentials
=> git config --global user.name "karthik"
=> git config --global user.email "karthikbairi37@gmail.com"

# to check credentials
=> git config --ls

# clone data from github to our local system
->open vscode and any folder, now in the termial go to the folders path and enter,
=> git clone <http github repository link>
# To check the current status
=> git status

# After modifying data to track the changes by git & add it to git staging area,follow these 2 steps:
1. add => git add <filename>
       => To add all files once "git add ."
2. commit => git commit -m "some message"

# Update remote or git repository from local repository
=> git push origin main
