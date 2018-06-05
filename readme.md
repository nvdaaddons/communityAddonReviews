# NVDA Add-ons Review Center #

Welcome to NvDA Community Add-ons Review Center.

The purpose of NVDA Add-ons Review Center is to provide a tracker for add-on reviews, including milestones, technical comments, and giving authors another venue for requesting reviews. As such, this repository only consists of issues, and does not accept pull requests unless it is related to issue template or policy changes.

A collection of community add-ons can be found at https://addons.nvda-project.org.

## Add-on review process

The NVDA add-ons community welcomes add-on submissions from authors. Please follow the below procedure to submit a new add-on for review so it can be listed on add-ons website:

1. If you haven't already, sign up for GitHub.
2. Go to https://github.com/nvdaaddons/reviews/issues/new.
3. Fill out the add-on review template, including name of the add-on, a short description, name(s) of add-on author(s), repository (if you have one), version (optional), and request for additinoal reviews not covered by basic review below (the add-on must pass basic review first before deeper reviews can be performed).
4. Your add-on review request will be commented on by the community and reviewers.
5. Once the review is finished, an add-on reviewer will approve the add-on, suggest changes, or write a reason why the add-on wasn't accepted at this time.
6. You're more than welcome to reopen the add-on review issue if you want a fresh new review.

## Review levels

All add-ons go through basic review that checks the following:

1. License and copyright.
2. User experience (tested by at least one tester).
3. Documentation and messages.
4. Security (possible concerns about security).

Add-on authors may request one or more of the below deeper reviews once the add-on has been approved (passes basic review):

* Coding style: this review is ideal for add-ons that the community believes should become part of NVDA screen reader in the future.
* Python 3 compatibility: this is best for add-ons that are planned to be used for a long time (past 2020).
* GUI: for add-ons that present dialogs and windows. This review looks at control spacing, window placement and other graphical elements.
* Translations: a user who speaks another language will be asked to review add-on messages in hopes of helping you make your messages easier to understand and translate.
* advanced security: ideal for add-ons that perform tasks such as file system manipulation, accessing the web and so on.
* NVDA feature compatibility: for add-ons that may extend NVDA features or add features from newer releases to older NVDA versions.
* Bug hunting: this is ideal for add-ons requiring high reliability. One or more NvDA add-on experts will probe add-on source code and user experience to uncover potential bugs.
* Additional deeper reviews once resources become available.
