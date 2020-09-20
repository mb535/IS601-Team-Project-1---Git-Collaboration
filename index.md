# Introduction:

Docker created the industry standard for containers, which are self contained units of software packages that contain the application code and all related dependencies. Packaging and distributing as a package ensures that the code runs and functions reliably and efficiently across different environments.  The container is standalone  and contains everything required for the application to function effectively.

The use of containers eliminates the typical inefficiencies of distributing otherwise where the application code and it's required dependencies are installed separately, often by different teams or individuals, with no apparent connection. As the code moves through the test environment, it must be "setup" and configured repeatedly at each step. This is very time consuming, and has proven to be prone to mistakes and complications.

Use of Git, along with Docker and automated testing enables the software design principle of Continuous Integration. 

Git, a distributed version control system, enables developers to collaborate effectively and "check in" (commit) their code changes to the repository quickly, and on their own schedule. Commiting, though, is only the first step in "releasing" code to the users. Once the code is checked in, automated build scripts, it is built and tested automatically using scripts that react to the commits. This automated testing ensures the introduced changes pass all tests, meet standards and statisfy the functionality they are trying to solve. 

Using Git, Docker and automated testing to implement [continuous integration](https://en.wikipedia.org/wiki/Continuous_integration) enables companies to reduce time to market. New features can be introduced quickly, allowing not only quick reaction to customer demands, but also A/B testing, context labs, focus groups, etc. Developers can concetrate on developing new features and can "trust" the process to rollout their features effectively.

## GitFlow
    GitFlow is a branching model used for collaboration and scaling the development workflow.
    GitFlow can four key benefits: Parallel Development, Collaboration, Release Staging Area, and Support For Emergency Fixes
    
    - Parallel Development allows developers to isolate new development from finished work. New development (such as features and non-emergency bug fixes) is done in feature branches, and is only merged back into main body of code when the developers is happy that the code is ready for release.
    - Collaboration make it easier for two or more developers to collaborate on the same feature, because each feature branch is a sandbox where the only changes are the changes necessary to get the new feature working. That makes it very easy to see and follow what each collaborator is doing.
    - Release Staging Area allows new development to get merged back into the develop branch, which is a staging area for all completed features that haven’t yet been released. So when the next release is branched off of develop, it will automatically contain all of the new stuff that has been finished.
    - Support For Emergency Fixes allows branches made from a tagged release called hotfix branches.You can use these to make an emergency change, safe in the knowledge that the hotfix will only contain your emergency fix. There’s no risk that you’ll accidentally merge in new development at the same time.
## Commands and Terminology 
   - [Repository](Repository.md)
   - [Clone](Clone.md)
   - [Fork](Fork.md)
   - [Branch](Branch.md)
   - [Commit](Commit.md)
   - [Merge](Merge.md) 
   - [Checkout](Checkout.md) 
   - [Push](Push.md) 
   - [Pull](Pull.md)
   - [Remote Add / Remove / Show](Remote.md) 
   - [Status](Status.md) 
   - [Master Branch](MasterBranch.md) 
    
### Changelog
   - [link](readme.md)