# Project Management Plan for Team-Based Software Engineering

## Questions to Answer for Team-Based Software Engineering

- How will you inventory the skills of team members to determine who is
  suited for specific tasks?

  Identify and list skills that are relevant to the project, such as skills for
  resolving issues with GitHub workflow, debugging, problem-solving, and markdown
  skills. Each team member will assess their skills with “Assessment Guidelines”
  and identify areas they are experts in, areas they do not have much experience
  with, and skills they would like to practice and improve. Project managers are
  responsible for keeping track of who is good at what, but team members must
  also be communicative and open to volunteering.

- How will you divide the entire team into sub-teams assigned to complete
  specific tasks?

  - Specify Tasks

    When dividing the entire team into sub-teams, the first step is realizing all
    the tasks that need to be accomplished. This includes making an expansive list
    of tasks and taking care not to overlook details even if they seem unimportant.

  - Divide Tasks into Categories

    Once a comprehensive list of tasks exists, the next step is to divide these
    tasks according to category of labor. The distribution of tasks should be as
    even as possible while remaining accurate.

  - Divide Team Evenly

    Each sub-team should contain members with different skills so that groups can
    divide their assigned labor accordingly. For example, each group should have
    a `Project Manager` that is able to oversee group operations and communicate
    with other group managers. Outside of the project managers their should be project
    specialists whose role should be specific to the entire group's project, based
    on what needs to be done. This will provide each group with lateral communication
    and allow for individual members to communicate with project specialists outside
    of their own groups.

  - Assign Tasks to Teams

    As for specific tasks, project specialists and project managers can take the
    tasks that most pertain to them and any other tasks that they may feel comfortable
    undertaking. This will speed up the production process as teams will have greater
    autonomy over handling tasks within a category.

- How will you ensure everyone has the opportunity to master all software
  engineering skills?

  Project managers will communicate with each other and the team members regarding
  what we have and have not worked on yet, so they can properly organize the work
  among the groups. We must make sure that people get to do work outside of their
  first role for each project. Team members should be given opportunities to try
  new skills with each project.

- How will you run the course sessions to ensure that you use them
  to maximum effectiveness?

- When and how frequently will you give demonstrations of the software that
  you are engineering?

  The frequency of updates and demonstrations will be largely dependent upon the
  intended audience and partially dependent on the scale of said updates.
  Updates should be delivered relatively frequently in order to encourage
  adherence to deadlines as well as maintain cross-team structure. Ideally,
  lesser updates delivered within individual teams should be delivered once or
  twice a week from assigned team members, while requests for team feedback
  concerning the professor and teaching assistants should be delivered roughly
  once every two weeks. Demonstrations should likely also be made for faculty
  outside of this course, as the products of this class are being developed with
  the intent of their distribution for use by the Computer Science department.
  These demonstrations should be made every two to three times a project depending
  on faculty concerns.

- How will you adjust the project's schedule if the team falls behind on the
  completion of tasks?

- How and when will your team conduct blame-less postmortems to resolve
  project mistakes?

  - Creating a blame-less postmortem:

    They should be created immediately when a team member notices the
    issue. These will be discussed in a Github issue tracker with a
    `blame-less postmortem` tag in the title. You may assign specific people to the
    issue tracker, on the basis that they are well suited to solving the problem.
    You should not assign people because you believe they created the error.
    New group members can be assigned after the initial creation of the issue tracker.

  - Responding to a blame-less postmortem:

    We will take on blame-less postmortems as collective problem that is our
    responsibility to solve. These postmortems should be viewed as learning opportunities
    that will enhance our technical and professional abilities. When discussing the
    details of the postmortem you should not directly or indirectly blame
    any one group or individual. Everyone's concerns in the issue tracker
    should be listened to and considered when developing a fix. The point
    of this is to pool our expertise and devise a solution that solves and
    prevents future errors.

  - Closing a blame-less postmortem:

    Postmortems can only be closed if there's empirical evidence showing that the
    problem is no longer present. Additionally everyone assigned to the blame-less
    postmortem has to agree that the problem has been solved, and that the issue
    racker can be closed. The issue cannot be closed just because a build passes
    checking software such as Travis-CI.

- How will your team elicit, analyze, and document the requirements for the
  software project?

  Elicit the requirements for the software project by talking to the customer(s),
  the student technical leaders and instructor. Determine the features that would
  be needed to create a fully functional version of the requested software to
  formulate the software project requirements. Analyze each requirement and how
  it fits into the overall scope of the project. Break down the requirements into
  sub-requirements if necessary and prioritize them. Document the requirements
  for the software project on GitHub in the Issue Tracker or elsewhere if
  necessary, such as within the README or in Pull Requests. The process of
  eliciting, analyzing, and documenting the requirements for the software project
  should actively continue throughout the project, not just at the beginning, as
  things oftentimes change during the software engineering process.

- What will your team do if it determines that it cannot feasibly implement
  promised features?

  If a feature is unable to be implemented after the task was distributed to team
   members, the team should research and discuss alternative resolutions. If the
   team makes the decision that there are no feasible alternative solutions, team
   members need to be able to move forward on implementing other promised features.
   It is better to fully implement some promised features than only partially
   implement all features. However, be aware that the team should do research at
   the pre-implementation stage of the project to decide if a feature is feasible.
   Team members should follow the GitHub Flow model to communicate with each other
   during the process of resolving the unimplementable feature.

- What is your team's software development and testing process for creating
  new features?

  - Utilize the Issue Tracker:

    When developing a new feature the first step is to create an issue in the
    GitHub Issue Tracker. This issue should outline the purpose of the new
    feature and the steps needed for feature development. If this feature solves
    any current issues open in the Issue Tracker, connect the issue numbers.
    Next, assign the members of your development team and request feedback
    from team members, Technical Leaders, and the course instructor.

  - Create a Branch:

    The next step is to create a branch off of master with the following naming
    convention: `feature/description-of-the-feature`. All the work for the new
    feature should be completed and committed in this branch to avoid
    merge conflicts and breaking the current build.

  - Write Test Cases:

    Once you feel that your feature is complete, you can begin to test your
    feature by writing test cases. Test cases should be written in the appropriate
    fashion for the programming language being used, in the instance of
    this course you should use pytest. To ensure clarity, use descriptive names
    for your tests. Make changes where necessary depending on the accuracy of
    your tests.

  - Open a Pull Request and Merge:

    After testing the feature, and gaining confidence in code correctness,
    open a PR in GitHub. Request the review of team members, Technical Leaders
    and the course instructor, making changes where necessary until the new
    feature is ready to merge.

- What process will the team follow to find, report, and fix defects in the
  software project?

  - Finding Defects:

    In order to find the defects in a software project,
    first check the error
    messages in the terminal window. Secondly, if there still are
    defects, check the test
    cases and assess their correctness. Lastly,
    check Travis CI to see which
    part of the program does not pass the checks. Also check GitHub peer
    reviews since a classmate might be able to catch a mistake that
    slipped by.

  - Report:

    There are many tools that software engineers
    use to communicate and report
    any bugs, errors, or defects in the project. Each tool has a different
    purpose, and benefit for using it. GitHub
    issue trackers and pull request
    threads can be great ways to point out issues,
    review code, and suggest
    new changes. On the other hand,
    Slack work-spaces can also help in direct
    communication through group chats and channels designated to specific
    topics. All of these tools combined
    would greatly help us communicate and
    report our progress as well as issues we face.

  - Fix:

    Fixing defects is an important part of getting your
    code to work smoothly. The first step is doing
    some research to try to find a solution. This
    research can be found online or in a book. The second step is
    asking for help from a classmate, technical
    leader, or instructor. This could be very helpful
    because they may provide insight to assist in fixing the defect.
    The last step is trial and error with
    the help of test cases which can indicate whether the issue(s) have been
    solved or they are still present.

- How will your team know when it is finished with the implementation of the
  software project?

  Our team will know when it is finished with the implementation of the software
  project when the following is complete. First, our software project will not
  only compile, but it should run effectively with the desired output. Secondly,
  it should pass any requirement checks for what the program should do that are
  given at the beginning of the project. The final task the team should do to
  know they have finished the implementation of the project is by running through
  the assessment and conduct guide to ensure everything meets the requirements
  outlined in them.
