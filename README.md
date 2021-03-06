[![Create a Slack Account with us](https://img.shields.io/badge/Create_Slack_Account-The_Carpentries-071159.svg)](https://swc-slack-invite.herokuapp.com/) 
[![Slack Status](https://img.shields.io/badge/Slack_Channel-dc--ecology--openref-E01563.svg)](https://swcarpentry.slack.com/messages/C9Y0RDGPQ) 

# OpenRefine-ecology
Lesson on OpenRefine for ecology

## Maintainers

### Current Maintainers

Coming soon...

### Past Maintainers

Coming soon...

## Version

The current version has been tested with OpenRefine 3.4.1.

## Data set notes

* This data set is derived from [The Portal Project Long-term desert ecology](http://portal.weecology.org/) project data. [This data file](http://www.esapubs.org/archive/ecol/E090/118/Portal_rodents_19772002.csv) was downloaded and then modified specifically for use with OpenRefine.
    * Taxon names were put back into the file.
    * Globally Unique Identifiers (in the form of UUIDs) were added.
* These modifications were made in order to illustrate some features of Open Refine.
    - Errors were added to the taxon names (`scientificName` field), to demonstrate OpenRefine's ability to find likely mis-entered data.
    - These errors can be found using clustering algorithms on the `scientificName` column, showing the power of the algorithms to find discrepancies quickly and making it simple to fix all issues found.
    
## Contributing

We welcome all contributions to improve the lesson! Maintainers will do their best to help you if you have any questions, concerns, or experience any difficulties along the way.
We'd like to ask you to familiarize yourself with our [Contribution Guide](CONTRIBUTING.md).

Please see the current list of [issues](https://github.com/datacarpentry/OpenRefine-ecology-lesson/issues) for ideas for contributing to this repository. For making your contribution, we use the GitHub flow, which is nicely explained in the chapter [Contributing to a Project](http://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project) in Pro Git by Scott Chacon.

Look for the tag ![good_first_issue](https://img.shields.io/badge/-good%20first%20issue-gold.svg). This indicates that the mantainers will welcome a pull request fixing this issue.  
