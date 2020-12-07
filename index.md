---

layout: col-sidebar
title: OWASP SecureFlag Open Platform
tags: training appsec securecoding secdevops secureflag
level: 2
type: tool
pitch: Training platform for developers to learn and practice modern secure coding techniques through hands-on exercises.

---



<p align="center"><img src="assets/images/secureflag-logo.png"/></p>

<br/>

The SecureFlag Open Platform is an open source training platform created for developers to learn and practice modern secure coding techniques through hands-on exercises. The platform helps develop secure coding skills through real-world challenges to ensure knowledge acquired during the course can be confidently and continuously applied in the real world.

<br/>

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/24KrcgjsBaw" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</p>

<br/>

Developers manually find, exploit and remediate the code of vulnerable applications running in development environments accessed via a web browser. The platform offers 100% hands-on training, with no multiple-choice questions involved, and uses an engine able to live-test code changes to measure efficacy, instantly displaying whether the code has been fixed and awarding points upon exercise completion. 

SecureFlag provides a gamified experience where users can assemble into teams, track their progress through a leaderboard and unlock special challenges. Exercises are grouped into sequences of logically-linked units called Learning Paths that enable participants to attain expert, usable knowledge in relatively small steps. When candidates complete a Learning Path, they receive a SecureFlag certification; certifications have an expiration date and can be renewed by taking refresher exercises throughout the year. 

Armed with their newly embedded capacities, developers can take part in time-boxed tournaments and engage a whole community of participants from within the same organisation, all competing to remediate security issues.

## Who should use SecureFlag Open Platform?

SecureFlag Open Platform helps professionals who want to raise awareness about application security within their workplace by organising training sessions and tournaments. Additionally, professors and trainers can benefit by using the platform to teach practical secure programming in their courses. Even communities of security enthusiasts can adopt Secureflag Open Platform to improve their application security skills in a methodical yet enjoyable way.

Whatever the need may be, SecureFlag Open Platform enables you to deploy your own secure coding training platform in a matter of minutes, which can be used by you and everyone else in your organisation.

## How does SecureFlag Open Platform work?

SecureFlag Open Platform is a platform based on a micro-services architecture that runs on AWS. The entire infrastructure is created  in a completely automated fashion, from scratch, in less than 15 minutes.

The core components of the infrastructure are:

* The [portal](https://gitlab.com/secureflag-community/portal): the main web application. It allows the candidates to run the exercises and the administrators to manage and configure the platform.
* The [gateway](https://gitlab.com/secureflag-community/gateway): the remote desktop gateway that makes the exercise desktops accessible through a web browser.
* A MySQL [database](https://gitlab.com/secureflag-community/database).

Read further information regarding [how to install SecureFlag](https://community.secureflag.com/#/platform/installation).

Users can run secure coding exercises through the portal by choosing from a catalog of topics in different languages and frameworks. 

When an exercise is launched, a dedicated Linux desktop is run and the trainee is provided with step-by-step instructions on how to find, exploit and finally remediate the security issue.

Exercises run in isolated Docker containers that are disposed when the exercise ends. The desktop comes with a pre-configured development environment, complete with the IDE and various tools that the candidate can use to solve the exercise. Environments are created on demand and can be accessed through a web browser, without the need to install additional software.

Exercises can be either be downloaded from the SecureFlag Hub or newly created with SecureFlag's SDK. The SDK enables the creation of Exercises to be published on the SecureFlag Exercise Hub for the entire community to use.

Read more about exercise development in the [SDK](https://community.secureflag.com/#/sdk/setup-sfsdk) section.


## Functionalities

- Run exercises in a dedicated environment in the cloud; find & fix vulnerabilities following the instructions.
- Real, turn-key, development environment pre-configured with selected vulnerable exercises.
- Exercises focus on exploitation / remediation or secure coding and target the most common application security issues.
- Live-test changes to instantly learn if code has been fixed and award points for completing the exercise.
- Automated deployment on AWS through CloudFormation.
- Install Exercises from the SecureFlag Exercise Hub or create new ones with the SecureFlag SDK.
- Assign Learning Paths to align developer skills according to the company’s risk appetite.
- Setup Tournaments to engage the entire developer community in your organisation.
- Setup and manage Organisations, Teams and Users through the Management interface.
- Get Stats at an Organisational, Regional, Team and User level to quickly identify gaps.


### Discover more at [https://community.secureflag.com](https://community.secureflag.com).
