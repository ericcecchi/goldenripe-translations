---
layout: default
title: Goldenripe Translations
subtitle: Clearly Communicating Scripture—in Your Language
---

## Hey, translators. Thanks for helping us out.

So you want to help bring The Way to more people, in more languages, and in more countries? Great! Here's how you can get started now.

To help us keep track of things, there are just a few steps you need to follow in order to translate, correct, or add to the content in The Way. We use a service called Github to keep track of and review changes to The Way. It's easy for anyone to sign up and contribute.

If you're not a computer engineer or software developer, you've probably never heard of Git or Github. That's ok. It's a pretty complex and powerful tool, but it's really the best there is when it comes to keeping track of content coming from several different contributors. The goal of this guide is to make contributing to The Way as simple as possible for everyone.

# How to contribute

## Sign up

The first thing you need to do is head over to [Github.com](http://github.com) and sign up for an account. It's free and takes only a couple seconds.

## Get a copy of The Way

The easiest way to get a copy of the text content of The Way is to [click here](https://github.com/ericcecchi/goldenripe-translations) and then click the Fork button in the upper right side of the page.

The Way lives in what Git calls a "repository." Repositories are simply a collection of files and folders. A repository is named by the Github user that created it, like so: "user-name/repository-name". In the [ericcecchi/goldenripe-translations](https://github.com/ericcecchi/goldenripe-translations) repository, all the text content for The Way is contained in a folder for each language. For example, the English version lives in the "en" folder. You can tell what repository you are in by looking at the top left part of the page:

![A repository](/images/repository.png)

By clicking the Fork button, you now have an exact copy of the source content of The Way under your Github account. It lives at  your-username/goldenripe-translations. We call this your Fork. The original repository remains intact. We call that the Base.

## Make some changes

You can make changes only to your Fork, not the Base repository. You can get to your Fork by clicking on your username in the upper right corner of any page on Github.com. You should then see your Fork listed under the Repositories tab:

![Your Fork](/images/fork.png)

Click on goldenripe-translations, and then navigate to the language folder you want to edit. If I click on "en" for English, I get a list of files for the English language sections:

![The sections](/images/sections.png)

Click on the file you want to edit, then the Edit button, and you're good to go. I would highly reccommend changing the "No wrap" setting to "Soft wrap" to make things a lot more readable.

![Edit](/images/edit.png)

## Structure

The structure of the content is extremely important for its proper display in all formats, web, print, and mobile.

At the top of each file is a note about the category and language of the content:

~~~
<!---  
The Way
Questions
English  
-->
~~~

There's no need to edit this. It's there for informational and technical reasons.

The structure of the content is fairly straightforward. A single hash mark (#) followed by a single space denotes the section name. Two hash marks followed by a single space denotes a question. The answer is contained in the lines after a question and before the next question. Each paragraph in an answer is seperated by a single blank line. Here's an example of a couple questions:

~~~
# Section Name

## This is a question?

This is the first paragraph of the answer to the question. Citations should use the full name of the book followed by the chapter and verse numbers seperated by a colon, like so: "For God so loved the world that he gave only Son, that whoever believe in him should not  perish but have eternal life" (John 3:16).

This is the second paragraph. There is exactly one blank line seperating it from the first.

Here is a third, very short paragraph.

## This is another question?

Here is the first paragraph. It has two short sentances.

This is the second paragraph. And so on.

~~~

## Committing changes

After you've made some changes, you can save your progress by scrolling down below the content editor and clicking the "Commit changes" button.

![Commit](/images/commit.png)

You can optionally enter a summary (short sentance) and a longer description of the changes you made. Committing saves your changes into your Fork only, not the Base repository. It's a good practice to commit early and commit often. You don't want to accidently lose your progress.

## Submitting your changes for review

Once you've committed some changes and you're ready to submit them to the Base repository, you need to create a Pull Request. This can be done by clicking on the pull request button when you're somewhere in your Fork. You'll get a page that looks like this:

![Pull request](/images/pull.png)

First make certain that the "base repo" is ericcechi/goldenripe-translations and the "head repo" is your-username/goldenripe-translations. Then give your Pull Request a title and brief description before sending it in.

## Watch for your changes to be accepted

After submitting a Pull Request, you'll be redirected to a discussion page for your Pull Request in the Base repository:

![Discussion](/images/discussion.png)

Reviewers can discuss and accept your changes from here. They may ask you to make some more changes before they accept it, though. So pay attention to this page. You can get back to it by going to the Base repository and click on the Pull Requests tab. Your Pull Requests will also be listed on the bottom of your profile page:

![Contributions](/images/contributions.png)

## Rinse and repeat

After your pull request has been accepted, you should delete your Fork. This will allow you to start over with the latest version of The Way next time you want to make changes. To do this, click on the "Settings" tab in your Fork. Then scroll down to the Danger Zone and click the "Delete this repository" button:

![Danger](/images/danger.png)

Don't worry—there's no danger in deleting as long as you're changes have been accepted in the Base repository.

When you're ready to contribute again, start over at step 1 by forking the Base repository again.

## Breathe deep

Don't worry about making mistakes. They can easily be fixed along the way. The best thing you can do for The Way is start contributing right now, so have at it! Here at Goldenripe, we greatly appreciate your willingness to help us out. And on behalf of those whose lives will be enlightened by the truth communicated in The Way, thanks and God bless!
