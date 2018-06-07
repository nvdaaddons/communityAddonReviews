# NVDA Add-ons Review Center #

Welcome to the NVDA Community Add-ons Review Center.

The purpose of this NVDA Add-ons Review Center is to provide a tracker for performing NVDA add-on reviews, including allowing reviewers to set review milestones, give technical comments on deep reviews, and giving authors another venue for requesting reviews. This forum allows reviewers to keep track of review status and assign reviews to reviewers through existing methods. As such, this repository only consists of issues, and does not accept pull requests unless they are related to issue template or policy changes.

A collection of community add-ons can be found at https://addons.nvda-project.org. As such, addons can be submitted for review here. If the basic review passes, addons are put on this website for the NVDA community to enjoy.

## Add-on review process

The NVDA add-ons community welcomes add-on submissions from authors. Please follow the below procedure to submit a new add-on for review so it can be listed on the official add-ons website:

1. If you haven't already, sign up for GitHub.
2. Go to https://github.com/nvdaaddons/reviews/issues/new.
3. Fill out the add-on review template, including the following:
    * Name of  add-on, which is a human readable name suitable for the link as listed on the addons site, not the internal name as used by NVDA. We recommend using the addon summary.
    * a short description of your add-on. We will include this as the contents of your addon on our site.
    * name(s) of add-on author(s) and optional emails for authors.
    * repository (if you have one). Note that this does not need to be git.
    * version (optional)
    * request for additional reviews (see below for a description of our review process).
    * statement of compliance with GPL. (This is required because NVDA is lisenced under the GPL, and your addon is running as code which is part of NVDA's process). There are some special exceptions. Please see the NVDA license for more details, especially the part labeled "Non-GPL Components in Plugins and Drivers".
4. Your add-on review request will be commented on by  reviewers. If you would like community feedback on your addon, please [join the NVDA-addons list](https://nvda-addons.groups.io/).
5. Once the review is finished, an add-on reviewer will approve the add-on, suggest changes, or write a reason why the add-on wasn't accepted at this time.
6. After this, the reviewer will upload your addon to the addons website. This may take about 24 hours, as we are still dealing with a website designed when NVDA had far fewer resources and have not gotten around to rewriting our website to use modern technologies. If we need more information, we will ask you for it here. This will include download links for the addon, and information on whether you would like your addon listed as a beta version first.

Note: You're more than welcome to reopen the add-on review issue if you want a fresh new review.

## Review levels

All add-ons are required to go through a basic review, which checks the following:

1. License and copyright.
2. Basic User experience (tested by at least one tester).
3. Documentation and messages. (Do we want to remove this? I'm pretty sure we decided that addons don't need docs on IRC with Jamie once).
4. Security (Does the addon do anything dangerous, or maliscious). Note that security concerns which did not have malicious intent may still block review if we deem them severe.

Add-on authors may request one or more of the below deep reviews once the add-on has been approved :

* Coding style: this review is ideal for add-ons that the community believes should become part of the NVDA screen reader in the future. This is because the core code in NVDA is held to a high standard, and your core contribution will be subjected to harsh constructive criticism to ensure quality.
* Python 3 compatibility: this is best for add-ons that   will be useful  for a long time (past 2020).
* GUI: for add-ons that present dialogs and windows. This review looks at control spacing, window placement and other graphical elements. Note: Review availability is subject to availability of non-blind contributors.
* Translation: a user who speaks another language will be asked to review add-on messages in hopes of helping you make your messages easier to understand and translate. We will also comment on how to utilize NVDA's translation system.
* NVDA feature compatibility: for add-ons that may extend NVDA features or add features from newer releases to older NVDA versions.
