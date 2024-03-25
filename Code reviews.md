# Code reviews 

## Rules

- Restrict each code review session to less than 400 lines of code. This limit is imposed to maintain focus, effectiveness, and efficiency during the review process. 
</br>
> By limiting the number of lines reviewed in each session, reviewers can maintain better focus and attention to detail, ensuring thorough scrutiny of the code change.
</br>
> Emphasize the importance of quality over quantity in code reviews. Rather than trying to review a large volume of code at once, prioritize a meticulous examination of a smaller portion to identify potential issues and provide meaningful feedback.
</br>
> Breaking down code reviews into smaller sessions enhances efficiency by preventing fatigue and cognitive overload among reviewers. This approach encourages more effective collaboration and communication between reviewers and developers.
</br>
> Encourage an iterative review process where code changes are incrementally reviewed in manageable chunks. This allows for timely feedback, corrections, and improvements, ultimately leading to a higher quality codebase.
</br>
> A code review session have to be shorter than 60 minutes.
- Ensure that the codebase includes adequate documentation in the form of comments. Comments serve as valuable supplementary information that enhances code readability and understanding.
</br>
> Evaluate the clarity and comprehensiveness of the comments to ensure they effectively communicate the purpose, functionality, and intent of the code to other developers.
</br>
> Verify that comments are used to explain the underlying logic, algorithms, or complex operations in the code. Comments should provide insights into why certain decisions were made and how specific portions of the code function.
</br>
> Check if the comments include documentation for public APIs, functions, methods, or classes, explaining their usage, parameters, return values, and potential side effects.
</br>
> Encourage adherence to consistent commenting conventions and style guidelines throughout the codebase. Consistency in formatting and language helps maintain readability and coherence.
</br>
> Emphasize the importance of keeping comments up-to-date with code changes. Ensure that developers review and update comments when modifying relevant code to prevent inconsistencies or misleading documentation.
- Check for test quality.
> Ensure that at least 70% of the codebase is covered by tests. This metric, known as test coverage, helps gauge how much of the code is exercised by tests.
</br>
> Verify that the tests themselves do not produce errors. Tests should be reliable and error-free to effectively validate the functionality of the code.
</br>
> Check if the tests align with the functionality being implemented or modified. Ensure that each test case corresponds to a specific feature or behavior of the code.
</br>
> Validate that error cases are thoroughly tested to handle unexpected inputs or edge cases. This ensures robustness and stability in the face of unforeseen circumstances.
- Check for the linter, it has to be no errors of coding style.