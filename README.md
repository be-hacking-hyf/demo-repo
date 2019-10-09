> there are 4 modules testing out versions this structuring: [databases](https://github.com/hackyourfuturebelgium/databases), [node](https://github.com/hackyourfuturebelgium/node.js), [html/css](https://github.com/be-hacking-hyf/html-css-github), [js-1](https://github.com/be-hacking-hyf/javascript-1)

# Module Name

this is a proposal for how to reorganize the HYF content.  it tries addresses these concerns (among others):
* embed development workflow into the content from module 1
    * git/github & collaborative workflow can't be taught in a sunday or two before the final project.  the students need to be living these skills from the beginning if they are to really leave prepared for a job
    * the repository contains only code the student needs to study and complete, like real collaboration.  
    * readings, lesson plans, ... are all hosted in the wiki.  a bit like the separation between documentation and source code
* more structured practice and clarity of learning objectives for students
    * it's impossible to cover everything a student needs to learn in a weekly project and 4 hours of class.  Having module-long challenges build of coding challenges gives students a chance to practice the subskills necessary for the projects in a structured way
    * having a set of challenges that demonstrates what competences are expected of them by the end of a module is reassuring and helpful to students independent study
* intentional project scaffolding to teach architecture, incremental development, practice working with existing code, and avoid "blank page" syndrom:
    * students are not asked to build projects from scratch from week 1.  instead they are given code to complete and modify in week 1, in week two code to complete and debug, and in week 3 asked to build from scratch with the same architecture, language features and coding techniques as in previous weeks
    * each week's project uses the same architecture and language features, but asks student to implement different behavior.  this will help to explicitly teach how to plan and structure applications from a list of behvioral requirements
* being more intentional about contribution
    * moving lesson plans and study materials to [the module wiki](https://github.com/be-hacking-hyf/demo-repo/wiki) makes it very easy for coaches and students to continually improve the study & Sunday experience without dispersing their contributions and examples in branches or having to wait for PR's to be accepted
    * gate-keeping the challenges and core project material will ensure that there is a consistency of quality and vision to the core content students are expected to complete for their portfolio
* make it possible for coaches to participate on more flexible schedules, here are 3 proposed coach roles:
    * Project Coaches: they must come in on sundays and are responsible for teaching and grading weekly projects.  they guide students on project management, collaboration, and the big picture
    * Homework(challenge) Coaches: they have no in-person obligation.  their role is to support and code-review student challenges, helping students with the smaller skills of development
    * Tutor coaches: this role is to provide a continuity of support to students throughout the whole HYF curriculum.  they will be assigned a group of 3-5 students (ie. 3-5 coaches per class) that they will help out from module 1 through the final project, ~4/6 hrs permodule.  They have no fixed schedule or in-person commitment 
* central student tracking 
    * it will be easier to see how each student is progressing when coach feedback is centralized on their repo instead of buried in closed PR's on the HYF repo.  
    * (read the next section for more on this)


Along with reformatting the content it could be helpful to revisit the homework submission process.  Instead of students pulling their changes to the HYF fork, it could be better if coaches review the students' repos directly with issues, patches and PR's.  his would put all coach feedback for each student directly on their fork which would have several advantages:
* homework repos will be more useful later on when students try to review their coursework
* we could ask student to use github projects to track their progress
* we could write a "simple" web interface that uses the github api to assess their repos and report on a central dashboard (ie. are all pr's & issues closed, is there a branch with name $%*#, did it pass CI, ...)
After students become familiar with this process it would even be neat if students code-reviewed each other weekly projects and coaches reviewed their reviews (meta michiel).


