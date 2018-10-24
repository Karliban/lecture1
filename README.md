# lecture1
Adding a second branch - called 'feature'

1: git branch feature // add the feature branch
2: chnage to that branch -> git checkout branch // Switched to branch 'feature'
3. do normal git add <file.name> & git commit -m "..."
4. git push - you'll get the following message:
  
  "fatal: The current branch feature has no upstream branch.
  To push the current branch and set the remote as upstream, use
  git push --set-upstream origin feature"
  
  // this means that the locally created branch 'feature' has no corresponding branch on github
  
  5. copy the following command: git push --set-upstream origin feature // as seen in the alert itself
  6. Done!
