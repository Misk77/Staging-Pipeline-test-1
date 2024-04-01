# Staging-Pipeline-test-1
github action staging pipeline  
developers branch for pr and push and if we are satisfied with the code we want a manual trigger for merging to master  


This workflow will trigger on pull requests and pushes to the developer branch.  
Once the code is built and tested  successfully, it will wait for a manual trigger (workflow_dispatch) to merge to the master branch.  

This works but we need to change the base manually to branch staging fomr the working branch


notes:
1. Make it easier if the default branch is the staging branch
2. master and staging should be protected
3. master requrires reviews


PR 8

