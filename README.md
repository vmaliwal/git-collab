## Git overview
This covers an overview of git.  It incormorates the key things you need to know, some of the history and some tips from working with git.

##Set-up steps

- run
```
npm install
grunt serve
```

- Make changes by modifying index.html

**Changes must me pushed to the Github repo's gh-pages for the statis site to build.

- Then visit ```<username>.github.io/<project name>```
  - [View this presentation.](http://aln787.github.io/git-collab/)

##Talk Outline

####Overview

1. What is Git
1. Git Key Concepts
1. Git in Action
1. Additional Git Concepts
1. Collaboration
1. Merge Conflicts
1. Advance Commands / tips and tricks
1. My personal collaboration workflow for a hackathon
1. References

####Details

  - Intro - Kaylyn and Alex
    - Discuss Hackathon Mentorship
  - Why discuss git today? 
    - Covering because at most hackathons see students who either have only used git individually or who don't understand the power of git.
    - Git as your the savior of your project - Victory and yelling at the computer 

1. What is Git
  - Talk about Linus Creating git, what drove him to go this how long this initial process took
    - Who has used VCS other than git
    - Who has heard of Linus Torvold?
    - (Confirm in the article from Jim) He created the initial framework in a weekend and after a few hours it was self hosting or being used for the project’s version control
1. Animation Project Demo
  - Fire up the summit VM
  
    ```
    username: summiteer
    password: capitalone
   ```
    - cd /media/sf_shared
  - Login demo
    - cd /animationExamples/loginExample
    - git checkout static
      - Show in xcode - view with background issues and no animations
    - git checkout dynamic
      - Show in xcode - view with animations added, background issue remains
    - git checkout background
      -  Show in xcode - animations added and background issue resolved
  - Flight Demo
1. Git Key Concepts
  - Staging Area / Working Copy
  - Git Repository
    - What is included in .git
  - Branches
    - git branch -r
  - Merging
1. Git in Action
  - git status
    - Tracked vs untracked files / changes
  - Git Diff
  - init
  - Clone
  - Commit
1. Additional Git Concepts
  - (Git Config)
  - .gitignore
1. Collaboration
  - Remote Repository
  - Pulling Remote Changes
  - Multiple remotes
  - Fork and pull
1. Merge Conflicts
  - Merge Conflict example (potentially one for the calss to work through together)
1. Advance Commands / tips and tricks
  - *Unsure what to do?*
    - Copy the directory you are working on and you will be able to roll back if you have any issues
  - Rebase 
    - Discuss how this is different than a merge 
  - Squash
  - Amend
  - SSH keys
  - Aliases
1. My personal collaboration workflow for a hackathon
 - Show the summit app as an example
 - Everyone's commit history is initally messy, some clean it up with rebase or squash
1. References

##Other Resources
- [A Yeoman generator for the awesome Reveal.js presentation framework.](https://github.com/slara/generator-reveal)
