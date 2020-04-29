**Explaining git concepts**

In this exercise, you will write an explanation for various git concepts.

Don't assume any prior knowledge of git: imagine you are explaining these concepts to a brand new software developer. Because of this, try not to use jargon.
Write full, complete prose. Bullet points can be useful, but not what we're after for this module.
Test the explanation. Try your explanation on a non-technical friend before submitting it.
We want explanations for:

GIT

1. Git is a free and open-source version.
2. Git is a content tracker. 
3. Git has Version Control System(VCS) 
4. Git has a remote repository .
5. Git is a Distributed Version Control System
6. Branches are highly important in the git world. 
7. Git Keeps track of all files in a project.
8. Record any changes to project files
9. Restore previous versions of files
10. Compare and analyze code
11. Merge code from different computers and different team members.


REPOSITORY

1. Repositories is a collection of files 
2. The VCS is used to create these versions and store them in a specific place termed as a repository.
3. Importing content into the repository using git tools is called cloning.
4. Users can also create a new repository or delete an existing repository.
5.Repositories can be divided into two types based on the usage on a server. These are:
	a.Bare Repositories
		->Share the changes that are done by different developers.
 		->A user is not allowed to modify this repository.
		->Not allowed the user to create a new version for this repository based on the modifications done.
	b.Non-bare Repositories
		->These are user-friendly.
		->Allow the user to create new modifications of files.
		->It allows creating new versions for the repositories. 
 		->The cloning process by default creates a non-bare repository.
		->if any parameter is not specified during the clone operation.


REMOTE

1. Used to create, view, and delete connections to other repositories.
2. They are like bookmarks rather than direct links into other repositories.
3. They serve as convenient names that can be used to reference a not-so-convenient URL.
4. git-remote - Manage set of tracked repositories
5. Remote is the version of something that is hosted on a server, most likely GitHub. 
6. It can be connected to local clones so that the changes can be synced


BRANCHING

1. Branch is a parallel version of a repository.
2. It is contained within the repository, but does not affect the primary or master branch allowing you to work freely without disrupting the "live" version.
3. Branch to isolate development work without affecting other branches in the repository. 
4. Each repository has one default branch, and can have multiple other branches. 
5. We can merge a branch into another branch using a pull request.
6. We can use the branch to Develop features, Fix bugs and
Safely experiment with new ideas.
7. We can also use a branch to publish a GitHub Pages site.
8. Only the repository administrator, can merge pull requests on branches with branch protections enabled even if the pull request does not meet the requirements, unless branch protections have been set to "Include administrators."

MERGING

1. Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another.
2. This often happens as a pull request (which can be thought of as a request to merge), or via the command line. 
3. A merge can be done automatically via a pull request via the GitHub web interface if there are no conflicting changes, or can always be done via the command line.
4. Git merge will combine multiple sequences of commits into one unified history.
5. Git merge is used to combine two branches.

MERGE CONFLICTS

1. Version control systems are all about managing contributions between multiple distributed authors.
2. Sometimes multiple developers may try to edit the same content.
3. If Developer A tries to edit code that Developer B is editing a conflict may occur.
4. To alleviate the occurrence of conflicts developers will work in separate isolated branches.
5. The git merge command's primary responsibility is to combine separate branches and resolve any conflicting edits.
6. Merging and conflicts are a common part of the Git experience.
7. Conflicts in other version control tools like SVN can be costly and time-consuming.
8. Git makes merging super easy. 
9. Most of the time, Git will figure out how to automatically integrate new changes.
10. Conflicts generally arise when two people have changed the same lines in a file, or if one developer deleted a file while another developer was modifying it.
11. In these cases, Git cannot automatically determine what is correct. 
12. Conflicts only affect the developer conducting the merge, the rest of the team is unaware of the conflict. 
13. Git will mark the file as being conflicted and halt the merging process.
14. It is then the developers' responsibility to resolve the conflict.
15. Types of Merge Conflicts are
	a. Git fails to start the merge
	b. Git fails during the merge


THE 3 GIT STATES:-
    The working directory, staging area, and the git directory.
    
    
	MODIFIED
		1. Git views untracked and modified files similarly. 
		2. Untracked means that the file is new to your Git project.
		3. Modified means that the file has been seen before, but has been changed, so is not ready to be snapshotted by Git.
		4. Modification of a file occurs in your working directory.
		
		
	STAGING
		1. When a file becomes staged, it's taken into the staging area.
		2.  This is where Git is able to take a snapshot of it and store its current state to your local repository.
		3.This area is also known as the Index.
		
		
	COMMITTED
		1.Committed means that Git has officially taken a snapshot of the files in the staging area.
		2. And stored a unique index in the Git directory.
		3. The terms snapshotted and committed are very similar. 
		4. The significance of being committed is that you can now revert back to this project's current state at any time in the future.
