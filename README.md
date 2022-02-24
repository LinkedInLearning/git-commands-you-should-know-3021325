# 8 Git Commands You Should Know
This is the repository for the LinkedIn Learning course 8 Git Commands You Should Know. The full course is available from [LinkedIn Learning][lil-course-url].

![8 Git Commands You Should Know][lil-thumbnail-url] 

If you’re a software developer, you probably already know that Git is one of the most useful version control systems out there. But while most developers have mastered the basics of Git, it can be a bit harder to take your skills to the next level and become an advanced Git user. In this course, instructor Ronnie Sheer shows you how to make the move from intermediate Git developer to the realm of finely tuned, source control expert.

Learn eight power-user Git commands that can save you time, prevent bugs, and more. Find out how to increase your productivity as well as minimize your moments of frustration. Ronnie walks you through a few basic tricks like stashing and adding changes, and then turns to more advanced techniques, such as undoing commits, reverting, and setting up precommit hooks. Test out your new skills with Git-command challenges along the way.

## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

## Installing
1. To use these exercise files, you must have the following installed:
	- [list of requirements for course]
2. Clone this repository into your local machine using the terminal (Mac), CMD (Windows), or a GUI tool like SourceTree.
3. [Course-specific instructions]


### Instructor

Ronnie Sheer 
                            


                            

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/ronnie-sheer).

[lil-course-url]: https://www.linkedin.com/learning/8-git-commands-you-should-know
[lil-thumbnail-url]: https://cdn.lynda.com/course/3021325/3021325-1645560341111-16x9.jpg
