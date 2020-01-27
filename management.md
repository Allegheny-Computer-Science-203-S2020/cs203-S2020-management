# Project Management Plan for Team-Based Software Engineering

## Questions to Answer for Team-Based Software Engineering

- How will you inventory the skills of team members to determine who is
  suited for specific tasks?

- How will you divide the entire team into sub-teams assigned to complete
  specific tasks?

- How will you ensure everyone has the opportunity to master all software
  engineering skills?

- How will you run the course sessions to ensure that you use them
  to maximum effectiveness?

- When and how frequently will you give demonstrations of the software that
  you are engineering?

- How will you adjust the project's schedule if the team falls behind on the
  completion of tasks?

- How and when will your team conduct blame-less postmortems to resolve
  project mistakes?

  - Creating a blame-less postmortem:

    They should be created immediately when a team member notices the
    issue. The postmortems will be discussed in a Github issue tracker with
    "blame-less postmortem" in the title. You may assign specific people to the
    issue tracker, on the basis that they are well suited to solving the problem.
    You should not assign people because you believe they created the error. New people
    can be assigned after the initial creation of the issue tracker.

  - Responding to a blame-less postmortem:

    We will take on blame-less postmortems as collective problem that is our
    responsibility to solve. These postmortems should be viewed as learning opportunities
    that will enhance our technical abilities. When discussing the details of the
    postmortem you should not directly or indirectly blame any one group or individual
    affiliated with a particular area. Everyone's concerns in the issue tracker
    should be listened to and considered when developing a fix. The point of postmortems
    is that it allows us to pool our expertise and devise a solution that solves
    and prevents future errors.

  - Closing a blame-less postmortem:

    Postmortems can only be closed if there's empirical evidence showing that the
    problem is no longer present. Additionally everyone assigned to the blame-less
    postmortem has to agree that the problem has been solved, and that the issue
    racker can be closed. The issue cannot be closed just because a build passes
    checking software such as Travis-CI.

- How will your team elicit, analyze, and document the requirements for the
  software project?

- What will your team do if it determines that it cannot feasibly implement
  promised features?

- What is your team's software development and testing process for creating
  new features?

  - Utilize the Issue Tracker

    When developing a new feature the first step is to create an issue in the
    GitHub Issue Tracker. This issue should outline the purpose of the new
    feature and the steps needed for feature development. If this feature solves
    any current issues open in the Issue Tracker, connect the issue numbers.
    Next, assign the members of your development team and request feedback
    from team members, Technical Leaders, and the course instructor.

  - Create a Branch

    The next step is to create a branch off of master with the following naming
    convention: `feature/description-of-the-feature`. All the work for the new
    feature should be completed and committed in this branch to avoid
    merge conflicts and breaking the current build.

  - Write Test Cases

    Once you feel that your feature is complete, you can begin to test your
    feature by writing test cases. Test cases should be written in the appropriate
    fashion for the programming language being used, in the instance of
    this course you should use pytest. To ensure clarity, use descriptive names
    for your tests. Make changes where necessary depending on the accuracy of
    your tests.

  - Open a Pull Request and Merge

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

- How will your team know when it is finished with the
  implementation of the software project?
