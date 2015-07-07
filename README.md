
<a href="https://jigsaw.agilex-devcloud.com/jigsaw/#/" target="_blank">Click here for Working Prototype</a>

![alt tag](/process-documentation/agile-process-photos/response-images/proposal-header.png?raw=true)

# Request for Quotation 4QTFHS150004 Multiple Award Blanket Purchase Agreement for Agile Delivery Services (ADS I) 

## Introduction
Upon receipt of the RFQ, our team decomposed the requirements to understand the scope and resources needed for the effort. The following describes our approach and a bit of the history of this short lived project. We adapted a few agile techniques including Scrum, Kanban, and XP to support this effort.  The basic solution leverages the FDA Food Recall Enforcement Reports dataset. The vision of the prototype was an interactive web tool used to inform and educate consumers of food product recalls in an open or closed status.
![alt img](/process-documentation/agile-process-photos/design/high-level-overview.png)

## Team 
Within the first 24 hours, our full multidisciplinary team had been assembled, covering eight labor categories-Agile Coach, Visual Designer, Interaction Designer, Back End Developer, DevOps Engineer, Front End Developer, Product manager and Business Analyst.  Our Team’s corporate reach back helped to address surge and evolving needs by tapping 3,800 US based Agile resources, 1,800 scrum masters and 800 DevOps practitioners. Our proven experience executing Agile processes applied to over 1,000 Agile Scrum, Kanban & Lean projects, spanning Federal & commercial projects, provided the framework and tools to quickly define sprint zero needs, and enable the teams to begin sprinting.  Our team was empowered, self-organized and accountable for delivering value within each 'daily' sprint. Although not ideal or typical, our team did not have the luxury of each member dedicating 100% of their time to the RFQ.  Some roles were shared as team members came in and out. With this, it was imperative that the team openly communicate, share dependencies, maintain high visibility, and resolve impediments together.  

## Basic Agile Process 
Due to the short turn around we took a modified agile management approach based with Scrum and Kanban leveraging a <a href="https://github.com/AccentureFed/18FRFQ-Response/blob/master/process-documentation/agile-process-photos/process-photos/6.18.2015%2014.03%20-%20kanban%20board.jpg?raw=true" target="_blank">Physical task board</a>.  We had daily 'sprints' where we had a <a href="https://github.com/AccentureFed/18FRFQ-Response/blob/master/process-documentation/agile-process-photos/process-photos/6.24.2015%2009.33%20-%20standup.JPG?raw=true" target="_blank">Team stand-up</a> at 9:00am to understand where each team member was discussing what had been completed, what was to be worked on next, and any impediments that were of concern. This kept each task visible, lightweight, fast moving, and easy for all to see the current state of the project.  Each afternoon at 3:00pm, a sprint review was held where the team met to review progress made during the day and begin <a href="https://github.com/AccentureFed/18FRFQ-Response/blob/master/process-documentation/agile-process-photos/process-photos/2015-06-29%2009.18.32%20-%20work-in-progress.jpg?raw=true" target="_blank">planning</a> for the next day's sprint.  Once new stories, features, defects, functionality or change requests had been captured via stickies on the task-board, the product owner would prioritize the backlog based on user impact, time and value. This prioritization enabled the PO during our daily sprint planning to set the sprint goals, and allow the team to define how those goals would be implemented and what could be taken on during the sprint.

##Human Centered Design 
Human Centered Design stood as the backbone of our prototype. The end user desiring information pertinent to FDA Food Recalls, their needs, wants and desires drove a prototype tailored uniquely to them.  The following graphic and four steps, summarizes our basic approach. 

![alt tag](https://github.com/AccentureFed/18FRFQ-Response/blob/master/process-documentation/user-centric-design/design_evolution_images/UCD-Process-for-8F_2.jpg?raw=true>)

1. Understand the User Concept.  <a href="https://raw.githubusercontent.com/AccentureFed/18FRFQ-Response/master/process-documentation/user-centric-design/design_evolution_images/Persona1.jpg" target="_blank">Three personas</a> were developed to depict multiple user context for the prototype. 
 a. Ann Jordan - Mom searching for information for her children 
 b. Steven Jones - FDA Administrator monitoring site metrics and updating public information 
 c. Kathy Miller - Nutritionist looking for updates for her client base 
2. Understand the End User.  <a href=https://github.com/AccentureFed/18FRFQ-Response/blob/master/process-documentation/agile-process-photos/process-photos/features(added%206.23).png?raw=true" target="_blank">User Stories</a> were developed to depict multiple user context for the prototype with acceptance criteria.  We conducted an end-user survey at a local grocery store with four people matching our personas.  The personas described a need for the solution to be versatile, responsive, interactive and seamless to support a variety of end-user devices.  The UX designers focused on crafting each targeted device to provide optimal viewing and an interactive experience. Users are presented different layouts and content is adaptive to specific device types and its orientation. Mobile users will be presented with content and layout appropriate for limited real estate and quick access to information.    
3. Implement Rapid Prototyping.  Once our understanding evolved, rapid prototyping allowed for <a href="https://github.com/AccentureFed/18FRFQ-Response/blob/master/process-documentation/agile-process-photos/process-photos/wireframe%20(added%206.23).png?raw=true" target="_blank"> design iterations</a> and quick changes driven by continual feedback from the PO, usability and 508 testing, surveys and the team.  Stories were created and prioritized to ensure the most valued work was addressed based on iterative user feedback.  
4. Test and Evaluate.  Usability testing with both local and remote testers, along with remote observers using a COT usability tool, Morae,  allowed collaboration between test administrators and remote observers. 508 and accessibility testing using JAWS screen reader, the WAT toolbar and Keyboard Accessibility helped drive continuous improvement and enhance usability for disable users.   

## Design Style Guide 
Our user first focus leveraged pattern libraries (e.g. Font Awesome, Bootstrap) and a lightweight <a href="https://github.com/AccentureFed/18FRFQ-Response/blob/master/process-documentation/user-centric-design/jigsawStyleGuide.pdf" target="_blank">Style Guide</a> to drive the UX and design patterns to help maintain a consistent user experience among our designers and across multiple devices.  Bootstrap was used to develop our multi-device framework.  This encouraged collective code ownership, making it easier for our developers to work across the code base.  Developing and implementing Pattern libraries and UI libraries also allowed the team to have functionality and design elements that could be reused, and compliant with 508, keeping cost and time low.  

## Testing 
Backend unit testing utilized JUnit and Spock.  All components received unit tests, especially corner cases and null.  Unit tests were created simultaneously as code was developed. Unit tests (~30) were run on every Jenkins build (~125).  If defects were identified, the developer would resolve the defect within the same sprint.  

Usability testing drove multiple iterations of mock-ups and wire frame development. At the daily sprint review, designs were reviewed and feedback from the development team, product owner and stakeholders incorporated to the Kanban board. Within 48 hours of defining the prototype vision, a solid design was conceptualized in an interactive, clickable wireframe. In 72 hours, usability tests were created and <a href="https://vimeo.com/132240054" target="_blank">testing</a> was administered with real users against that design with individuals who matched the personas. Local and remote testing was conducted and based on feedback received, designs were refined.  

<a href="https://vimeo.com/132240055" target="_blank">508 testing</a> was done utilizing JAWS, the Wat toolbar and Keyboard Accessibility. Results highlighted that areas of our implemented design were not conducive to individuals with disabilities. These tests allowed our team to implement design changes, ensuring our prototype was accessible for all users.    

## Technology Choices 
Open source technologies allowed our team to drive efficiencies (cost, time, reliability, value).  Our prototype and the underlying <a href="https://github.com/AccentureFed/18FRFQ-Response/tree/master/process-documentation/evidence/Attachment_E_Evidence_Q" target="_blank">51 technologies</a> used to create and run the prototype are openly licensed and free of charge.
![alt tag](/process-documentation/agile-process-photos/design/tool-diagram.png)

## Development 
The team both developed and consumed a RESTfull API <a href="https://github.com/AccentureFed/18FRFQ-Response/blob/master/jigsaw-rest-api.md" target="_blank">(details here)</a> Development dependencies across layers of the architecture was mitigated by first creating a shell end-point to begin  integration with.  Developer review and interaction with the shell end-points, resulted in feedback and changes.  Ultimately, five final APIs were established with appropriate unit tests and committed for build.  One way our API's enriched the data set was by normalizing State recall information embedded in free text.  A specific data element was added to easily represent the formal list of States associated with the recall.  

The team utilized Github for configuration management. Three backend developers each worked part time, to ensure continuity and CM best practices. They used Github time stamps and the check-in, check-out feature to work on the most recent code sources.  The team built in the ability to trace any warfile back to the Jenkins Job/Build and commit reference in Github. This allowed tractability and a testing reference for each build.  

## Deployment 
The team choose to deploy our software into an Amazon Web Service EC2 instance for production running the Docker daemon. The application was deployed inside of a Docker container, from a Docker image running Ubuntu 14.04, Tomcat 8.0.2.3 and Java 8. Our Docker container running on the Docker hypervisor, is our operating system-level virtualization. We chose Docker because it is free, easy to use, and provides application portability and infrastructure flexibility.

![alt tag](/process-documentation/agile-process-photos/design/deploy-stack.png)


## Continuous Monitoring 
To provide continuous monitoring the team developed an administrative view to a dynamic page. This url is accessible at the bottom left of the homepage titled "metrics" or by clicking <a href="https://jigsaw.agilex-devcloud.com/jigsaw/#/appMetrics" target="_blank">here</a> (admin/afs18F).  This monitoring app is just a start to provide insight into the activity of the application and to monitor for intrusions, denial of service attacks, etc.  Since we chose to use only publicly available data there is no need to store any end-user sensitive information.  These choices were intentional to lower the security profile.  Clearly a full security assessment is in order as this solution moves to production.  

## Conclusion 
All of our evidence is in this Git repository, and can be leveraged as needed.  The <a href="https://github.com/AccentureFed/18FRFQ-Response/blob/master/process-documentation/evidence/README.md" target="_blank">evidence Summary</a> README.md provides a replica of our Attachment_E submission and additional supporting documentation.

