<h1 align="center">
	<br>
	<a href="https://github.com/WolfSoftware">
		<img src="https://github.com/WolfSoftware/branding/blob/master/images/general/banners/64/black-and-white.png?raw=true" alt="Wolf Software Banner" />
	</a>
	<br>
	Contributing
	<br>
</h1>

<h4 align="center">How to contribute to a Wolf Software owned project.</h4>

<p align="center">
	<a href="https://travis-ci.com/WolfSoftware/contributing">
		<img src="https://img.shields.io/travis/com/WolfSoftware/contributing/master?style=for-the-badge&logo=travis" alt="Build Status">
	</a>
	<a href="https://github.com/WolfSoftware/contributing/releases/latest">
		<img src="https://img.shields.io/github/release/WolfSoftware/contributing?color=blue&style=for-the-badge&logo=github&label=Latest%20Release" alt="Release">
	</a>
	<a href="LICENSE.md">
		<img src="https://img.shields.io/badge/license-MIT-blue?style=for-the-badge" alt="Software License">
	</a>
</p>

<h2>Overview</h2>

If you discover issues, have ideas for improvements or new features, please report them to the issue tracker of the repository or submit a pull request for the specific project. 

Please, try to follow these guidelines when you do so.

<h3>Issue reporting</h3>

* Check that the issue has not already been reported, if it has and you can provide additional information please feel free to do so.
* Check that the issue has not already been fixed in the latest code.
* Be clear, concise and precise in your description of the problem.
* Open an issue with a descriptive title and complete all of the questions in grammatically correct, complete sentences. Add an additional information you think is relevant.
* Specify which version you are running as this will help us when we attempt to replicate the issue.
* Include any relevant code to the issue summary.

<h3>Feature requests</h3>

If you have an idea for a new feature or improvement that you would like to see, but you can't (or don't want to) make the change yourself to the code, then you can also log this by using the issue tracker.

<h3>Pull requests</h3>

* Read [how to properly contribute to open source projects on GitHub][1].
* Fork the project.
* Use a topic/feature branch to easily amend a pull request later, if necessary.
* Write [good commit messages][2].
* Use the same coding and documentation conventions as the rest of the project. If not your pull request might well be rejected.
* Commit and push until you are happy with your contribution.
* Make sure to add tests for it. This is important so we don't break it in a future version unintentionally.
* Make sure that the code passes any existing tests cleanly.
* [Squash related commits together][3].
* Open a [pull request][4] that relates to *only* one subject with a clear title and description in grammatically correct, complete sentences.

*NOTE:* We reserve the right to reject any pull requests that do not meet this requirements. We will however feedback on why pull requests were rejected.

<h3>Version Numbers</h3>

Please do not bump the version number in VERSION.txt as there could well be other changes that are in progress or planned for release and your change might be in a later version.

For this reason any PRs with a change to the VERSION.txt file will be rejected as a matter of course.

<h3>Changelogs</h3>

We use [caretaker](https://github.com/DevelopersToolbox/caretaker) to auto-generate all of our changelogs, so there is no need to update the CHANGELOG, in fact any changes will be automatically overwritten.

[1]: http://gun.io/blog/how-to-github-fork-branch-and-pull-request
[2]: http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html
[3]: http://gitready.com/advanced/2009/02/10/squashing-commits-with-rebase.html
[4]: https://help.github.com/articles/about-pull-requests/
