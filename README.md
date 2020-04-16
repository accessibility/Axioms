# A11yAxioms
Accessibility Axioms (A11yAxioms): Basic truths about building an inclusive digital world. An [axiom](https://en.wikipedia.org/wiki/Axiom) is a "statement that is taken to be true, to serve as a premise or starting point for further reasoning and arguments." In this case, the further reasoning is to help us build a common understanding of how to approach buidling a digitally inclusive future. The axioms here should simplify our understanding of the bigger process. 

Much of this discussion started on Twitter on the [A11yAxioms hashtag](https://twitter.com/hashtag/A11yAxiom), [Reddit](https://www.reddit.com/r/accessibility/comments/fkfdj5/id_love_feedback_on_these_basic_nuggets_of_truth/) and [LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:6645820604584906752). Lots of people have contributed on social media. Thanks! 

## Standards
- **Some things don’t appear in WCAG, not because they aren’t important, but because they cannot be concisely expressed and defended.** Cognitive and learning disabilities are often neglected from accessibility standards. It is  hard to express some needs as a universally understood success criterion. 
- **WCAG is nothing more than a good start to the larger goal of an inclusive society.** Achieving WCAG 2.x AA conformance is good, but insufficient on its own. 
- **WCAG isn’t perfect.** It is only as good as the people and the community behind it. Creating community guidelines is hard, but a necessary pre-condition to building a common solution. 
- **A site with some accessibility enhancements will be easier to comply with newer guidelines.** A site that meets WCAG 2.0 A  should be easier to remediate to meet WCAG 2.1 AA than a comparable site that has had no accessibility considerations.
- **New WCAG 2.x guidelines build on the previous ones. A site meeting WCAG 2.1 AA will also meet WCAG 2.0 AA.**

## Design
- **User-centered design isn’t going to give you as inclusive a result as user-led design.** Design with - not for - people with disabilities. 
- **Without an inclusion lens, digital solutions are brittle.** Permanent disabilities about hit 15% of the population. Temporary and situational disabilities effect us all. Thinking about accessibility early helps reduce the higher costs of remediating older implementations.
- **Design for the extremes of humanity.** If you start with the starburst of humanity it will be easier to meet WCAG later. Products and services that are built for the 80/20 Rule (Pareto Principle) are harder to make inclusive afterwards. 
- **Uncomplicated interfaces are easier to make accessible, more usable, and will be simpler to maintain.**
- **Keep it simple.** Start with sound document structure. On the web that means semantic HTML and adding WAI-ARIA if the semantics can't be added through HTML. Use CSS to solve visual layout issues and JavaScript to enhance behavior.

## Software
- **Public facing tools get more review than internal facing sites and authoring tools.**  Not all disabilities are publicly known and and the abilities of our teams change over time. 
- **It is easier to improve the accessibility in a system with reasonable accessibility than to start with one with unknown number of accessibility issues.** 
- **All CMS’s are broken into those elements which an editor can control, and those that are managed by the system which developers build**. This is similar to how a photo sits in a frame. 
- **Critical mass matters** the more people who use the same system, the more likely that your organization will be able to benefit from someone else's work. Communities that share and encourage openness are best for finding solutions. 
- **There is no overlay that can fix all accessibility issues.** You can't add meaningful semantics and document structure after the fact. These JavaScript overlays can fix some some issues, for some disabilities, but WCAG requirements are broader than this. 

## Software development
- **Building with patterns that have previously been tested for accessibility will reduce costs for implementing WCAG.** 
- **Make things open: it makes things better.** This is especially true in digital accessibility where everyone is trying to keep up with the internet. 
- **The earlier you start incorporating digital accessibility into your digital tool, the less expensive it will be to become accessible (shift left).**
- **No ARIA is better than bad ARIA.** Often WAI-ARIA isn't properly applied. WAI-ARIA is an important enhancement to HTML5, but it must be very carefully applied. 
- **It is more difficult to assess WAI-ARIA semantics than it is HTML5.** Sites with lots of WAI-ARIA will take more time to check if is accessible. 

## Software as process
- **Software on the internet needs to be seen as a living system.** Need to move from leveraging periodic checklists to building an ongoing journey.
- **It is more expensive to make a legacy tool accessible than it is to rebuild it on a more accessible platform.**
- **Older software is more likely to have accessibility problems.** Although not universally true, accessibility awareness and tools are improving, and older tools are likely to have more accessibility problems. 
- **Constant vigilance is required.  Just because an interface did meet meet WCAG 2.0 AA, doesn't mean that it will six months later.** Technology, W3C standards and our use of it is constantly changing. 
- **Given the number of potential patterns for a given accessibility solution, the chance of a team selecting a best practice in isolation is low.** Only by comparing solutions will the advantages/disadvantages of any given solutions be understood.
- **You are more likely to get accessibility problems fixed in development or alpha/beta stages of software development.** Once a stable version of the software has been released, many core developers focus their energy on the next version of the software.

## Accessibility testing
- **Automated testing is a great first step.** But can only find around a third of accessibility issues.
- **A blended testing approach will provide the best results.** Plan for tests that can be automated along with your continuous integration (CI), tests that can be easily applied by themers & designers, tests that can be leveraged by editors, and tests to gather site wide errors. 
- **There is no perfect accessibility tool, nor is any one tool going to always provide the best results.** A combination of automated tools should be used, some of the errors identified may be accessibility false positives. 
- **The automated tests are getting better over time.**  More tools adopting the W3C's Accessibility Conformance Testing (ACT) Rules will provide greater consistency in the results different tools provide. 
- **Keyboard issues hold about 40% of accessibility failures**, and most automated tools do not evaluate for them. Testing for this is relatively easy, but is often overlooked. 
- **Involving people with lived experience with disability early in the development process will produce more accessible results.**

## Authoring
- **Authoring experiences can shape the accessibility of their work.** The Authoring Tool Accessibility Guidelines (ATAG) 2.0, Part B is a strong example of this.
- **Accessibility will always be easier if a project starts with good, meaningfully structured content written in plain language.** Do the hard work of making it easy to understand. 
- **Any process involved in creating digital content can impact its accessibility.** After it is created, lots of different software is required to deliver it to the end user. Software is rarely built perfectly to a common open standards.
- **If accessibility is the easiest, default option, more things will be accessible.** Lets make sure to focus on shifting the defaults. 

## Achievable Goals
- **Digital tools will never be 100% accessible, just like it will never be 100% secure.**
- **There is always more that can be done to be more inclusive,** how inclusive you need to be will depend on the users and your budget. Be focused on making your site more accessible today than it was yesterday. 
- **The digital ecosystem is based on standards but is not standardized.** Despite the call to design with Web Standards, browsers and assistive technology all are working to build a competitive advantage. New standards are often slow to incorporate in user agents and bigger companies often include extras elements that better support their users. 

## Process (People)
- **Good accessibility is a community effort.** In order to effectively address accessibility issues, we need experience outside of project teams. Collaborative approaches will achieve the best results in the long run.
- **There will always be users who find barriers to their use of the technology.** Having an open feedback system will help to identify new accessibility issues. 
- **Individuals can only do so much in isolation.** The more people that champion and apply a lens around accessibility and inclusion within an organization, the more they can scale efforts, capacity and improve outcomes for people who use their products and services.
- **Digital accessibility involves technology, but should not be technocratic.** Empathy is required to make good judgements as this is ultimately a human issue. Objectivity is needed to guide judgement, and thus we need to invest in common standards. 
- **Accessibility is about ensuring that an author can effectively communicate to a user who may have a disability.**  Sometimes the author is using the wrong tools and the challenge becomes transitioning to use the right tools and in the right way. 
- **There’s no such thing as an average user and the need for personalization is inevitable.** There is no “one-size-fits-all” digital tool that will meet everyone’s needs. Dark Mode is just the beginning.
- **Digital is one service channel.** When planning inclusive services ensure that all channels & touchpoints apply an inclusive lens.
- **Designing systems that encompass the diversity "at the edges" will respond better to change and cost less in the long run.** Accommodation and accessibility gate-keeping are expensive, brittle and degrade quickly. 
- **You can have a greater impact by making systematic changes rather than individual changes, even often for the specific individual involved.** Personalization and choice is important, but creating complex work-arounds will always be less effective and more expensive. 
- **Most developers/designers underestimate the complexity of digital accessibility.** Many teams assume that they already know how to make pages accessible. 
- **Digital accessibility requires an ongoing commitment to education.** There is always new material being created to help practitioners learn how to be more inclusive. 
- **There is no checklist that you can follow that will make sure your digital tools inclusive.** Checklists can be useful as reminders, but too often in accessibility they become limiting in how people approach a complex problem.

**Also worth checking out:**
[Truths about digital accessibility](https://ericwbailey.design/writing/truths-about-digital-accessibility.html) by [Eric Bailey](https://ericwbailey.design/)
