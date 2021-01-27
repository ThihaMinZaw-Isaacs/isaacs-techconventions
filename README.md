# isaacs-techconventions
Tech standards to be followed while coding


<h2>Conventional Commits</h2>

<h3>Commit Format</h3>

 <type> [optional scope]: <description>
[optional body]
[optional footer(s)]

<h3>Types of commits</h3>

1. feat: addition of some new features
2. add: changes to add new capability or functions
3. cut: removing the capability or functions
4. fix: a bug fix
5. bump: increasing the versions or dependency versions
6. build: changes to build system or external dependencies
7. make: change to the build process, or tooling, or infra
8. ci: changes to CI configuration files and scripts
9. doc: changes to the documentation
10. test: adding missing tests or correcting existing tests
11. chore: changes for housekeeping (avoiding this will force more meaningful message)
12. refactor: a code change that neither fixes a bug nor adds a feature
13. style: changes to the code that do not affect the meaning
14. optimize/perf: a code change that improves performance
15. revert: reverting an accidental commit

<h3> Example Commit </h3>

add: summarize the change within 50 characters

More detailed explanation goes here, as this is the body of the commit message. Mostly the first line of the body is treated as the commit message as well. A blank line or so called line-break is must between the title and the body.
The body can also have multiple paragraphs to provide the detailed
message on the context of the commit. Using irregular or punctuation
other than comma(,) and period(.) are discouraged here.

This is also the place for explaining the problem or issue this commit is solving. This body can also contain bullets as followed
- This is to make sure the intended meaning is conveyed properly.
- Bullets also saves more characters by stating the obvious.
- Either asterisk or hyphens can be used for bulletin notations.
Resolves: #555
See also: #235, #635

