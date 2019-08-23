# Module Name

this is a proposal for how to reorganize the HYF content.  it tries addresses these concerns (among others):
* more structured practice and clarity of learning objectives for students
    * it's impossible to cover everything a student needs to learn in a weekly project and 4 hours of class.  Having module-long challenges build of coding challenges gives students a chance to practice the subskills necessary for the projects in a structured way
    * having a set of challenges that demonstrates what competences are expected of them by the end of a module is reassuring and helpful to students independent study
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

