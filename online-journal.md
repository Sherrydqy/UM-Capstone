# UM Capstone - TabSanity | Online Journal #
*By Qinyu Ding*

---
##### Nov 2nd, 2020 - Nov 28th, 2020
## Final Usability Testing and Refinement
I ran the final usability test with 6 participants, using an interactive, high-fi prototype of the latest design. The test followed the same process as the previous one. The overall feedback were much more positive than previous ones:
+ **[DISLIKE]** Users were confused about the section "Archived" saying that they had no idea what could possibly in there. The term does not make sense to them.
+ **[DISLIKE]** There is no way to search content across all the sections. *"What if I do not remember where I put it?"*
+ **[LIKE]** The layout of the sidebar is really clear and intuitive.
+ **[LIKE]** Different sections of workspace really helps with further organization of the tabs.

Based on the findings, I added a search box to the sidebar allowing for searches across all sections. The Archived section was divided into Archived Workspace and Saved Tabs, which were merged respectively into the Workspace and the Tabs section.

![Design Iteration Final](/Assets/Final Design1.png)
![Design Iteration Final](/Assets/Final Design2.png)
![Design Iteration Final](/Assets/Final Design3.png)
![Design Iteration Final](/Assets/Final Design4.png)
---
##### Oct 15th, 2020 - Nov 1st, 2020
## Final Design and Prototype
I looked up the feasibility and design guidelines for Google Chrome extensions. Finally I decided to use sidebar as a replacement for the top bars in my previous designs. I divide the sidebar into 4 sections:
+ **Workspace** - tasks that users are working on
+ **Tabs** - current open tabs categorized by automatically generated keywords based on the word frequency in titles of all webpages
+ **Windows** - current open windows with tags to show the keywords of the webpages within each of them
+ **Archived** - everything that were saved and closed, including archived tabs and archived workspace
![Design Iteration3](/Assets/3rd design.png)

---
##### Apr 1st, 2020 - Apr 26th, 2020
## Improvements of the second version(For the presentation in May)
One of the biggest issue of current design is the feasibility. Technically, it is not possible to modify Chrome by adding another section to the top of it. Due the presentation required in early May, I modified the design based on the findings of the previous usability research and leave the feasibility issue to the Fall Semester.

In this iteration, I added a pop-window to remind people to organize their tabs when the amount of open tabs reach a certain number. Also I added an animation before showing users the automatically generated topics to explain where these come from. In order for the audience to understand the prototype, I spent time learning to use Principle to animate all interactions.

![Design Iteration2-21](/Assets/Design2-21.png)
![Design Iteration2-22](/Assets/Design2-22.png)
![Design Iteration2-23](/Assets/Design2-23.png)
![Design Iteration2-24](/Assets/Design2-24.png)


---
##### Mar 16th, 2020 - Mar 29th, 2020
## Usability Testing II
With a high-fi and interactive prototype, I conducted a formative usability test with another 5 participants. In the test, the participants were asked to finish 3 tasks using the prototype, including starting a new search, starting another search, and finding a visited tab.
### Usability Test Task Scenarios
+ **Start a new search** - You want to learn more about Coronavirus. Use the browser to search for the following information:
  + Coronavirus symptoms
  + How to protect from coronavirus
+ **Start another search** - As time goes, there are more and more tabs open since you have done searches on lots of things, such as Coronavirus symptoms, its protection measure, eating habits huskies, oscar awards of 2020, and information about high blood pressure. Use our browser extension to organize them.
+ **Find a visited tab** - You are doing searches on blood pressure diet when your parents suddenly texted you about Coronavirus common symptoms. You remembered you just saw it somewhere. Try to find the website where you learned about the coronavirus symptoms.


### Usability Test Findings
The findings of the usability test are presented as follows:
+ **[DISLIKE]** The design of all the “Searched for” and topic names is not intuitive, in terms of 1)which tabs are covered by a ”Searched for” keywords, and 2)presenting the relations between the ”Searched for” keyword and the topic of the current tab
+ **[DISLIKE]** The sudden appearance of the pop-up window with categorized topics is confusing – users don’t understand how they got here.
+ **[DISLIKE]** Lack of affordance showing a tab or a “Searched for” section is able to be moved around. Users don’t realize that these are just suggested categorizations which can be manually rearranged.
+ **[DISLIKE]** Having to bookmark a page to save it in TabSanity requires unnecessary extra effort.
+ **[LIKE]** Users like this overview showing the search context of different topics as they are clear and informative.


---
##### Mar 2nd, 2020 - Mar 16th, 2020
## Design Iteration II
Based on the feedback of the usability tests, I removed the reminder function, changed the requirement of predefining a task before browsing and replaced it with an algorithm that can suggest categorizations based on the keywords used for searches. A pop-up window will show up to present the suggested categories of currently-open tabs. Users can modify and rearrange it before finalizing the sorting. After confirmation, all tabs will be separated into different tasks. The tasks will be displayed in the form of a folder at the top of the browser.
![Design Iteration1A](/Assets/Design2A.png)
![Design Iteration1B](/Assets/Design2B.png)


---
##### Feb 19th, 2020 - Mar 1st, 2020
## Usability Testing I

Since I'm still at the design exploration phase, I started the first round of usability testing using the low-fi design. I ran a walkthrough with 5 participants to collect their opinions of the design idea. The findings of the usability test are presented as follows:
+ **[DISLIKE]** Having to put a specific topic before starting a search is annoying. Most of the time, users don’t know what exactly they are looking at first since their initial searches are general exploration.
+ **[DISLIKE]** The width of the topic on the left-side bar is too short to read.
+ **[DISLIKE]** The reminder system is adding more to users’ mental effort. It makes them feel like it they’ve got more on their plate.
+ **[LIKE]** Most users showed interest in the keywords captured on the top, saying they would help them to recall the context to some extent.


---
##### Feb 1st, 2020 - Feb 18th, 2020
## Design Iteration I

According to my interviews, I mapped out an As-is journey map to help me visualize the current process of web-based academic research and the pin points during the process:

![Journey Map](/Assets/JourneyMap.png)
The journey map describes four main insights of user needs:
+ When multitasking, users need to have a general idea of what he/she has been working on and how far did he/she go in order to coordinate between different tasks of varied topics.
+ When they are concentrating on the current topic,  users do not want to be distracted by others.
+ Users need to document their search context which includes search flows (e.g.,where they started, where they have been which are useful, and where they stopped) and the search results (e.g., keywords search result and the linked webpages)
+ Users need to eliminate the feeling of losing the information if they close the tab. Users need to quickly find the relevant information they saw earlier about a topic because they can only think of certain keywords and it takes forever to go through all their notes one by one.

Based on the findings, I came up with the first design solution. The main idea is to provide context for users while they are doing web-based searches. The interviews indicated that the context of different tabs helped trigger users' memories when multitasking and kept them from getting lost in overflowing tabs. It includes features as follows:
+ Capture and display keywords used for searching in order to keep track of the search context
+ Present an overview of the progress of different topic searches.
+ Allow for concentration on the current topic.
+ Add the a webpage to the calendar as a reminder for later review.
![Design Iteration1A](/Assets/Design1A.png)
![Design Iteration1B](/Assets/Design1B.png)
![Design Iteration1C](/Assets/Design1C.png)
---
##### Jan 22nd, 2020 - Jan 31st, 2020
## Analysis of User Interviews

I coded all 10 interviews in NVivo and came up with the insights. From my interviews, I found that:

![Insight 1](/Assets/insights6.png)

![Insight 2](/Assets/insights5.png)

![Insight 3](/Assets/insights4.png)

![Insight 4](/Assets/insights3.png)

![Insight 5](/Assets/insights2.png)

![Insight 6](/Assets/insights1.png)
---
##### Jan 15th, 2020 - Jan 21st, 2020
## User Interviews (2/2)

### Finished the rest 5 interviews.

This week, I finished my last 5 interviews in the U.S.. Ready for analyzing the interviews!
---
##### Dec 1st, 2019 - Jan 14th, 2020
## User Interviews (1/2)

### Discussion Guide
Before conducting my interviews, I thought about what I wanted to get out of this interview and how I was going to get there: 

> CENTRAL QUESTIONS: 
> - What kind of relationships of content between tabs help users recall the context of a previous web-based academic search?
> - What kind of visual elements do they use to develop the relationships?
>
> TYPE OF INTERVIEW: Semi-structure
>
> DATA ANALYSIS TYPE: Thematic analysis

Then I began thinking about the questions that can help me get the answers to the central questions. Because this was the first time writing interview questions, I had a really hard time finding out what kind of questions to ask. My first version of the discussion guide totally failed in my pilot test. After several iterations, I finally found out what questions to ask that can actually help me to get the answers to the central questions. The same with the demographic survey.

​How I got to the final version was that I started thinking about in order to get the answers to my central questions, what kind of information do I need to get to that point. Therefore, I divided my interview questions into different sections asking about:
+ Types of Research
+ Tab Using Behavior
+ Types of the Relationships between tabs
+ Visual Hints used to identify the Relationships
+ Previous Experience with Tab Management Tools

Turns out this new version actually went out really well! During the winter break, I finished 5 interviews in China.

---

##### Nov 16th, 2019 - Nov. 30th, 2019
## Competitive Analysis  

### Design Precedents
I did a competitive analysis of 6 typical design precedents of my product.

There are two types of design precedents:

1. Manually group the tabs by themes
    *E.g.: Toby, Graphitabs, Tabs Outlier, Workona, Feedly, Pocket, Instapaper, Kurator, etc.*
2. Manually organize the content from tabs
    *E.g.: Evernote, Diigo, Microsoft Word/Google Doc, etc.*

![feature audit](/Assets/featureAudit.png)


Based on the result of the feature audit, I identified the biggest gap of the current products which is **a lack of interpretation of the relations through graphical overviews**.

From all findings above, I came up with my design questions for this project:
+ How might we better communicate the relationships of content between tabs to help recall the context of the previous search of a topic?
+ How might we make the process of search-based multitasking more effective?
---


##### Oct. 26th, 2019 - Nov. 15th, 2019
## Secondary Research  

### Motivation
This idea comes from my own story. I have been suffering from having too many tabs open on my browser for a long time. I cannot either finish reading a tab given the limited amount of time or feel comfortable closing any tabs. I always have a fear of losing the information I have read. Therefore, I decided to come up with a solution to it.

### Issues with Tabs
I did some searches about the tab using history. 

Providing the world of information at the fingertip, the internet has become an essential part of our life. In 2018, the average hours that Americans spent on the internet per week was 22.5 hours. Studies showed the use of internet covered a wide range of purposes and have replaced some traditional information-gathering methods, for example, information retrieval for academic research. Over two-thirds of internet users who are students go online at least once daily to get information for academic-related activities. Due to the increasing complexity of the information environment, people were found to be engaged in multitasking on web-based search such as searching on multiple topics simultaneously while switching back and forth. The provision of browser tabs has made multitasking search easier by increasing the volume of parallel browsing, the most common browsing behavior today.

However, tabs can not optimize web-based search because they fail to address the issue of multitasking:

* Multitasking during web search demands constant context switching at the cost of increased cognitive load. Limited working memory limits the retention of the relationships between information retrieved while switching from one topic to the next.

* The affordance offered by tabs does not positively increase association and relationships of content between related tabs.

This project aims to investigate how users develop associations of content between tabs while doing web-based search and to identify factors that hinder this process in context switching. The final goal is to develop a tab management tool that optimizes the process to increase the effectiveness of parallel browsing in web-based search.

### Coming up with a research question
> What design elements improve the communication of relationships between tabs for web-based research?

### Insights from the secondary research
I looked up the previous work of tab using behavior and best practice for improving the effectiveness of information gathering when using tabs on web-based search. The insights from the existing research include:

* Multitasking information behavior ranges over multiple topics 
* A coherent series of tasks for coordination during multitasking information behavior include:  seeking, searching, interactive browsing and retrieving, and constructing information.
* Signaling the rhetorical relations between web pages helps with comprehension, reading times’ efficiency and navigation of web search.
* Graphical overview interface supported flexible navigation across web pages 
* Graphical-overview supports the interpretation of inter-textual relations between web pages

Design implications informed by the insights above are as follows:

Web features should allow users to...
* access, refine, and use results from a previous search within the confines of a session across multiple topics.
* add notes to different or related search topics
* easily track multiple queries concurrently on different or related topics 
* rearrange multiple queries
* easily generate and compare relevance judgments from different or related searches
* create clusters of retrieved information related to different topics.
* tag rhetorical relations between pages
* better interpret the relations through graphical overviews

​
