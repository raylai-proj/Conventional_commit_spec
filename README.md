# Conventional_commit_spec
This is a collection of documentary of conventional commit specification for quick commit usage and suggested commit tools for python.<br >
The specification refer to below documents:<br >
1. conventional commits: https://www.conventionalcommits.org/en/v1.0.0-beta.3/<br >
2. the Angular convention: https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#-commit-message-guidelines<br >
3. RFC 2119: https://www.ietf.org/rfc/rfc2119.txt<br >
4. docs(Conventional Commits): Feat, Fix, Refactor… which is which?: https://medium.com/@noriller/docs-conventional-commits-feat-fix-refactor-which-is-which-531614fcb65a<br >

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
1. feat: add / remove a feature<br >
2. fix: fix a bug<br >
3. docs: adding document, such as comment<br >
4. style: change the white space, code formatting, or sign missing (such as colon, single quotation marks, double quotation marks)<br >
5. perf: change the code to improve performance<br >
6. test: add a test or change current tests<br >
7. refactor: regular code refactoring for structure maintenance<br >
8. ci: changes related to continuous integration (usually in changing configuration files, such as .yml)<br >
9. build: changes related to build of a project or it's dependency<br >
