An issue I ran into today.. This solved it

"So what happened in my case , I opened GitBash and typed git init to initialize a repo but , what actually happened was my C drive whole folder was made a repo and that is why it was showing 10000 changes detected to revert the changes or discard , Remove the directory :

1. Open git bash
2. Type rm -rf .git on it and press enter
3. This command will remove that repo no files will be deleted its safe to use
4. Create a new repo to push



Video @ 20:58