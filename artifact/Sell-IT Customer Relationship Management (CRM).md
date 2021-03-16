 # Sell-IT Customer Relationship Management (CRM)

  #### **Team Members:**

  *Celeste Gambardella* - *Mallory Bridge* - *Jacquelyn Leung* - *Giovanni Melchionne*

  #### **Professor:**

  *Samuel Malachowsky*

------

  # Artifact 1

  Overview, Organizational Structure, and Scope

  ## **Problem/Opportunity Statement**

  After failing to outperform competitors, Sell-IT, the producers of a Customer Relationship Management program, has hired a new CEO and development team. The team has been assigned to rewrite ~~create an updated Customer Relationship Management (CRM) program,~~ Sell-IT, to meet the market's expectations ~~cutting edge~~ and be easier to use. The CRM collects user data to maximize sales and customer retention. The team must have a modular design that can be expanded or updated over time to cater client's needs.

  ## **Goals & Project Benefits**

  ### Goals

  -   Outcompete similar CRM products

  -   Easier use~~r~~ of system

  -   Optimize workflows

  -   Modular d~~D~~esign

  -   Provide in-depth analysis of system functions (for business and clients)

  -   ~~Most~~ Minimal viable product to be marketed and deployed within one year ~~as soon as possible~~

  ### Benefits

  -   Increase clients' satisfaction

  -   Attract more high-profile clients

  -   Easy to maintain

  -   Do not force onto users features that users will not use

  -   Cater to each client\'s ~~the clients'~~ needs

  ## Stakeholders

  ### Internal

  -   CEO - Head of company, hired the team, sets goals for Sell-IT

  -   Team - Responsible for development of ~~makes~~ Sell-IT program

  -   ~~Sales & Marketing~~

  -   Marketing - Responsible for branding of Sell-IT, ensuring it looks modern and highlighting features of program

  -   Sales - ~~will market the product and increase revenue~~ Looks for customers for Sell-IT who will hopefully test and later buy the product. They figure out what the customers really want to see

  ### External

  -   Clients - ~~those using the product~~ Those who are going to buy and use the Sell-IT product

  -   Clients users - The people Sell-IT will be collecting data from

  -   CRM competitors - Other CRM companies in the market Sell-IT needs to compete with

  ## **Team & Organizational Structure**

  <img src="../models/Team and Organizational Structure v2.png" style="zoom:80%;" />

  ### Description

  -   CEO - The new head of the company. Oversees all departments in the company and sets the overall goal for the Sell-IT product.

  -   HR Department - Handles the Human Resources of the company. Currently only two people.

  -   Project Manager - Organizes and manages the development of the Sell-It Product. Communicates with other departments to keep transparency on the product high and relays messages from customers and other departments to the team

  -   Project Architect - Works closely with the development team on the actual creation of the product. They're job is to make the plan for how the project is structured and make sure the team follows it.

  -   Development Team - Make the actual the Sell-IT program. Currently only five people are employed by the company (not including the project manager and project architect). More developers will be hired as the project expands and eventually there may be multiple development teams.

  -   Sales - These are the people going out and bringing in customers to test and hopefully buy the Sell-IT product when it is ready. Only three people have been hired so far.

  -   Marketing - Creates the brand of Sell-IT. They are currently focused on revamping to the Sell-IT brand to be very modern and fresh. Two people have been hired here so far.

  ## **Scope**

  ### The Project MUST Include (~~MVP~~Minimal Viable Product)

  -   Must use built in integrations with existing enterprise systems

  -   Multiple ~~Many~~ workflows : ~~Data collection, analysis, marketing tasks~~

      -   Data collection : data from ad views & clicks, news mentions, social media views, and purchasing / pricing page views

      -   Data analysis : Perform and report analysis

      -   Marketing tasks : Create, revise, approve/reject, and disseminate marketing plans

  -   Manage customer and potential customer

  -   Track purchases of client products & services

  -   Organize elements \[customers, purchased products & services, potential customers\] into groups with personalized features : metadata filtering, analytics, events & message notification organized by group & element type

  -   Integrations with Salesforce, SharePoint, & Oracle Enterprise Resource Planning (ERP) \-- (HR) (Legacy)

  -   Single sign On

  -   Importing real-time data

  -   Must use built in integrations with existing enterprise systems

  ### The client would LIKE the Project to include

  -   Collecting data from website traffic, social media, subsystem to analyse performance, anticipated revenue, un-contracted customers

  -   Display collected data on dashboard

  -   Integration of emails

  -   Data collection from emails

  -   Optimize workflow for marketing, customer sign on, data retrieval, data analysis, reproting

  -   Automate workflow for client & clients' customers

  -   Find best customers for client through analysis

  ### The Project will NOT Include

  -   Hardset Features that does not allow a modular design

  -   AI Engine to analyze aggregated data

  -   Analysis of psychographic factors and demographics

  -   Proof of concept sign-off, planning, & tracking

  -   Free version of the software outside of testing/trial period

  -   Mobile version

  -   Different pay tiers outside of extending functionality (e.g. remove 10 user limit by paying more, you can have a reasonably large number of users from the get-go)

  -   Full built-in training seminar

------

  # Artifact 2

  #### Methodology Analysis, Risks, and Decision

------

  ## **Methodology Options**

  ### Plan-Driven

  #### *Team Software Process (TSP)*

  -   supports the development of industrial strength software through the use of team building, planning, and control.

  -   Strengths:

      -   Take ownership of their process and plans to make realistic commitments to the project

      -   Consistently using processes and methods they select in order to stay on track

      -   Allows team and project managers to have clear visibility of the progress as the team progresses week to week

  -   Weaknesses:

      -   Being artifact centric and high ceremony, or in other terms having many deliverables, meetings, etc.

      -   Does not do a great just as scaling for small team and shorter projects

  -   Meshing:

      -   Provides the organization needed for a project like this using artifacts

      -   Help by having a team leader or coach that will oversee the project from a managers perspective, which in the end is a great benefit to our stakeholders in the project

  -   Risk Register

| Name                                               | Description                                                  | Mitigation                                                   |
| -------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Overestimating time is takes to complete artifacts | Tech team overestimates their capabilities  for finishing their requirements. | After a project requirement does not meet a  set deadline switch the predetermined schedule  to allow for more leeway next time. |
| CRM security breach                                | There is a security breach in the CRM  platform and customers data is at risk. | Have a system that generates flags when unusual  activity occurs for a potential breach that notifies  all developers no matter the time of day. |
| The Team Leader or Coach leaves                    | The Team Leader or Coach has to leave  for an unknown amount of time due to  a family emergency. | The team comes together and discusses who they think  is the most qualified to take over as a Team  Leader/Coach based on experience and other team  members' feedback. |
| Spike in activity                                  | There is a spike in activity on the server  that cannot be handled causing the application  to slow down and impact customers. | Create a testing environment that tests the constraints  of the server and overestimate the number of active  users. Having a backup server to switch over to if one  ever fails. |

  #### *Feature Driven Design (FDD)*

  - Blends a number of industry-recognized best practices into a cohesive whole; to deliver tangible, working software repeatedly in a timely manner.

  - Strengths

    -   Useful for scaling a small agile development to a long-term project with a large team

    -   Allows for large projects to be broken down into more manageable chunks easily

    -   Provides a process flow designed to deliver working software in a timely manner

    -   Client-valued (feature) perspective

    -   Requires fewer meetings than Agile methodologies

  - Weaknesses

    -   Doesn't work well for smaller projects

    -   Places high dependence on a chief programmer (acts as a coordinator, lead designer, and mentor)

    -   Produces no client-facing documentation

  - Meshing

    -   FDD defines the following main roles:

        -   Project manager

        -   Chief architect

        -   Development manager

        -   Chier programmer

        -   Class owner

        -   Domain expert

    -   These roles would work fairly well with the company and team organizational structures laid out in Artifact 1.

  - Risk Register

    | Risk Name                                    | Description of Risk                                          | Mitigation                                                   |
    | -------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
    | Chief Programmer leaves                      | The Chief Programmer leaves the company during  the development of a product. | Have more than one person familiar with the work done by the Chief Programmer, acting as a backup. |
    | Management switches  existing project to FDD | FDD may not work well with existing systems  because there is no model to define the system. | Spend time to examine the existing system and create  a general model, if possible. Otherwise, the project  may need to be started over. |
    | Developer goes on vacation                   | A developer working on a class (part of a  feature being currently worked on) goes on  vacation. | Have all members of the feature teams be familiar  with the classes comprising their feature at a basic  level. |
    | Large feature is  introduced                 | A feature is added to the project scope that  cannot be completed in its entirety within  2 weeks. | Break down the feature into multiple smaller features.       |

  ### Agile

  #### *Scrum*

  - Scrum is an agile project management methodology or framework used primarily for software development projects with the goal of delivering new software capability every 2-4 weeks.

  - Strengths

    -   Allows for teams to develop deliverables quickly and efficiently

    -   Large projects divided into smaller sprints

    -   Works well for fast moving development projects

    -   Teams have clear visibility from scrum meetings

    -   Adopts feedback from project manager and stakeholders

    -   Allows for changes from feedback to be made easier

  - Weaknesses

    -   Lack of definite end date leads to scope creep

    -   Adopting scum to large teams can be difficult

    -   Needs experienced team members

    -   Quality hard to implement unless goes through aggressive testing process

    -   If team member leaves in middle of project, can cause a huge negative impact

  - Meshing

    -   This methodology allows for the stakeholders to be more involved in the development cycle and allows for high communication between the developers and stakeholders. There will be multiple smaller teams working on different aspects of the CRM to ensure an efficient pace on deliverables.

  - Risk Register

    | Risk Name                                                    | Description of Risk                                          | Single Mitigation                                            |
    | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
    | Experienced team member quits  to work at a FAANG company    | During the middle of developing a senior  architect quits the company to join Apple. | The team promotes a developer to become the senior  architect and hires a new developer to the team. |
    | Management onboards 10 new  development team members         | Management onboards 10 new team members that  are all going to be managed by the same  manager and work together on the CRM project. | The project manager splits up the new team members  into smaller teams to work on specific features of  the CRM. |
    | Management onboards 3 fresh  hires with no experience in  Agile development | Management hires 3 fresh graduates with no  previous experience of scrum or agile  development and has only worked on waterfall  teams. | The new hires are taught by current developers about  scrum and work together to ensure work is being  completed in two-week sprints. |
    | Team member refuses to attend  daily/weekly scrum meetings   | A developer refuses to attend daily stand-ups  and weekly scrum meetings to give his updates  and progress on his development. | The project manager speaks with the developer about  their performance and lack of attendance to get the  developer attending daily standups and scrum meetings. |

  #### *XP*

  - Dynamically changing software requirements

  - Risks caused by fixed time projects using new technology

  - Small, co-located extended development team

  - The technology you are using allows for automated unit and functional tests

  - Strengths

    -   Receive customer feedback at end of each release

    -   Able to mold the project exactly to what the customers want based on feedback

    -   Useful in small teams

    -   Acceptance tests are a necessary part of each story, guarantees functionality

    -   Daily meetings keep team members reliable

    -   Frequent code reviews ensure a complete understanding of code base throughout project

    -   Easily get a functioning product quickly

  - Weaknesses -

    -   Does not scale well with larger team

    -   Harder to integrate with legacy/ outside code

    -   Need constant customer communication

  - Meshing

    -   Does give a start up feel with small, close team

    -   Product needs customer feedback so it can fit their needs

    -   Can get a functioning product out the door fast

    | Risk Name                                                    | Description of Risk                                          | Mitigation                                                   |
    | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
    | Two team members are unagreeable  with each other and refuse to  work together. | Two of the members on the team are always  disagreeing with each other during the daily  meetings and refuse to code in pairs. This  greatly reduces the productivity of them in  a pair and the team as a whole because the  entire vibe is uncomfortable. | Hold an extensive behavioral interview before a  person is hired to make sure their personality  agrees with the team. |
    | There are too many customers to  meet with and cater to at one time. | Sell-IT is not a product used by just one  customer, but many and we are trying to cater  to all of their needs. Holding meetings and  getting feedback from all the customers each  release would take time out developing the  product and delay the project. | Start by working with only one or two customers  directly, and mostly rely on industry research.  Build up a customer base and the team learns to  manage a small number of customers well. |
    | Customer drops communication part  way through development feature | Halfway through the development process of a  modular feature a customer wanted, the customer  stops communicating with the company leading  developers lost for design of the module. | Thoroughly ask customers what the modular feature  they want would look like a complete project, so  that should the customer leave the module could be  fully developed and possibly sold to another customer. |
    | Feature does not integrate with  existing software as intended. | Customer tells us what legacy software they want  to integrate Sell-IT with and when the customer  is brought in for feedback, it works. However,  on deployment, it turns out the legacy software  the customer uses is not the same version,  breaking the feature. | Thoroughly inspect the customer’s environment before  starting development on the feature. |

  ## Selected Methodology: Feature Driven Development (FDD)

  We chose FDD because it most closely aligns with Sell-IT's ideal modular design. Each iteration of the process would allow the team to meet with customers to receive feedback, molding the product to exactly what the market wants. At the end of each iteration working software is delivered, so as soon as the minimal viable product is working, it is available to the customers. FDD also allows for the company to emulate startup culture while being an older company having to integrate with legacy software. Developers do not have to be meeting everyday and looking over each other\'s shoulder, but still can change their design based on changing requirements rather easily. FDD also makes expansion of the team easy; as the project grows and more customers are acquired the team will need to expand too.

  ### Potential Risks

| Risk Name                                                    | Description of Risk                                          | Probability | Impact    | Risk  Exposure | First Indicator                                              | Mitigation 1                                                 | Mitigation 2                                                 |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ----------- | --------- | -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Chief  Programmer  leaves                                    | The Chief Programmer  leaves the company  during the  development of a  product. | 20%         | 30  weeks | 6 weeks        | Showing signs of uninterest  in work being done, not  caring as much as before as  compared to when they were  first hired. | Have more than one person  familiar with  the work done  by the Chief  Programmer,  acting as a  backup. | The team comes together and  discusses who  they think is  the most qualified  to take over as  a new Chief  Programmer based  on experience and other team members'  feedback. |
| Management  switches existing  project to FDD                | FDD may not work well  with existing systems  because there is no  model to define the  system. | 5%          | 15  weeks | 0.75  weeks    | Management starts to  complain about the current  process taking place in terms of development. Mentioning  they want the large projects  to be broken down into more  manageable chunks. | Spend time to  examine the  existing system  and create a  general model,  if possible.  Otherwise the  project may need  to be started  over. | Making sure the  system’s code has  clear documentation  and well structured  to allow for  developmental  adaptability. |
| Developer goes on  vacation right  before critical  feature release | A developer working on  a class (part of a  feature being currently  worked on) goes on  vacation for two weeks | 40%         | 4  weeks  | 1.6  weeks     | Taking their time completing things as they know they are  leaving soon. | Have all members  of the feature  teams be familiar  with the classes  comprising their  feature at a basic  level. | Have all employees  give at least a  two-week notice for  vacations longer than  three days, and get it  approved by upper  management. |
| Large feature is  introduced                                 | A feature is added to  the project scope that  cannot be completed in  its entirety within 2  weeks. | 70%         | 3  weeks  | 2.1  weeks     | Stakeholders start to mention  that they are looking for a  new update to the CRM, that has  to be revolutionary. | Break down the  feature into  multiple smaller  features.    | Make sure management  is communicating with  the developers of the  stakeholders potential  requests so developers  can start thinking ahead if they decide to move  forward with the new  feature update. |
| Missing /Unclear  documentation                              | Poor Documentation leading  to long transitions for  new team members. | 80%         | 2  weeks  | 1.6  weeks     | New hires or new team members  unsure of the current state of  project, members taking a long  time to read over new code. | Updating Design  documentation after  each sprint of the  project. Conduct  code reviews for  other team member's  code. | Have code reviews take  place before anything  goes into production in  which all code has to have correct documentation. |
| Company has layoffs  and team is cut in  half                | There is a worldwide  pandemic and the company  is unable to pay for all of  the developers on the team  and needs to lay off a lot  of developers. The CRM team  is cut down to only have  four developers versus the  eight at the beginning of  the project. | 1%          | 52  weeks | 0.52  weeks    | Travel ban/flight prices decrease, Schools extending spring break, Online classes taking place,  Non-Essential businesses forced  to shut down | Have a risk  assessment plan in  place just in case  a major crisis occurs and a flexible budget to minimize the  number of employees  needing to be laid off. | Lots of hand sanitizer  and make sure everyone has at least one way to work  remotely. |
| There is a security  breach within the  system               | Mismanagement of security  keys leads to a large employee  data breach. | 75%         | 4  weeks  | 3 weeks        | Team notices loss of data, or other oddity                   | Make sure to hire an  employee with some  experience in security | Outsource security to another  company before the company  is developed enough to have  its own. |
| New CEO mismanages  the company                              | The new CEO is unable to manage  the company efficiently. The  CEO has extremely high  expectations of the new CRM  system and team. | 5%          | 20  weeks | 1 weeks        | CEO doesn’t listen to the  developers, struggling to handle  everything and manage the company,  Can’t communicate with other managers  properly. | Discuss with the CEO  about concerns with  his/her management | Discuss with Stakeholders and  investors about the CEO’s  mismanagement of the company  to find a new CEO. |
