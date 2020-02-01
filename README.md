# Managing Updates

## Description

In this lesson you will learn about why updates are important and how to manage them in WordPress.

## Objectives

After completing this lesson, participants will be able to:

*   Identify any updates that are available for your sites' themes, plugins, and core files.
*   Install available WordPress core, theme, and plugin updates.

## Target Audience

Who is this lesson intended for? What interests/skills would they bring? Choose all that apply.

* [x] Users
* [ ] Designers
* [x] Developers
* [ ] Speakers
* [ ] All

## Experience Level

How much experience would a participant need to get the most from this lesson?

* [x] Beginner
* [x] Intermediate
* [ ] Advanced
* [ ] Any

## Type of Instruction

Which strategies will be used for this lesson plan? Choose all that apply.

* [x] Demonstration
* [ ] Discussion
* [ ] Exercises
* [ ] Feedback
* [ ] Lecture (Presentation)
* [ ] Show & Tell
* [x] Tutorial

## Time Estimate (Duration)

How long will it take to teach this lesson (in minutes)?

60 minutes

## Prerequisite Skills

Participants will get the most from this lesson if they have familiarity with:

*   Basic knowledge of [installing and activating WordPress themes](https://make.wordpress.org/training/handbook/user-lessons/choosing-and-installing-a-theme/) and [plugins](https://make.wordpress.org/training/handbook/user-lessons/choosing-and-installing-plugins/)
*   Knowledge of how to back up [a WordPress database and files](https://make.wordpress.org/training/handbook/user-lessons/backing-up-your-wordpress-site/)

## Readiness Questions

*   Are you familiar with installing and activating themes and plugins via the WordPress dashboard?

## Materials Needed

*   A local install running [WordPress version 4.3](https://wordpress.org/download/release-archive/)
*   [Slides](https://rawgit.com/wptrainingteam/repo-name/dev/slides/index.html) (included in this repo)

## Notes for the Instructor

*   It is ideal to pair this lesson with the Backing up Your WordPress Site lesson plan so that students learn how to back up their WordPress site before running updates.
*   This lesson uses WordPress version 4.3 on a local installation for demonstration purposes. Older versions of WordPress should never be used on production websites.

## Have You Thought About...?

* Challenge 1
* Challenge 2

> What could present challenges to delivering this lesson? Is there anything that can be done in advance to prepare for those challenges?
>
> _For example:_
>
> *  What if there’s no internet available?
> *  What if there’s no projector available?
> *  What if a participant doesn’t has a WordPress site to work with?
> *  What if there aren’t enough computers for everyone?
> *  What if no one has the prerequisite skills? What if there are different opinions about the topic?

## Lesson Overview

* First do this
* Then move on to this
* Finish with this

> The plan for the lesson. Outline form works well.
>
> _For example:_
>
> * Talk about what a theme is
> * Demonstrate how to install and activate a theme
> * Practice exercises to have participants find and install a theme on their own site

## Exercises

*   Using a local install of WordPress that is based off of a non-current version of WordPress, have students update the plugin, theme, and core files for their installation.

## Assessment

**Which of these components do NOT require updates:**

1.  Core
2.  Themes
3.  Plugins
4.  Media

**Answer:** 4\. Media

**_______ include new WordPress features**

1.  Major releases
2.  Minor releases

**Answer:** 1\. Major releases

**______ include maintenance releases, security fixes, and updates to translation files**

1.  Major releases
2.  Minor releases

**Answer:** 1\. Minor releases

**By default, every site has automatic updates enabled for minor core releases and translation files.**

1.  True
2.  False

**Answer:** 1\. True

**Where can you look to determine if WordPress core has updates available?**

1.  At the top of the administration dashboard
2.  Dashboard > Updates

**Answer:** 1\. At the top of the administration dashboard and 2\. Dashboard > Updates

**Where can you look to see what updating a plugin should fix?**

1.  changelog
2.  themes
3.  reviews
4.  help

**Answer:** 1\. changelog

**Automatic plugin background updates only happen by default for plugins and themes in special cases**

1.  True
2.  False

**Answer:** 1\. True

**When you run a theme update, you are actually overwriting the theme files.**

1.  True
2.  False

**Answer:** 1\. True

**Before you run any updates, it’s a good idea to back up your website.**

1.  True
2.  False

**Answer:** 1\. True

## Additional Resources

*  [Updating WordPress](https://codex.wordpress.org/Updating_WordPress) @ Codex
*  [Easy Theme and Plugin Upgrades](https://wordpress.org/plugins/easy-theme-and-plugin-upgrades/)
*  [Configuring Automatic Background Updates](https://codex.wordpress.org/Configuring_Automatic_Background_Updates)  @ Codex
*  [Upgrading WordPress - Extended Instructions](https://codex.wordpress.org/Upgrading_WordPress_-_Extended_Instructions) @ Codex
*  [Dashboard Updates Screen](https://codex.wordpress.org/Dashboard_Updates_Screen) @ Codex

## Example Lesson

### What Updates Are and Why We Need Them

Today we are going to learn how to identify when updates are available for WordPress sites and how to run those updates. But first, what are updates? And why do we need them? Updates to any software are released for three reasons: to fix security vulnerabilities, to fix bugs that have been discovered in the code, and to add new features. So, when we say that "WordPress core" has an update, we mean that new code has been released to replace some old code so that security issues are patched, bugs are fixed, and new features are available to users. Sometimes people procrastinate on updating their sites, but this is a very risky approach to maintaining a site. We need to consistently install the updates that are available for our sites because all sites need security patches so that they are not vulnerable to known hacks. Additionally, all sites benefit from bug fixes because then they are running off a more stable code base. It is arguable that sites can get by for some time without introducing new features to the underlying software, but new features are introduced in WordPress with the intent of making the experience of administering one's site easier for the user. If the thought of updating your site resulting in changes to the interface that you see is scary, that is OK! There is always a tutorial on new features to show you where things are after updating. For all of these reasons, you should always update WordPress to the latest version. There are three components of your WordPress site that may require updates:

*   WordPress core
*   themes
*   plugins

Each update to WordPress core, plugins, and theme files often includes bug fixes and security fixes. Major updates to WordPress core and some updates to plugins and themes include feature enhancements that can be really helpful to you in administering your website. By holding off on updating, you may be missing out on bug fixes and feature enhancements that will make managing your site easier and on security fixes that will protect your website from being vulnerable to being hacked or targeted by malicious code.

### Core Updates

There are two types of updates to the WordPress core software that become available for your website:

1.  **Major core updates** that include new WordPress features. You can tell an update is considered a "major" release because the number will follow the pattern: 4.0, 4.1, 4.2, 4.3, 4.4, etc.
2.  **Minor core updates** often include maintenance releases, security fixes, and updates to translation files. You can tell an update is considered a "minor" release because the number identifying it will be appended to the number for the current major release. For example: 4.4.1, 4.4.2, 4.4.3, etc.

By default, every site has automatic updates enabled for minor core releases and translation files. It is possible to disable these automatic updates, but automatic updates for minor core releases are one of the best ways to guarantee your site stays up to date and secure moving forward. For that reason, disabling automatic updates is strongly discouraged. Even when automatic updates are enabled you still need to manually trigger major release updates. You will be able to tell that there are core updates available for your site in a few key places throughout the site. First, there will be a banner at the top of the every administration page to alert you to the update: [![dashboard with core update available](https://make.wordpress.org/training/files/2014/12/Screen-Shot-2016-02-23-at-7.36.00-AM-1024x387.png)](https://make.wordpress.org/training/files/2014/12/Screen-Shot-2016-02-23-at-7.36.00-AM.png)Second, on the "Updates" page within the WordPress admin (yourwebsite.com/wp-admin/update-core.php) there is a section that will tell you whether WordPress core is up to date or not: [![updates available](https://make.wordpress.org/training/files/2014/12/Screen-Shot-2016-02-23-at-7.38.54-AM.png)](https://make.wordpress.org/training/files/2014/12/Screen-Shot-2016-02-23-at-7.38.54-AM.png) [tip]To get an idea what was changed in a particular version, you may check out [Releases Category Archive](https://wordpress.org/news/category/releases/)[/tip]

### Plugin Updates

Plugin updates do not follow a consistent naming convention that will help us in determining whether the update contains security updates, bug fixes, new features, or some combination of the three. Instead, there are other resources to help ensure that the updates we make to plugins are safe for our sites. Plugins are administered from the "Plugins" screen in the administration screens of your WordPress site. You can go there by clicking on the "Plugins" button in the left side navigation or by navigating to yourwebsite.com/wp-admin/plugins.php. Once on this page, you'll see a list of all of the plugins that are installed on your website, whether they are activated or not. [![plugin admin screen](https://make.wordpress.org/training/files/2014/12/Screen-Shot-2016-02-23-at-7.53.08-AM.png)](https://make.wordpress.org/training/files/2014/12/Screen-Shot-2016-02-23-at-7.53.08-AM.png)Each plugin has a description of what the plugin does, a version number, an author, and a website to refer to. If updates are available for the plugin, there is an alert below the standard plugin information that says "There is a new version of [plugin name] available. View version [number] details or update now." You can click on the "Update Available" link to view only the plugins that have updates available. In this instance, the only plugin that has updates available is Akismet. When looking at the plugin listing information for Akismet, we can see that the website we're looking at has version 3.1.3 of the plugin installed and that a new version is available. [![Akismet update](https://make.wordpress.org/training/files/2014/12/Screen-Shot-2016-02-23-at-7.47.09-AM.png)](https://make.wordpress.org/training/files/2014/12/Screen-Shot-2016-02-23-at-7.47.09-AM.png)Before we run updates for a plugin, it's best practice to make sure that the plugin won't have compatibility issues with the version of WordPress the site is running or with other plugins that we have running on our site. To see what has changed in a new version of a plugin, you can click on the "view version [number] details" link to view the release notes for the new version. In the changelog we can learn lots of information about how the new version of a plugin is different from the version we have installed. For example, by reading the changelog we may learn that a plugin added some documentation, made  an accessibility fix for screen-readers and keyboard navigation, or resolved a compatibility issue with a new version of WordPress. [![release notes for Akismet](https://make.wordpress.org/training/files/2014/12/Screen-Shot-2016-02-23-at-8.02.26-AM.png)](https://make.wordpress.org/training/files/2014/12/Screen-Shot-2016-02-23-at-8.02.26-AM.png) Unlike WordPress core, automatic background updates only happen by default for plugins and themes in special cases, as determined by the WordPress.org API response, which is controlled by the WordPress security team for patching critical vulnerabilities. This means that most of the time you will need to manually trigger updates for the plugins on your site. In addition to managing plugin updates through the "Plugins" administration panel, the "Updates" page within the WordPress admin (yourwebsite.com/wp-admin/update-core.php) also includes a section that will tell you which plugins have updates available: [![updates screen available plugin updates list](https://make.wordpress.org/training/files/2014/12/Screen-Shot-2016-02-23-at-8.14.23-AM.png)](https://make.wordpress.org/training/files/2014/12/Screen-Shot-2016-02-23-at-8.14.23-AM.png)

### Theme Updates

As with WordPress core and plugins, themes that are bundled with core, that you have installed from the [WordPress Theme Directory](https://wordpress.org/themes/), or that you have installed from a third party source will require occasional updates. You can see the available theme updates from the "Themes" section on the "Updates" page within the WordPress admin (yourwebsite.com/wp-admin/update-core.php): [![available theme updates list](https://make.wordpress.org/training/files/2014/12/Screen-Shot-2016-02-23-at-8.21.22-AM.png)](https://make.wordpress.org/training/files/2014/12/Screen-Shot-2016-02-23-at-8.21.22-AM.png)When you run a theme update, you are actually overwriting the theme files. If you made any changes to these files when setting up your site you will lose the changes when you update. Since losing the changes that make a website look a certain way is frustrating and sad, WordPress provides an easy way to avoid this headache by encouraging the use of "child themes" that inherit all of the characteristics of the "parent theme", but do not lose any customizations when the parent is updated.

### Back Up Your Site Before You Update

Before you run any updates, it is a good idea to back up your website because sometimes updates do not go as planned and may break part of your website. If you have a backup, you can restore your website to it's previous state if there are any issues when upgrading. Complete instructions to make a backup can be found in the [WordPress Backups](https://codex.wordpress.org/WordPress_Backups "WordPress Backups") section of the Codex.

### How to Run the Updates

There are two methods for updating - the easiest is the one-click update, which will work for most people. If the one-click update doesn't work or if you just prefer to be more hands-on you can follow the manual update process that is [documented in the Codex](https://codex.wordpress.org/Updating_WordPress#Manual_Update). Modern versions of WordPress (version 2.7 and up) let you update with the click of a button. For WordPress core, you can run an update by clicking the link in the new version banner (if it's there) or by clicking the "Update Now" button in the WordPress core section of the "Updates" screen. You shouldn't need to do anything else other than let the updates run. Once it's finished, your WordPress software will be up-to-date. For both plugins and themes, you will need to select the check-boxes for each plugin or theme you would like to update and then click the "Update Plugins" or "Update Themes" button to run the updates. One-click updates work on most servers. If you run into any issues with one-click updates they are probably related to server level permissions issues.

### Lesson Wrap Up

![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/lightbulb.png) Follow with the Exercises and Assessment outlined above.
