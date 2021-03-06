# Usability
## What is the goal of this branch?
To proactively report any behavior/usability issue that might affect the overall User Experience of Redu. [ISO](http://www.iso.org/iso/home.html) define usability as: 
> “The extent to which a product can be used by specified users to achieve specified goals with effectiveness, efficiency, and satisfaction in a specified context of use.”

By this definition, we should report a usability issue every time someone realize that the interface cannot achieve the following *standart* metrics:
- **Learnability**: how easy is it for users to accomplish basic tasks the first time they encounter the design?
- **Efficiency**: once users have learned the design, how quickly can they perform tasks?
- **Memorability**: when users return to the design after a period of not using it, how easily can they re establish proficiency?
- **Errors**: how many errors do users make, how severe are these errors, and how easily can they recover from the errors?
- **Satisfaction**: how pleasant is it to use the design?

#### Further Reference
Usability guidelines we can use as reference: [Usability.gov](http://guidelines.usability.gov/)

Social Media User Experience: [Social UX] (http://www.nngroup.com/reports/social-media-user-experience/)

## How can you report a usability issue?

1. Generate and upload a **screenshot** of the interface's context;
2. Inform **where** this issue come from (in Redu's architecture);
3. Inform **what** the user wanted to do;
4. Inform **why** he couldn't do what he wanted;
5. Inform if there was some **frustation** because of this issue.

Some informations may be difficult (or impossible) to note. In these cases, you have to be careful about your personal assumptions from the facts it is shown.
## How can you rank a issue?
Every issue created must be associated with a label — _high_, _medium_, _low_ and/or _next version_.  We rank these labels by the following matrix:

![Ranking Issues](https://dl.dropboxusercontent.com/u/13659411/Ranking-Issues.png)

#### Value
The measure of value must be guided to accomplish Redu's strategic decisions:

1. Content production;
2. Management of V.L.E. (“A.V.A.”);
3. Members' social interactions (“A.V.A.”);
4. Lessons' visualization;
5. Security and privacy;
6. Partnership.

#### Impediment
The measure of impediment must follow the [usability's standart metrics](https://github.com/redu/usability/blob/master/README.md#what-is-the-goal-of-this-branch).

***

P.S.: *next version* is a label for issues that may be hard to solve in the current version of the U.I. and/or have a need for more than two iterations to be ready. It must be together of _high_, _medium_ or _low_ labels.
