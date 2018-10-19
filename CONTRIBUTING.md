## Submitting issues

If you have questions about how to install or use the project files please send us an email at contrubiting.in.journalism@amg.fr

### Short version

 * The [**issue template can be found here**][template] but be aware of the different repositories! See list below. Please always use the issue template when reporting issues.

### Guidelines
* Please search the existing issues first, it's likely that your issue was already reported or even fixed.
  - Go to one of the repositories, click "issues" and type any word in the top search/command bar.
  - You can also filter by appending e. g. "state:open" to the search string.
  - More info on [search syntax within github](https://help.github.com/articles/searching-issues)
* This repository is *only* for issues within the Nextcloud Server code. This also includes the apps: files, encryption, external storage, sharing, deleted files, versions of the website.
* __SECURITY__: Report any potential security bug to us via security@amg.fr .
* The issues in other components should be reported in their respective repositories: You will find them in our [GitHub Organization](https://github.com/IW4-GROUPE-AMG/)

* Report the issue using our [template][template], it includes all the information we need to track down the issue.

Help us to maximize the effort we can spend fixing issues and adding new features, by not reporting duplicate issues.

[template]: ./ISSUE_TEMPLATE.md

## Contributing to Source Code

Thanks for wanting to contribute source code to AMG That's great!

Please read the Developer Manuals o learn how to create your first application or how to test the code with PHPCSFIXER.

### Tests

In order to constantly increase the quality of our software we can no longer accept pull request which submit un-tested code.
It is a must have that changed and added code segments are unit tested.
In some areas unit testing is hard (aka almost impossible) as of today - in these areas refactoring WHILE fixing a bug is encouraged to enable unit testing.



### Apply a license

In case you are not sure how to add or update the license header correctly please have a look at LICENSE.md