# Quire Documentation Contributor Guidelines

>**All are welcome.** As an open-source community, Quire is committed to providing a safe, welcoming, transparent, and inclusive environment for all our community members and those wishing to become involved. Please see our **[Code of Conduct](https://github.com/thegetty/quire/blob/main/CODE_OF_CONDUCT.md)** for more on the expectations and protections for our community members.

**Thank you for your interest in contributing to Quire!** 

We recommend following the process outlined below to ensure a smooth contributing experience. Our goal is to make the process as effective and transparent as possible, and to ensure that your every contribution can become part of Quire.   

1. [Learn About Contributing To Quire](#about-contributing-to-quire)
2. [Identify a Contribution to Make](#identify-a-contribution-to-make)
3. [Start Work on Contribution](#start-work-on-contribution)
4. [Submit Your Contribution](#submit-your-contribution)

## About Contributing to Quire

Developed by Getty, Quire is a new, multiformat publishing tool available for immediate access and use. Quire is in a limited beta, © J. Paul Getty Trust, and not yet released as open-source software. **For a free license to use Quire, please complete [this form](http://bit.ly/quire-signup).**

Striving toward becoming a fully open-source project by spring 2022, we encourage contributions from our community members. No matter what level of experience you have, we welcome all contributions, big and small.

There are two Quire repositories hosted on GitHub that can contribute to:

- [**quire**](https://github.com/thegetty/quire):  Core Quire code including command-line interface, default starter content, and default theme.
- [**quire-docs**](https://github.com/thegetty/quire-docs): Quire website and documentation.

You are currently in the **quire-docs** repository. The Quire website and documentation are actually built using Quire. That means contributing to this repo will give you an opportunity to work on a live Quire project. For some, the process may be familiar and for others it will be a good way to familiarize yourself with the tool. If you haven't already, please [install Quire](https://quire.getty.edu/documentation/install-uninstall/) to get started. 

>🗣**CALLING ALL FIRST-TIMERS!** — We can’t stress enough that Quire is open to contributors at all levels. Here are a few resources especially for you:
>- Find [“good first issues”](https://github.com/thegetty/quire-docs/issues) tagged in our issue tracker for the thegetty/quire-docs repo
>- Read the Quire guide to Making Your First Contribution — *in progress*
>- Learn more about contributing to open source at [First Timers Only](http://www.firsttimersonly.com/)

## Identify a Contribution to Make

Our website and docs are updated continuously for clarity and completeness but it’s not always easy to keep up with the pace of Quire’s development. We invite you to share your ideas or jump in and make edits yourself. There are several ways to contribute to the Quire website and documentation.

**Fix a Typo or Broken Link:** Sometimes little things like typos or broken links can slip through the cracks, and every small fix you make really helps.

**Copyedit Text:** As a regular user of Quire, you’ll likely find sections of the text that can be improved or clarified for other users. You’ll know best!

**Propose/Write a New Section:** Have you recently contributed a new feature to our main [Quire repository](https://github.com/thegetty/quire) and have the time to add the corresponding documentation? Have you come across a TK section (shorthand for “to come”) and would like to complete it? Do you have an idea for a new section? We’d love your help!

**Propose/Write an Article for the Website:** We’re always interested in adding articles about specific aspects of working in Quire to our Learn knowledge base. Maybe you have some tips on modifying shortcodes or styling is CSS in the custom.css.

**Translate the Documentation:** The Quire community is global and we hope to be able to continue to expand access to Quire, including to non-English speakers. If you are interested in translating our documentation or even just sections of the documentation we'd love to talk to you about it.

### Use the Issue Tracker

We use GitHub’s [issue tracker](https://github.com/thegetty/quire-docs/issues/) to track work needs to be done, that is currently being done, or that is proposed to be done.

You can use it to find an existing issue to work on, to post about a new issue that you’d propose working on, or to post about a new issue you’ve found that someone else might work on.

#### Work on an Existing Issue

If you are working on a previously posted issue, please comment on that issue and let us know you are working on it. That prevents duplicating efforts or having your changes rejected because someone else is working on it.

#### Post a New Issue

If your changes are small or straightforward then there is no need to create a new issue. Just dive in and get to work. However, if you are proposing or attempting a large/complex change please post a new issue [on our issue tracker](https://github.com/thegetty/quire-docs/issues/) before proceeding. This helps avoid changes being rejected before you've done too much work. Be sure to briefly describe your proposed solution and say whether you may need help with any aspect of it. This approach has several advantages:

- Lets people know you’re working on it
- Gives the core team and the community a chance to give feedback before you do any work
- Helps to ensure your contribution will be accepted and successfully merged in

## Start Work on Contribution

Now that you've identified your contribution, your next step will be to use GitHub and a text editor (such as Atom) to make the desired changes.

>We use GitHub to manage all our work on Quire. If you are new to GitHub, we recommend downloading [GitHub Desktop](https://desktop.github.com/). Before getting started, review the [GitHub Desktop documenation](https://docs.github.com/en/desktop) and the [Project Management with GitHub](https://quire.getty.edu/documentation/github/) section of the Quire documentation. An abbreviated explantion of how to submit changes via GitHub included below.

**Download Your Quire Project from Github**
1. Open GitHub Desktop.
2. Click on the upper left-hand corner of the application window, where it says “Current Repository”. Click “Add” and choose the option to “Clone repository…”
3. Click the URL menu option and cut-and-paste the following URL: https://github.com/thegetty/quire-docs.
4. Save the cloned `quire-docs` repo in your home directory.

**Preview Your Quire Publication**
1. Next, pull up your [command line](https://quire.getty.edu/learn/tutorial/#1-work-in-a-command-line-shell) to navigate through your computer files.
2. Use the cd command to navigate to your computer's home directory and then navigate into your `quire-docs` folder.
3. Once you are in your `quire-docs` folder, run the following commands:
```
quire install
quire preview
```
4. Go to [http://localhost:1313](http://localhost:1313) the project as you work on it.

**Open Your Project in GitHub Desktop**
1. At the top right, click "Current Repository" and choose the `quire-docs` repo.

**Create a New Branch in GitHub Desktop**
1. Navigate to where it says “Current Branch” at the top of your GitHub Desktop window.
2. Click the drop-down arrow and select “new branch” to the right of the Filter box.
3. Name your branch.
4. Select “main” where it says “Create branch based on.” This means you are creating a new branch that runs parallel to the main project.

**Open Project File in Atom**
1. Open Atom
2. Click File > Open
3. Navigate to your home directory and your select `quire-docs` folder.
5. In Atom, expand the contents folder to see the editable markdown files and look for the file you'd like to make your changes in.

**Save Changes in Atom**
1. To save changes, hit File > Save or Command-S (Mac) or Control-S (PC).
2. If working on multiple markdown files, make sure to save each file individually. You will see a little blue dot at the top of the page if there are any unsaved changes.
3. Double check that your changes look right by previewing at [http://localhost:1313](http://localhost:1313).

**Make Commits in GitHub Desktop**
1. At the bottom left, above where it says description, write a short name for your commit. You have the option to include a description as well.
2. Press the blue button that says “Commit to [branch name].”

**Push Changes in GitHub**
1. After you have made all your commits, click on the "Publish Branch" and then “Push Origin” button at the top right.
2. Now the changes to your project have been successfully saved to your branch on GitHub.

## Submit Your Contribution

Once you've identified your contribution and submitted changes through GitHub Desktop, you will prepare to submit it to us for review as a pull request. A pull request says, “Hey, I did something useful for you, want to pull it in and merge it into your project?”

A pull request is a chance for Quire’s core team to evaluate the proposed changes made and decide whether to:

- merge them in as is
- merge them in with changes
- reject them

>A pull request doesn’t have to represent finished work. We always recommend opening a pull request early on, so others can watch or give feedback on your progress. When submitting a work in progress pull request, please mark it as a draft by following [these instructions](https://github.blog/2019-02-14-introducing-draft-pull-requests/). As you make new commits to that branch and push them to GitHub, they’ll automatically be added to the open pull request.

**Create a Pull Request in GitHub**
1. Click the blue-button that says “Create Pull Request.” This will take you to GitHub.com.
2. Confirm that the branch in the base drop-down menu is the `main` branch of the `quire-docs` repo.
3. You can leave the default title or type a new title and description for your pull request.
4. On the right-hand side, you will see an option to choose a reviewer. Choose **@erin-cecele** and she will receive a notification of your pull request.
5. Click the green-button that says “Create Pull Request” if all your changes are ready for review. Or click the drop-down arrow and choose “Create Draft Pull Request” if you are still making changes that will be included in this particular pull request.
6. Once your pull request has been reviewed and approved, you will see your work merged into the Quire documentation and website!!

Here are a few tips when submitting your pull request:
- If this is your first time putting in a pull request on a project like this, we recommend the [*First Contributions* command line](https://github.com/firstcontributions/first-contributions), or Kent C. Dodds' video series, [“How to Contribute to an Open Source Project on GitHub”](https://egghead.io/courses/how-to-contribute-to-an-open-source-project-on-github)
- Reference any relevant issues or supporting documentation in your pull request description (for example, “Closes #203.”)
- Follow the pull request remplate to explain what the changes do and what your approach was.
- Include screenshots of the before and after if relevant.
- You may receive feedback or requests for changes to your pull request from Quire’s core team before your work can be merged. Answer questions in the pull request comments, make changes and new commits if needed, or suggest alternate solutions if you have them.

Thank your for reading our `quire-docs` Contributing Guidelines. To learn more in the *Open Source Guide*’s [“How to Contribute to Open Source”](https://opensource.guide/how-to-contribute/).

**At this point, we hope you feel ready to contribute! But don’t hesitate to [ask for help or clarification](mailto:quire@getty.edu), everyone’s a beginner at first. And thank you again for your interest in making Quire a better tool for all!** 🦄

## Helpful Resources

- [Code of Conduct](https://github.com/thegetty/quire-docs/blob/main/CODE_OF_CONDUCT.md)
- [Website & Documentation Style Guide](https://github.com/thegetty/quire-docs/wiki/Quire-Website-&-Documentation-Style-Guide)
- [GitHub Desktop Documentation](https://docs.github.com/en/desktop)
- [Website](https://quire.getty.edu)
- [Issue Tracking](https://github.com/thegetty/quire-docs/issues/)
- [Documentation](https://quire.getty.edu/documentation)
- [Community Forum](https://github.com/thegetty/quire/discussions)

**Quire Core Team:**

Greg Albers ([@geealbers](https://github.com/geealbers)), product manager<br />
David Newbury ([@workergnome](https://github.com/workergnome)), product manager<br />
Matthew Hrudka ([@mphstudios](https://github.com/mphstudios)), lead maintainer<br />
Erin Cecele Dunigan ([@Erin-Cecele](https://github.com/Erin-Cecele)), community manager<br />

Contact us at [quire@getty.edu](mailto:quire@getty.edu)
