Q1: Is the keyword "fixes" the only way to auto-close an issue from a PR (pull request). Is there other keywords that can accomplish the same thing?

A1: No, there are a series of other keywords see https://help.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword

Q2: Do you have to create a new PR EVERYTIME you want to close an issue,
or is it possible to close multiple issues within a single PR? If so, 
how?

A2: A single PR could close multiple issues. In the PR comment, refer to multiple issues using #issuenumber

Q3: Provide an example of using map that is different from the one I have done.
Your example must use map both as a named function declaration and with an
anonymous function. 

Within comments, explain exactly what map is doing. Finally, why is the
"transformation function" we discussed in class sometimes referred to 
as a callback function. 

A3: 
A map could also be used in printing options from a dictionary, to assit input decision from the user.

<!-- create object -->
var array1 = {'a': 1, 'b': 2, 'c':3}
<!-- map return value pair -->
obj.keys(array1).map(function(key, value) {
    console.log(key, value)
}

Transformation function is called callback function as they can be passed into another function and be called up later in a right order