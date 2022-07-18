# template-git-repo

1) First create a new public repo(In private repo you can't edit *Branch protection rules*) <br/>
2) Edit <b>*Branches*</b> under <b>*Code and automation*</b> => default branch should be <b>main</b> <br/>
3) Add a new role under <b>*Branch protection rules*</b> and the check <b>*Require a pull request before merging*</b>
   check for <b>*Require approvals*</b> and set it to be 1.<br/>
   When enabled, all commits must be made to a non-protected branch and submitted via a pull request before they can be merged into a branch that matches      this rule.
4) Go down and check <b>*Include administrators*</b> <br/>
   Enforce all configured restrictions above for administrators.
5) Clone the git repo that was created to your computer(~dev/*repo-name*)
6) Add/Commit and then push(git push --set-upstream origin *branch-name*) 
7) That's it you are ready to go!
