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

- How will your team elicit, analyze, and document the requirements for the
  software project?

- What will your team do if it determines that it cannot feasibly implement
  promised features?

- What is your team's software development and testing process for creating
  new features?

  - Utilize the Issue Tracker

      When developing a new feature the first step is to create an issue in the
      GitHub Issue Tracker. This issue should outline the purpose of this new
      feature and the steps needed for feature development. If this feature solves
      any current issues open in the Issue Tracker, connect the issue numbers. Then
      assign the members of your development team and request feedback from team
      members, Technical Leaders,and the course instructor.

  - Create a Branch

      The next step is to create a branch off of master with the following naming
      convention: feature/description-of-the-feature. All the work for the new
      feature should be completed and committed in this branch and ensure that all
      commit messages follow the outlined conventions from the GitHub guidelines.

  - Write Test Cases

      Once you feel that your feature is complete, you can begin to test your
      feature by writing test cases. Test cases should be written in the fashion
      appropriate for which programming language is being used, in the instance of
      this course,you should use pytest.To ensure clarity, use descriptive names
      for your tests.Make changes where necessary depending on the accuracy of
      your tests.

  - Open a Pull Request and Merge

      After testing the feature,and gaining confidence in code correctness, open a
      PR in GitHub. Request the review of team members, Technical Leaders, and the
      course instructor, making changes where necessary until the new feature is
      ready to merge.

- What process will the team follow to find, report, and fix defects in the
  software project?

- How will your team know when it is finished with the implementation of the
  software project?
