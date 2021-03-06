# What is a user story?
* What makes a great user story
  * agile development uses four clear delivery vehicles to bring structure to any agile project: user stories, sprints, epics, and versions.
  * The goal of a user story is to deliver a particular value back to the customer.
  * A story or user story is a software system requirement that is expressed in a few short sentences, ideally using non-technical language.
  * They don't go into detailed requirements. User stories are often written using the following template:
  > As a [type of user], I want [goal] so that I [receive benefit].

  * Let's use a website as a simple example to create a user story.
  > As a customer, I want to be able to create an account so that I can see the purchases I made in the last year to help me budget for next year.


  > “Stories are deliberately not fleshed out in detail until they are ready to be developed, you only need enough understanding to allow prioritization with other stories.” - Kent Beck

* Version (theme) vs Epic vs user story vs task
  * A version is a set of features and fixes released together as a single update to your product. Assigning issues to versions helps you plan the order in which new features (stories) for your product will be released to your customers.
  * An epic captures a large body of work. It is essentially a large user story that can be broken down into a number of smaller stories. It may take several sprints to complete an epic.
  * In JIRA Agile, a story is represented as an issue, and individual tasks within the story are represented as sub-tasks.
  * A sub-task issue is typically one of many tasks that make up a story (or parent issue).
* User story dos and don’ts
  * INVEST
    * I – Independent
      * Stories are easiest to work with if they are independent. That is, we'd like them to not overlap in concept, and we'd like to be able to schedule and implement them in any order.
    * N – Negotiable
      * A good story is negotiable. It is not an explicit contract for features; rather, details will be co-created by the customer and programmer during development. A good story captures the essence, not the details. Over time, the card may acquire notes, test ideas, and so on, but we don't need these to prioritize or schedule stories.
    * V – Valuable
      * A story needs to be valuable. We don't care about value to just anybody; it needs to be valuable to the customer. Developers may have (legitimate) concerns, but these framed in a way that makes the customer perceive them as important. This is especially an issue when splitting stories. Think of a whole story as a multi-layer cake, e.g., a network layer, a persistence layer, a logic layer, and a presentation layer. When we split a story, we're serving up only part of that cake. We want to give the customer the essence of the whole cake, and the best way is to slice vertically through the layers. Developers often have an inclination to work on only one layer at a time (and get it "right"); but a full database layer (for example) has little value to the customer if there's no presentation layer.
    * E – Estimable
      * A good story can be estimated. We don't need an exact estimate, but just enough to help the customer rank and schedule the story's implementation. Being estimable is partly a function of being negotiated, as it's hard to estimate a story we don't understand. It is also a function of size: bigger stories are harder to estimate. Finally, it's a function of the team: what's easy to estimate will vary depending on the team's experience. (Sometimes a team may have to split a story into a (time-boxed) "spike" that will give the team enough information to make a decent estimate, and the rest of the story that will actually implement the desired feature.)
    * S – Small
      * Good stories tend to be small. Stories typically represent at most a few person-weeks worth of work. (Some teams restrict them to a few person-days of work.) Above this size, and it seems to be too hard to know what's in the story's scope. Saying, "it would take me more than a month" often implicitly adds, "as I don't understand what-all it would entail." Smaller stories tend to get more accurate estimates.
    * T – Testable
      * A good story is testable. Writing a story card carries an implicit promise: "I understand what I want well enough that I could write a test for it." Several teams have reported that by requiring customer tests before implementing a story, the team is more productive. "Testability" has always been a characteristic of good requirements; actually writing the tests early helps us know whether this goal is met. If a customer doesn't know how to test something, this may indicate that the story isn't clear enough, or that it doesn't reflect something valuable to them, or that the customer just needs help in testing. A team can treat non-functional requirements (such as performance and usability) as things that need to be tested. Figure out how to operationalize these tests will help the team learn the true needs.
* Advantages of Jira; tips and tricks
* Examples of best in class and ineffective user stories you’ve received, and showing the end result of work in each case

## IN-SESSION EXERCISE YOU’LL LEAD:
* Select a real-life scenario (with sketches/wireframes, if possible)
* Present the concept of the feature
* Participants to write epic and 1-2 supporting user stories
* Participants will share their user stories and compare to real-life stories that were used for an already developed feature.
