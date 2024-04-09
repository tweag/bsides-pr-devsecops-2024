
# Template Repository - Shifting Security Left a Hands On Workshop

The following repository contains training material workshops on shifting security left.

This workshop is held at venue `X` on `DATE` at `TIME`.

## Workshop Outline

*Shifting Security Left a Hands On Workshop* provides participants with an introduction to baking security into the software development process and leveraging DevSecOps tooling to support this. 

Attendees will learn about setting up a local development environment which includes security tools such as IDE plugins. Students will then progress into learning how to use DevSecOps pipelines to detect security issues such as accidentally committed secrets.

The workshop will then wrap up with tips on how to handle secure deployments and a look to what the future holds in this space.

## Pre-setup Phase

In order to fully participate in this workshop you will need a GitHub account.

You can obtain this by signing up at http://www.github.com. 

Students will be able to sign up for a .edu account which comes with some added bonuses, such as being able to setup private repositories for free.

Once your account is setup, you will need to `Fork` and `Clone` this repository.


## Security within the development environment

Attendees will learn to integrate security tools and pre-commit hooks into their development environment thus enhancing code security off the bat:

1. 3rd party plugin integration. In this part of the talk we explore third-party tooling that can be integrated into the IDE to aid in linting and SAST. An example here includes the Horusec plugin.

2. Setting up pre-commit hooks to aid in security will be explored via the Talisman tool.

3. Git ignores. Git ignore files are a great way of preventing config files which may contain secrets, and other undesirable files such as .zips accidentally being committed. In this portion of the talk we provide practical examples of using .gitignore to aid in security.

Next we cover some repository scanning techniques, including secrets scanning and vulnerability detection, using tools like GitHub's dependabot.

1. Branch protection and pull request gating mechanisms. Here we learn how to enable branch protection rules and gate pull-requests. This sets students up to later modify the gating mechanisms to include security tooling.

2. Secrets scanning. A demonstration of how secret scanning can be performed in the source code. This includes examples of GitHub's tooling and Horusec.

3. Detecting security vulnerabilities within the repository. Students are introduced to the concept of detecting security vulnerabilities in the source code repository. A general overview of techniques and approaches is given, as well as those specific to GitHub.

4. Static analysis. GitHub Advanced Security contains a GitHub native SAST tool built on CodeQL. This section of the class walks through its feature sets and how it can be integrated into GitHub actions. This section of the talk will also cover Horusec and how it cane be used in the same capacity.

5. Vulnerable dependency detection. GitHub's dependabot provides a mechanism for analyzing the dependencies associated with a project and understanding if they contain security vulnerabilities. Walkthrough of dependabot is performed.

6. SBOMs. A final note on SBOMs. These can be used to extract a Software Bill of Materials from your applications stored in GitHub.

## Wrap-up

Discussion of future trends in this space.

Recap of what we've learned

