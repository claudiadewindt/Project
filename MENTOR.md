# Project mentors

For the final project the students require a `tech lead`, a `QA lead` and `product owner` for 6 weeks and a `scrum master` for 3 weeks. Usually we split this into two parts (first 3 weeks and last 3 weeks). The first 3 weeks are all about building the mvp together with the students. This is a little more hands-on as this will be the first full stack application they build as a group and we will let the students be a little more chaotic while they are wrapping their heads around their app. In the last 3 weeks the goal is to simulate a developer team with weekly sprints, refinement steps, retrospectives, etc. to have them experience what that looks like.

Below we will go into the different parts highlighting the responsibilities and time commitments per week. Weeks start on Sunday (except for week 0 which means any time before the first Sunday) and the week responsibilities are for the week after the Sunday meeting.

## 1. Part 1 (Build the MVP)

In part 1 we are deciding on an app and building a first minimal version. At this point, the students will want to build as much as possible and will probably lose sight of some of the key steps to development. That is ok, in part 2 they will see why these are so important. The focus at this point should be to implement features and get a little workflow going.

### 1.1 Tech lead

The table below gives an overview of what is expected, in the sections after that we go in deeper into what it means exactly.

| Week # | Sunday meeting             | Week responsibilities             |
| ------ | -------------------------- | --------------------------------- |
| 0.     | -                          | Look through project github       |
| 1.     | [Agenda](/week1/README.md) | Support the team in making an ERD |
| 2.     | [Agenda](/week2/README.md) | Manage code/reviews               |
| 3.     | [Agenda](/week3/README.md) | Supervise code/reviews            |

In week 7 of the project the students will have a presentation to show off what they have built, to which you are obviously invited!

#### Looking through the project github

You will be invited to the class project github and will want to spend some time looking at the setup. We usually have a `develop` and `main` branch, with the `develop` branch set up as the default branch where everyone publishes towards. There will also be a single roundtrip implemented with the basic folder structure set up (`client` for frontend and `server` for the backend with some `README`'s). We have some CI/CD pipelines set up to automatically check the code/run the tests and deploy the application on heroku. Have a look at the `README` for more information on this.

#### Supporting the team in making an ERD

In week 1 the class will be given a deliverable to create an ERD for the basic app, have a look at the description [here](/week1/MAKEME.md). The goal is to have a nice idea of the database schemas that the app will need that you should review to make sure that they aren't walking into pitfalls.

#### Managing/supervising code reviews

In week 2 and 3 the students will start building features. This will be the first time they really work on something with this many people and it will be a little difficult at the start. We want them to learn how to do code reviews properly, and that will require a little bit of support as well as supervising. From previous experience, expect the following:

- Struggling with `code merge errors` and how to solve them correctly
- `Non-critical code reviews`. The students will still feel a little unsure about what they think is right and accept whatever the other wrote. You will need to be a little pushy to have them say what they actually think to get a better code base.

In week 2 we expect you to have to do some code reviews yourself (after other students have looked at it) to show them that it is fine to be critical and make sure that the start of the project is clean. In week 3 we want to start transitioning into the students handling it all themselves, but do have a look at the code that is being pushed to make sure the quality is still high.

### 1.2 Product owner

The table below gives an overview of what is expected, in the sections after that we go in deeper into what it means exactly.

| Week # | Sunday meeting                                 | Week responsibilities                   |
| ------ | ---------------------------------------------- | --------------------------------------- |
| 0.     | -                                              | Set up the project board                |
| 1.     | Facilitate meeting: [Agenda](/week1/README.md) | Support the team in making user stories |
| 2.     | Facilitate meeting: [Agenda](/week2/README.md) | -                                       |
| 3.     | Facilitate meeting: [Agenda](/week3/README.md) | -                                       |

In week 7 of the project the students will have a presentation to show off what they have built, to which you are obviously invited!

#### Setting up the project board

You will be invited to the class project github and will want to set up the project board (`projects` tab) to how you would like to organise it. Also add an example user story to deploy the project so that the user can actually use the application. This will serve as a template for the students to make their own user stories in week 1.

#### Supporting the team in making user stories

In week 1 the class will have a deliverable of having user stories set up. The goal is to have a nice and clear wireframe set up that can serve as a guide for the students of what to build. They will also need to decide on what is in the initial version (doable in 2 weeks). From previous experience, expect the following:

- Questions about `user stories` and how to word them. Also why we do it like this
- The inability to cut features because 'it is all needed to be useful'

#### Facilitating meetings

In week 1, 2 and 3, it is the responsibility of the Product owner to facilitate the meetings. That means:

- Create a video conference link and share it in the class channel at 12:00
- Once everyone is there, go through the points as described in that week's agenda. If any of the points are unclear, let us know and we will help explain the goal
- After the meeting, write a message highlighting the important decisions/plan for that week so that everyone is on the same page

### 1.3 QA lead

The table below gives an overview of what is expected, in the sections after that we go in deeper into what it means exactly.

| Week # | Sunday meeting             | Week responsibilities                                      |
| ------ | -------------------------- | ---------------------------------------------------------- |
| 0.     | -                          | -                                                          |
| 1.     | [Agenda](/week1/README.md) | Be available for theory questions                          |
| 2.     | [Agenda](/week2/README.md) | Be available for questions, check out test cases/scenarios |
| 3.     | [Agenda](/week3/README.md) | Be available for questions, check out test cases/scenarios |

In week 7 of the project the students will have a presentation to show off what they have built, to which you are obviously invited!

#### Be available for (theory) questions

Every week, the QA students will get some theory to read through and they may have questions about that. You are the person they will approach if the material is unclear or they are unsure about something. During the week the students will also be tasked to perform the QA tasks mentioned [here](/week2/MAKEME.md) for which they may also require assistance.

#### Check out test cases/scenarios

The students will be tasked to add their test cases/scenarios to the user stories, as the QA lead it is up to you to ensure that these cover all the cases and provide a well rounded test strategy for that user story.

## 2. Part 2 (Work as a scrum team)

### 2.1 Tech lead

The table below gives an overview of what is expected, in the sections after that we go in deeper into what it means exactly.

| Week # | Sunday meeting             | Week responsibilities      |
| ------ | -------------------------- | -------------------------- |
| 3.     | -                          | Look through project code  |
| 4.     | [Agenda](/week4/README.md) | Be available for questions |
| 5.     | [Agenda](/week5/README.md) | Be available for questions |
| 6.     | [Agenda](/week6/README.md) | Be available for questions |

In week 7 of the project the students will have a presentation to show off what they have built, to which you are obviously invited!

#### Technical refinement

During the Sunday meetings (week 4, 5, 6) the students will be asked to do technical refinements. They haven't done it before so we expect you to have to assist a little more in the first week and then less and less as the weeks go on.

#### Looking through the project code

You will be invited to the class project github and will want to spend some time looking at the code before the first meeting. This should help you with assisting with technical refinements as well as answering any technical questions that may come up. The class will have already done 3 weeks of work on the application!

#### Be available for questions

During the week you may be asked for help if the class gets really stuck. They already have 3 weeks in them, so we expect the questions to be minimal, but you should be available at least once per day to answer anything. Let the class know the best way to reach you!

### 2.2 Product Owner

The table below gives an overview of what is expected, in the sections after that we go in deeper into what it means exactly.

| Week # | Sunday meeting             | Week responsibilities                        |
| ------ | -------------------------- | -------------------------------------------- |
| 3.     | -                          | Check out the app, wireframes, project board |
| 4.     | [Agenda](/week4/README.md) | -                                            |
| 5.     | [Agenda](/week5/README.md) | -                                            |
| 6.     | [Agenda](/week6/README.md) | -                                            |

In week 7 of the project the students will have a presentation to show off what they have built, to which you are obviously invited!

#### Check out the app, wireframes and project board

In the first three weeks an MVP will be built for the application. During week 3, the students will be asked to share a link to a deployed version of the app, the wireframes and you will also be invited to the github project. Have a look before the first Sunday meeting to check out what the app is that is being built and what the current status is. During the Sunday meetings it is your responsibility to answer questions about how the app should work as well as what the priority is!

### 2.3 QA lead

The table below gives an overview of what is expected, in the sections after that we go in deeper into what it means exactly.

| Week # | Sunday meeting             | Week responsibilities                                                                                    |
| ------ | -------------------------- | -------------------------------------------------------------------------------------------------------- |
| 3.     | -                          | Check out the app, wireframes, project board                                                             |
| 4.     | [Agenda](/week4/README.md) | Be available for questions, check out test cases/scenarios, do an exploratory test debriefing            |
| 5.     | [Agenda](/week5/README.md) | Be available for questions, check out test cases/scenarios, do an exploratory test debriefing (possibly) |
| 6.     | [Agenda](/week6/README.md) | Be available for questions                                                                               |

In week 7 of the project the students will have a presentation to show off what they have built, to which you are obviously invited!

#### Be available for questions

Every week, the QA students will get some theory to read through and they may have questions about that. You are the person they will approach if the material is unclear or they are unsure about something. During the week the students will also be tasked to perform the QA tasks mentioned [here](/week2/MAKEME.md) for which they may also require assistance.

#### Check out test cases/scenarios

The students will be tasked to add their test cases/scenarios to the user stories, as the QA lead it is up to you to ensure that these cover all the cases and provide a well rounded test strategy for that user story.

#### Do an exploratory test debriefing

In week 4 the students will learn about exploratory testing and will be tasked to do one and then debrief with the QA lead. Give them feedback on how they did and suggestions on how to improve. At the end of the project they will have to have done one successful exploratory test, we will leave it up to you as the QA lead to determine if the student passed the exploratory test.

### 2.3 Scrum Master

The table below gives an overview of what is expected, in the sections after that we go in deeper into what it means exactly.

| Week # | Sunday meeting                         | Week responsibilities       |
| ------ | -------------------------------------- | --------------------------- |
| 3.     | -                                      | Check out the project board |
| 4.     | Facilitate: [Agenda](/week4/README.md) | -                           |
| 5.     | Facilitate: [Agenda](/week5/README.md) | -                           |
| 6.     | Facilitate: [Agenda](/week6/README.md) | -                           |

In week 7 of the project the students will have a presentation to show off what they have built, to which you are obviously invited!

#### Check out the project board

In the first three weeks an MVP will be built for the application. During week 3, the students will be asked to share a link to a deployed version of the app, the wireframes and you will also be invited to the github project. Have a look before the first Sunday meeting to check out what the current status is. And have a look at the project board to see how it has been organised so far. Feel free to make adjustments, but if you do you have to explain them on Sunday!

### Facilitating meetings

Week 4, 5 and 6 will be facilitated by the Scrum Master. Have a look at the agenda's to see what that means exactly and if it is unclear, let us know! In week 5 and 6 we would like to have retrospectives to show the students what these are like and why they are useful. For week 6, it is important to help the students scope the last week with solely bugs and small improvements so that there is a nice looking and bugfree final version online!
