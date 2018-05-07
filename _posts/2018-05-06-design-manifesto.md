---
title: Design Manifesto
---

Before embarking on this semester-long journey into design thinking, I’d admittedly given very little thought to how designs come together and what the design process is really like. In my mind, it was as simple as thinking about a problem, coming up with a solution, and then implementing that solution. Now that I’ve come out the other end, there are five main guiding principles that I’ve carried with me throughout the design process that have come to define my understanding of what “design thinking” really is, or at least what it ought to include. They include: user understanding, defining and communicating the problem and the solution, learning to critique and learning to take criticism, designing for accessibility, and considering the ethics of design processes and solutions. 

## User Understanding

<figure>
<img src=”../img/design-process.jpg” /> 
<figcaption> The Human-Centered Design Process. Adapted from: *Norman (2013). The design of everyday things: Revised and expanded edition. Basic Books (AZ).* </figcaption>
</figure>

The design process always starts with keeping an open mind, understanding your target users, and understanding the problem you’re designing for. As the above diagram suggests, understanding the problem is at the heart of the human-centered design process. This means conducting thorough user research, and not letting our assumptions and preconceived ideas of what the problem *should* be cloud our understanding of what the problem that we want to design for actually *is*. 

There is certainly no shortage of techniques available for user research, and they include fly-on-the-wall observation, journaling, interviews, contextual inquiries, and many more. For our project, we used a combination of semi-structured interviews and contextual inquiries. We interviewed a diverse group of museum-goers, as our target audience was not a specific demographic, but simply anyone interested in attending museums for the purpose of learning about art. We wanted to understand why people visited museums in the first place, and what they wanted to get out of going to museums, so that we could construct a design that aids them in getting the most out of their art museum experience.

We decided to begin each interview with a semi-structured interview format as outlined in “Interaction Design” by Rogers, Sharpe, and Preece (p. 229-232), as they allow for both closed and open questions. Closed questions would allow us to compare our different interview participants along general baselines, such as how often they visited museums and with whom, and how often they learned about art outside museums. Open questions allowed us to probe deeper into the “why” of their interactions with art, and understand what they might get out of using an extra art education tool while navigating museum. 

Examples of questions we asked our participants at the beginning of each interview included:

> How often do you visit art museums?
> Why do you visit art museums?
> Do you usually visit art museums with others, or do you go alone sometimes?
> Do you ever research artworks or artists outside museums?

After the initial questions, we conducted contextual inquiries as we observed and communicated with our participants as they walked through the museum. We asked our users to verbalize their thoughts to each other and to us to get a sense of their interactions with artworks. We employed the four basic techniques of contextual inquiries, as outlined in “Contextual Design” by Beyer and Holtzblatt(?):

1. Context: interviewing people at an art museum
2. Partnership: constantly communicating with the participants to understand their thought process
3. Interpretation: checking our interpretations of the participants’ thoughts throughout
4. Focus: shifting attention always back to the art, but allowing deviations from our expectations of their opinions

This format allowed us to find concrete insights about the specific ways potential users would want to interact with artworks, and avoid generalizations. It allowed us to discover whether discussions would be useful and what kinds of discussions users might want to have with each other about art. Examples of questions we asked during the contextual inquiry portions of our interviews included:

> What do you think of this piece? (Referring to some artwork in the museum)
> What else would you want to know about this piece?
> How are you choosing which exhibit to look at next?

In the end, we learned a lot about what users might want to see in an app that supports art education. From our interviews with people outside formal art education backgrounds, we learned that discussion is at the heart of how they interact with art. We also learned that some people prefer to only read about specific aspects of an artworks’ background information, as too much information could distract them from developing their own personal interpretations. From our interviews with Art history professors, we learned that allowing for experienced professionals to guide discussions might be helpful in preventing discussions from devolving into mere speculation. Formal discussions about the entire scope of our results from interviews can be found [here](http://stephanieliu.me/hciproject/design-research-results-and-themes/). 

## Defining and Communicating The Problem

The next key piece of the design process was effectively defining and communicating the problem we were designing for. We needed to put ourselves in our user’s shoes, and understand exactly what the problem was that we were trying to solve, and what a solution to that problem might look like. 

Starting with our user research, we constructed an affinity diagram to understand the common links that connected the participants in our interviews. The affinity diagram approach, although helpful, was admittedly challenging with fewer than 10 interviewees. In fact, Beyer & Holtzblatt in Contextual Design note that they usually build affinity diagrams after interviewing 15-20 users at four to six different work sites. Nevertheless, building the affinity from the bottom up and finding common themes and structures out of the individual notes still helped us organize the notes we collected from the interviews. The affinity diagram we built is shown below.

<figure>
<img src=”../img/affinity-diagram.jpg” style=”max-width: 100%;”> 
<figcaption>The finished affinity diagram for our project </figcaption>
</figure>

Examples of high-level themes that we uncovered through affinity diagramming included:
Learning is a goal when visiting art museums
Learning through art is a social experience
Users want to customize and tailor their learning to fit their needs.

The next step in defining the problem we wanted to solve was carrying out a task analysis to narrow down the scope of our app’s functionality, and explain how our app might replace or support existing tasks users performed at museums. We first listed out the range of existing tasks and the possible future tasks we could support ([found here](http://stephanieliu.me/hciproject/Supported-Tasks/)). Once we did that, we drilled down on which two tasks would be the main ones we’d want to focus on. 

We decided our two main tasks would be:
Providing background information about artworks
Supporting online discussions about artworks

However, one-word sentences about future supported tasks are ultimately vague and uninteresting. An important component of design is being able to communicate the effectiveness of the design and convincing stakeholders and participants that the problem is compelling and a worthwhile pursuit. 

In that end, we found scenarios and storyboards to be effective tools that would serve as more compelling communication devices. 

Scenarios allow us to tell compelling narratives about a design; they describe a design within the context of a user and their actions, and allow us to bring stakeholders into the design thinking process. As Rogers, Sharpe, & Preece note in *Interaction Design*, ”telling stories is a natural way for people to explain what they are doing or how they achieve something.” Here is the scenario we used to describe how a user might use our app to discuss an artwork through an online discussion:

> Bob has recently visited a museum and become entranced with a Jackson Pollock work. He is waiting for the bus, and thinks back to this piece. He decides he wants to discuss this particular artwork with others, so he pulls up the Art for All app and navigates to the discussion section under this artwork profile page. He asks some probing questions, and finds that another student, Sarah, is also online at the same time and wants to talk about this particular work. They discuss their interpretations, and in the end Bob feels like he has a better understanding of the artwork.

Clearly, this scenario paints a much more vivid picture of what our design intends to support and how our design would be used be a real user. It concentrates on human activity, and describes the purpose of our app in the context of why people do the things they do and what they are trying to achieve.

In a similar vein, storyboards serve as short graphical depictions of narratives that envision future scenarios of how a design interaction might serve user’s needs. As Truong et al. note in *Storyboarding: an empirical determination of best practices and effective guidelines*, “storyboards must demonstrate not only the details of a specific interface but also higher level concepts surrounding user motivation and emotion during system use.” As such, we wanted our storyboards to convey an added layer of emotion and interaction between the user and the goals they were achieving with the app. The storyboard we constructed to convey the use of our design in finding background information is shown below.

<figure>
<img src=”../img/storyboard-1.jpg” style=”max-width: 100%;”> 
<figcaption>Storyboard laying out how users would use our app to find background information about artworks</figcaption>
</figure>

We made sure to keep the number of frames between 3 and 6 to keep them understandable and straight to the point. We included a bit of text to guide the viewer’s understanding, and tried to convey emotion within the stick-figures in our frames. These ideas followed guidelines also supported by Truong et al. 

## Critiquing

Once the focus of our design process had been fully laid out, the process of designing and evaluating the product began. In design thinking, this is always a very iterative process.

That meant that our design had to be constantly evaluated by participants and critiqued by our peers in order to become the better and better at every stage. Although this concept was a bit daunting at first (you mean everyone is going to be telling us how much our design sucks?), we quickly learned that getting constant feedback from our peers would be the best way to use our collective knowledge as a class to our advantage. Karen Cheng’s guide on “How to Survive a Critique” was a helpful reference point here for those of us new to receiving critiques. We learned over the course of the semester how to not get too attached to our initial designs and how to not get defensive when bombarded with questions about it.

The first critique we did in class involved the logo design. We paired up with another team and used the I like/I wish/What if method from the Stanford design school and the “Hamburger approach” (also outlined in Cheng’s article) to constructively analyze each other’s initial logos. Even for something as small as a logo design, the critiquing approach helped us improve on our design a lot, as you can see below.

<figure>
<img src=”../img/logo-process.jpg” style=”max-width: 100%;”> 
<figcaption>Iterations of our logo design, after receiving critiques from our peers. A common critique of our first logo was that it was a bit bland and didn’t effectively communicate that the rectangles were supposed to be artwork frames. </figcaption>
</figure>

We also spent some time in class critiquing each other’s projects, long before we had established a concrete design. This allowed us to get feedback on the overarching goals of our project, and understand what steps we needed to take in moving forward on implementing the design. We again paired up with another team in this endeavor, and the main takeaways from this preliminary critique included:
We needed to find a way to merge the learning aspects and discussing aspects of our design together to make the purpose of our app more clear and cohesive instead of distinct elements
Discussions needed to be seen as open dialogs to prevent the app itself from becoming pretentious (as art museums often seem to be for people)

Once we began to think about how we might want to design the actual app, we started with sketches and paper prototypes. These kinds of “low-fidelity” prototypes allowed us to make and remake our design as many times as necessary without getting too attached to a particular design. As Buxton explains so eloquently in *Sketching User Experiences*: “The role of design is to get the right design. The role of usability engineering is to get the design right.”

Before putting the design in front of any potential users, we first got critiques from our peers. These critiques followed a heuristic evaluation process using Nielsen’s Usability Heuristics, found in *Usability Engineering*. We got a lot of helpful insight from this process, and realized (as we often do in design) that our assumptions had played a large role in the inefficiency of our initial design.

For example, we faultily assumed that users would understand the camera symbol was for scanning QR codes, when that was not at all clear! We added explicit text to the favorite button, and provided a one-time tutorial on the use of the QR code function to alleviate these concerns, as shown below.

<figure>
<img src=”../img/paper-prototype-search.jpg” style=””> 
<figcaption>Initial search screen on our paper prototype </figcaption>
</figure>

<figure>
<img src=”../img/digf-qr.jpg” style=””> 
<figcaption>Final digital mock-up of search by QR process, with added one-time documentation about how the QR functionality works.</figcaption>
</figure>

Receiving constructive criticism from our peers thus defined our iterative approach to “getting the design right” throughout the design process, and allowed us to make our design better at every stage. 

## Accessibility

In the latter stages of our project, it became clear that we would need to begin to address accessibility concerns as the design started coming together. As Smyk notes in [Design With Accessibility in Mind: The POUR Methodology](https://theblog.adobe.com/design-with-accessibility-in-mind-the-pour-methodology/):

> “Exclusion happens when we do not think about all the possible ways the product will be used and by whom.” 

As a tool that is meant to make art more accessible to a wide audience, we definitely didn’t want to accidentally exclude large groups from using it.

To address the needs of users on the autistic spectrum, we decided to break down subsections by only showing small paragraphs at a time and providing a “read more” button so that it wouldn’t overwhelm the user. 

<figure>
<img src=”../img/takenaga-analysis”> 
<figcaption> Analysis section of artwork is broken down into small paragraphs at a time </figcaption>
</figure>

We also added more descriptive texts to buttons (which were confusing to even those users not on the autistic spectrum), and kept simple and consistent layouts, which also made our app more accessible to users with low vision. 

To address the needs of users with physical or motor disabilities, we had to increase the size of our buttons. To address the needs of users with low vision, we had to also increase the font size of our initial digital mock-up by quite a bit. 

<figure>
<img src=”../img/buttonswitch.jpg”> 
<figcaption> Increasing button sizes and font sizes </figcaption>
</figure>

All these modifications helped make the app more accessible to a wider audience.

Finally, we still needed to address users who are blind. This would prove to be a difficult challenge for us, because up until then we had been focusing entirely on visual art (which is often what is put up in museums). However, from further research we found that the art world itself has made several advances in making art accessible to the blind. The Louvre, the Guggenheim, and the Metropolitan Museum of Art in NY are great examples of museums that have established tactile tours of their galleries(cite https://mashable.com/2016/12/29/art-accessibility-blind-low-vision/#mc68orKeKmqJ ). Although we did not have time to incorporate new features in our app at the time, we do now know that our app can be made much more accessible by providing information about which museums provide these kinds of tours, and supporting them.

In that same vein, our project website could be made more accessible by providing tags for users participating in discussions who have experienced the art through tactile senses. That way, users could sift through discussions if they want to hear specifically what others think about artwork they experienced through touch. If we were to actually code up the app, we would also employ some of the techniques suggested “Guidelines for accessible and usable web sites: Observing users who work with screen readers” by Theofanos and Redish, such as providing a “Skip to Main Content” link at the top of artwork profiles so that blind users do not have to hear the tabs (About, Learn More, and Discussion) every single time and including alt tags for all images. 

## Ethics

Following good principles of ethics was an ongoing concern of ours throughout the design process. The stipulations of the ["General Moral Imperatives"](https://www.acm.org/about-acm/acm-code-of-ethics-and-professional-conduct) from the ACM Code of Ethics and Professional Conduct served as a good baseline for understanding our role and duties as designers of a new application.

The first code of ethics we learned to keep an eye out for was citing and giving proper credit for use of others’ intellectual property. This involved citing any and all images and resources we used throughout the creation process, including those used on our project site. 

Additionally, we did not want to make our participants uncomfortable in any way during the interview, contextual inquiry, and usability testing studies. We made sure to provide them guidelines ahead of time that would stipulate what kind of recording we would use (usually note-taking and occasionally audio recording), and explicitly stated that they could end the interview whenever they pleased if they felt uncomfortable at any point. 

We further made sure to keep all of our participants’ identities anonymous throughout when we reported the results from our studies, and remove any personally identifiable information.

Lastly, we allowed participants to keep certain information or discussions confidential if they did not want their comments to be made public. 

Regarding the actual implementation of our app, we would stipulate that the design would ask for very little personal information about the users. Users would be allowed to remain entirely anonymous to alleviate any potential of publicizing personally identifiable information. 

However, the main caveat to this is that we would have to develop solutions to prevent harassment and intolerant or hate speech. We want to make sure that our app does not pose any harm to users in any way. 

One of the main ways we could combat hate speech would be to involve museum staff and curators in the process, and allow them to moderate and flag abusive content. If online harassment became a real issue, moderators would be given total freedom to pre-screen discussions about particularly controversial pieces; in other words, we would allow them to screen all potential posts before they were posted, rather than after the fact. 

Moderators would also be given full discretion to block certain accounts from posting if they found repeated offenses. Users would also be allowed to flag any content they thought was unacceptable, and moderators could then pull up all flagged content and choose to allow or disallow certain posts. We would also allow artists to be given full discretion to remove certain content, remove discussions, or simply not publicize their content on our platform, if they so choose. 

As an undeniable newcomer in the design world, I’ve found that these principles have shaped my understanding of design thinking throughout this process. They are the methods, processes, and skills I plan to take with me in any future endeavor that relies on finding solutions to problems. 

