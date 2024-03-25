# Good practices for writing commits in Git

## Brevity and Clarity
When commit messages are short and clear, it's easier for collaborators to review the change history and understand what changes were made in each commit. This is especially useful when searching for a specific modification or when you need to understand the context of a specific change.

Commit messages act as a form of communication between team members. By keeping them short and to the point, it is easier to transmit information about the changes made, which helps keep all collaborators informed about the progress of the project.

## Descriptive Message
A descriptive message should clearly explain what changes were made to the code. This may include adding new features, fixing bugs, improving performance, updating documentation, among others. The more information you provide in the message, the easier it will be for other developers to understand the changes without having to review the changed code in detail.

In addition to describing specific changes, a descriptive message should also provide context about why those changes were made. This may include explanations of issues that were being addressed, customer requirements, or any other reason that led to the changes being implemented. Providing this context helps other developers understand the reason behind the changes and makes it easier to collaborate on the project.

## Use the Imperative
The use of the imperative provides a clear and consistent structure for commit messages. Starting each message with an imperative verb helps collaborators quickly understand what action is being taken on the commit.

Imperative messages are action-oriented, making them more direct and concise. This helps to effectively convey what changes are being made to the code and what impact they will have on the project.

By using the imperative, you emphasize the action being taken in the commit, making it easier to understand the changes introduced. This is especially useful when you need to revert a specific commit, since the imperative message clearly indicates which action is being undone.

## Separate Logical Tasks
By breaking changes into separate commits, each commit focuses on a specific logical task. This makes it easier for team members to review and understand the changes made in each commit without being overwhelmed by a large number of modifications in a single commit.

When each commit focuses on a single logical task, reviewers can provide feedback specific to that particular task. This facilitates communication between collaborators and helps ensure that changes are made accurately and effectively.

## Avoid Mass Confirmations
When many modifications are made in a single commit, it can be difficult for reviewers to understand what changes have been made and why. By avoiding bulk commits and breaking changes into smaller, specific commits, review of changes is made easier, improving the quality and efficiency of the code review process.

If a problem occurs in your code and a specific change needs to be reverted, it is much easier to identify and revert an individual commit rather than having to undo a large set of changes made in a single massive commit. This improves change history traceability and makes it easier to manage project versions over time.

## Review the changes
By thoroughly reviewing your changes, you can detect and correct any errors or problems before they are added to the repository's change history. This helps prevent bugs from being introduced into the code base and maintain project stability.

Reviewing changes ensures that all modifications necessary to complete a task or feature are included in the commit. This helps prevent important files or changes from being forgotten that could affect the operation of the software.

By reviewing the changes, you can verify that the added code is consistent with the project's coding standards, including coding style, naming conventions, and programming best practices. This promotes consistency and code quality throughout the project.

## Include Relevant Details
Relevant details, such as issue numbers or references to documentation, help provide context about changes made to the code. This makes it easier for collaborators to understand why certain changes were made and what their impact is on the project.

By including references to issue numbers or links to documentation in commit messages, you make it easier to find and cross-reference specific changes in the repository history. This is especially useful when you need to search for information related to a specific problem or task in the future.

Including relevant details in commit messages improves traceability of project development. This allows changes made in response to specific issues or user requirements to be easily tracked, making it easier to audit and track project progress over time.

## Avoid Committing Temporary or Unwanted Files
Temporary, build, or unwanted files can quickly accumulate in the repository if they are included in commits. This can make the repository difficult to navigate and manage as it grows in size.

Including temporary or unwanted files in the repository's change history can contaminate the history and make it difficult to review relevant changes. This can make it more difficult to identify and understand significant changes made to the project.

Temporary or build files are often unnecessarily large and can increase the size of the Git repository. Avoiding the inclusion of these files helps maintain a smaller, more efficient repository, making it easier to clone and manage.

## Keep History Clean
Break changes into smaller, coherent commits that represent a single complete and meaningful unit of work. This makes it easier to review, roll back, and understand changes made to the code.

Avoid making commits that do not add value to the repository's change history. This includes empty, debug, or test commits that do not contribute to the development of the project.

Use descriptive and meaningful commit messages that provide context about the changes made. This makes it easier for other team members to understand and review changes.

## Use Temporary Branches
When working on new functionality or fixing an issue, it is advisable to do so in a temporary branch separate from the main repository history. This ensures that changes in development are isolated and do not affect code in production until they are ready to be merged.

By developing on temporary branches, you avoid contaminating the main history with in-progress or incomplete commits. This helps keep the main history clean and organized, making it easier to review and understand changes made to the project.

Using temporary branches facilitates collaboration between team members by allowing multiple developers to work on different features or issues simultaneously without interfering with each other. Each developer can work independently on their own temporary branch and then merge changes back to the main history when they're ready.
