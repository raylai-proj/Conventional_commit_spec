# Conventional_commit_spec
This is a collection of documentary of conventional commit specification for quick commit usage and suggested commit tools for python.<br >
The specification refer to below documents:<br >
1. conventional commits: https://www.conventionalcommits.org/en/v1.0.0-beta.3/<br >
2. the Angular convention: https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#-commit-message-guidelines<br >
3. RFC 2119: https://www.ietf.org/rfc/rfc2119.txt<br >
4. docs(Conventional Commits): Feat, Fix, Refactor… which is which?: https://medium.com/@noriller/docs-conventional-commits-feat-fix-refactor-which-is-which-531614fcb65a<br >
5. Developer Blog Series: What Is A Breaking Change?: https://community.blackbaud.com/blogs/69/3219 <br >
6. LinkedIn API Breaking Change Policy: https://learn.microsoft.com/en-us/linkedin/shared/breaking-change-policy<br >

The conventional commits specification provides a set of rules for people to create explicit commit history to help commits readability.<br >
Commit messages have header, body, footer, and should no longer than 100 characters<br >
It is structured as belows:<br >

&lt;type&gt; [optional scope]: &lt;description&gt;<br >
&lt;blank line&gt;<br >
[optional body]<br >
&lt;blank line&gt;<br >
[optional footer]<br >

__&lt;type&gt;__ and __&lt;description&gt;__ are mandatory<br >

## type<br >
__&lt;type&gt;__ can be one of the following:<br >
1. feat: add / remove a feature (the test may broke or not covered)<br >
2. fix: fix a bug<br >
3. docs: adding document, such as comment<br >
4. style: change the white space, code formatting, or sign missing (such as colon, single quotation marks, double quotation marks)<br >
5. perf: change the code to improve performance<br >
6. test: add a test or change current test code<br >
7. refactor: change the code, but no test broke and no line lost coverage (regular code refactoring for structure maintenance)<br >
8. ci: changes related to Continuous Integration (usually in changing configuration files, such as .yml)<br >
9. build: changes related to build of a project or it's dependency<br >
10. chore: other actions are not included from above type (no change on source, test, build, or docs)<br >

## Note<br >
1. BREAKING CHANGE: BREAKING CHANGE in body or footer means breaking API change, such as change API endpoint, change return data type, change return value, which can be vary based on company policy.<br >

## Examples<br >




