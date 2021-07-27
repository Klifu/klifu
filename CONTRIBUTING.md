# Contributing to Klifu 
👍🎉 First off, thanks for taking the time to contribute! 🎉👍

The following is a set of guidelines for contributing to **Klifu** and it's packages, which are hosted in the [Klifu Organization](https://github.com/klifu) on GitHub. These are mostly guidelines, not rules. Use your best judement, and feel free to propose changes to this document in a pull request. 

## Table of Contents
- [Code of Conduct](#code-of-conduct)
- [I don't want to read this whole thing, I just have a question!!](#i-dont-want-to-read-this-whole-thing-i-just-have-a-question)
- [What should I know before I get started](#what-should-i-know-before-i-get-started)
- [How can I Contribute?](#how-can-i-contribute?)
	- [Reporting Bugs](#reporting-bugs)
	- [Suggesting Enhancements](#suggesting-enhancements)
	- [Your First Code Contributions](#your-first-code-contributions)
	- [Pull Requests](#pull-requests)
- [Additional Notes](#additional-notes)
	- [Issues and Pull Request issues](#issues-and-pull-request-issues)

---

## Code of Conduct 
This project are everyone participating in it is governed by the [Klifu Code of Conduct](https://github.com/Klifu/klifu/blob/main/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [souvikde.ns@gmail.com](mailto:souvikde.ns@gmail.com). 


## I don't want to read this whole thing, I just have a question!!
> Please don't file an issue to ask a question. You'll get faster results by using the resource below. 

We have an official message board with a detailed FAQ and where the community chimes in with helpful advice if you have any questions. 

- [Discuss, the official Klifu message board](https://github.com/Klifu/klifu/discussions)
- [Klifu FAQ](https://github.com/Klifu/klifu/discussions/categories/q-a)

If chat is more your speed, you can join the Klifu Discord. 


## What should I know before I get started

Klifu is fairly small open source project - it's made up of [3 repositories](https://github/klifu). When you initially consider contributing to klifu, you might be unsure about which of these 3 repositories implements the functionality you want to change, or report a bug for. This section should help you with that. 

As of now **klifu** is divided into 3 main repositories, 

- [@klifu/core](https://github.com/Klifu/core) -  where lives all the game logic and static data. 
- [@klifu/cli](https://github.com/klifu/cli) - the CLI client for klifu, as of now this is the only way to play klifu. 
- [@klifu/api](https://github.com/klifu/API) - klifu API which hosts all static data for the game. 


## How can I Contribute?

### Reporting Bugs
This section guides you through submitting a bug report for klifu. Following these guidelines helps maintainers and the community understand your report 📝, reproduce the behaviour 💻 💻, and find related reports 🔎.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report) as you might find out that you don't need to create one. When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report). Fill out the requried template, the information is asks for helps us resolve issue faster. 

> Note: If you find a Closed issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### Before Submitting A Bug Report 
- Check the [FAQs on the forum](https://github.com/Klifu/klifu/discussions/categories/q-a) for a list of common questions and problems. 
- Perform a [cursory search]() to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue istead of opening a new one. 

#### How do I Submit a (Good) Bug Report?
Bugs are tracked as [GitHub Issues](https://guides.github.com/features/issues/).You can only create issue in your `klifu` repository and all other repositories have thier issues blocked. 

Explain the problem and include additional details to help maintainers reproduce the problem:

- **Use a clear and descriptive title** for the issue to identify the problem.
- **Describe the exact steps which reproduce the problem** in as many details as possible. For example, start by explaining how you started Atom, e.g. which command exactly you used in the terminal, or how you started Atom otherwise. When listing steps, **don't just say what you did, but explain how you did it**. For example, if you moved the cursor to the end of a line, explain if you used the mouse, or a keyboard shortcut or an Atom command, and if so which one?
- **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
- **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
- **Explain which behavior you expected to see instead and why.**
- **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem. If you use the keyboard while following the steps, **record the GIF with the [Keybinding Resolver](https://github.com/atom/keybinding-resolver) shown**. You can use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.

### Suggesting Enhancements
This section guides you through submitting an enhancement suggestion for Klifu, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion 📝 and find related suggestions 🔎.

Before creating an enhancement suggestions, please check [this list](https://github.com/Klifu/klifu/discussions/categories/ideas) as you might find out that you dont need to create one. Before creating an issue for a feature request, please have a chat in the [discussion](https://github.com/Klifu/klifu/discussions/categories/ideas). 

### Your First Code Contribution
Unsure where to begin contributing to Klifu? You can start by looking through these `beginner` and `help-wanted` issues:

- [Beginner issues](https://github.com/Klifu/klifu/issues?q=is%3Aopen+is%3Aissue+label%3Abeginner) -  issues which should only require a few lines of code, and a test or two.
- [Help wanted issues](https://github.com/Klifu/klifu/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22) - issues which should be a bit more involved than `beginner` issues.

Both issue lists are sorted by total number of comments. While not perfect, number of comments is a reasonable proxy for impact a given change will have.

#### Local development 
All packaged of klifu can be developed locally. For instructions on how to do this see the `reademe` file of the package you are working on. 

### Pull Requests 
The process described here has several goals:
- Maintain Klifu's quality 
- Fix problems that are important to users
- Engage the community in working toward the best possible klifu. 
- Enable a sustainable system for Klifu's maintainers to review contributions

Please follow these steps to have your contribution by the maintainers:

1. Follow all instructions in the template. 
2. After you submit your pull request, verify that all the status checks are passing
	<details>

	<summary>What if the status checks are failing?</summary>

	If a status check is failing, and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe the failure is unrelated. A maintainer will re-run the status check for you. If we conclude that the failure was a false positive, then we will open an issue to track that problem with our status check suite.
	</details>

> While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

## Additional Notes

### Issues and Pull Request Labels 
This section lists the labels we use to help us track and manage issues and pull requests. Issues are only available in [klifu repo](https://github.com/klifu/klifu). 

|label name|Description|
|----------|-----------|
|`@klifu`|Issues regarding klifu repo|
|`@klifu/core`|Issues regarding core library|
|`@klifu/cli`|Issues regarding CLI client|
|`@klifu/API`|issues regarding klifu API|
|`beginner`|issues which should only require a few lines of code, and a test or two|
|`good first issue`|Good for newcomers|
|`help wanted`|Extra attention is needed|
|`bug`|Something isn't working|
|`enhancement`|New feature or request|
|`documentatio`|Improvements or additions to documentation|
|`design`|issues related to design|
|`duplicate`|This issue or pull request already exists|
|`wontfix`|This will not be worked on|
|`question`|Further information is requested|

