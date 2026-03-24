# Getting Started with Vibe Coding

If you are...

* ...a complete newbie, consider:
    * [Google AI Studio](#google-ai-studio)
* ...able to write a little code and want some occasional support, go with:
    * [Gemini Code Assist in Google Cloud Shell](#gemini-code-assist-in-google-cloud-shell)
* ...able to run applications locally on your own computer
    * [Cursor](#cursor)
    * [GitHub Copilot](#github-copilot-in-visual-studio-code)
* ...a pro, use:
    * [Claude Code](#claude-code)

## Getting Started Walkthroughs
1. [Creating a portfolio site in Google AI Studio](aistudio.md)


## Vibe Coding Platform Options

### Google AI Studio
[Google AI Studio](https://ai.studio)

#### Pros
* Drop-dead simple to start
* Easy publishing to Google Cloud Run
* Keeps all working files in context – easy to make changes throughout the project

#### Cons
* Connection to GitHub is unstable
* Cannot collaborate with others (and cannot pull external changes made to your repository)
* Focused on web-based applications, with an emphasis on React

### Gemini Code Assist in Google Cloud Shell
[Google Cloud Shell](https://ide.cloud.google.com)

#### Pros
* Integrated into Cloud Shell VM (nothing to install on your computer)
* Easy access to standard Cloud Shell integrations (GitHub, Google Cloud Run, etc.)
* Easy to collaborate with others (via Git and GitHub)

#### Cons
* "Agent" mode fails...a lot
* Does not automatically keep all files in context – can only read files that are open in the IDE

### Cursor
[Cursor](https://cursor.com)

#### Pros
* [Free for students for 12 months](https://cursor.com/students)
* Robust code editing in a VS Code-like setting

#### Cons
* You'll need to install software packages on your local machine to run/preview your applications
* Cannot be used in conjunction with Google Cloud Shell


### GitHub Copilot in Visual Studio Code
[GitHub Copilot](https://github.com/features/copilot)

#### Pros
* [Free for students via the GitHub Education program](https://github.com/education/students)
* Integrated into VS Code

#### Cons
* You'll need to install software packages on your local machine to run/preview your applications
* Cannot be used in conjunction with Google Cloud Shell


### Claude Code
[Claude Code](https://claude.ai/)

#### Pros
* Powerful terminal-like setting with extensive add-ons (MCPs) and scriptability

#### Cons
* No free access – requires a [Claude subscription](https://claude.com/pricing)
* Overkill for this course – requires some computer expertise and development experience