# Travel Company Call Management Centre

## Problem Definition
A major travel company performs sales of various holiday packages over calls in their call management centre (CMC). Relationship Managers (RM) are expected to provide information to customers about the variety and nature of the holidays packages they offer encouraging them to purchase it.

Currently, the inbound customers are connected to the fist available Relationship Manager (RM) at the CMC. This sometimes can cause issues as some of the new RM’s may not have enough information about the holiday package and can discourage the customer from purchasing a holiday package. During busy time, customers may be directed to an Interactive Voice Response resulting in low customer engagement and loss of opportunities. Customers can also hang up if they suffer from a long wait time in the queue.

RMs are looking to improve the call routing system and the call flow rate for both inbound and outbound calls to improve their service to their end and potential customers. 

## Objectives
The objectives of the project is to:

+ Provide efficient call routing and dynamic call flow control allowing RMs to serve their end and potential customers.
+ Reduce wait times for inbound customers.
+ Improve customer experience by matching RMs that have the product knowledge required by the customers.
+ Improve the customer experience for repeat customers to encourage more purchases.

## Stakeholders
The stakeholders involved in this project are:

+ Relationship Managers
+ Customers
+ Profiler Tool
+ Call Management Centre

## Project Assumptions
## Empathy Maps

**Company Empathy Map** <br>
**Think & Feel:**
+ They know about a travel company who has several holiday packages that suit each person’s needs and budgets.
+ Travel Company is struggling to provide the level of customer service which would attract and maintain a customer base.
+ They are unable to serve all the customers in the busy times.
+ Relationship Manager does not have enough knowledge about specific packages to help customers.

**See:**
+ They see reviews of the company online and see the ratings it has.
+ They see that Relationship managers are not able to provide quality customer service.
+ The packages are not marketed and described efficiently to the customer hence losing market share.
+ The current system in place is complicated and is restricting the company’s relationship managers to provide the best customer service.

**Hear:**
+ They hear that during busy times their call takes much longer to be answered.
+ They hear complaints of customers that suggest that relationship managers are unable to answer customer’s questions.
+ They hear competitors gaining more customer base and market share than them.

**Pain:**
+ The company is losing customers due to the poor customer services provided by the relationship managers.
+ They are unable to increase the sales of the packages because some relationship managers do not have enough knowledge about every package.
+ Competitors are taking advantage of the company’s loss of customers.

**Gain:**
+ The company will highly benefit from the score-based system where they can attend customers who are more likely to make purchases. This way they can retain a loyal customer base.
+ By allocating customers to the right relationship manager depending on their enquiry allows customers to receive the best customer service.
+ Relationship managers who are specialised in certain packages can use this as their advantage and increase sales.
+ The efficiency of outbound calls will be enhanced when the relationship manager is provided with a script and details from a database that familiarises them with customer interests.

**Customer Empathy Map**<br>
**Think & Feel:**
+ They know about a travel company who has several holiday packages that suit each person’s needs and budgets.
+ They feel that the travel company has poor customer service, especially the call management centre.
+ The relationship manager does not have enough knowledge of the package which I am interested in.

**See:**
+ They see the offers which the travel company is offering.
+ They notice that their family and friends are moving away from this travel company because of customer service.
+ They see reviews of the company online and see the ratings it has.

**Hear:**
+ They hear that during busy times their call takes much longer to be answered.
+ They hear the comments of their family and friends about the poor customer service this travel company offers.

**Pain:**
+ Customers are linked to relationship managers who do not explain the different packages clearly.
+ When customers are linked to relationship managers who have no knowledge about certain packages which a customer is interested in.

**Gain:**
+ Customers are connected to a Relationship manager with a short waiting time.
+ Relationship managers have the knowledge about the package which a customer is inquiring for.
+ Customers are informed about all packages and promotions which the company is offering.

## Brainstorming of Solution
+ Match end-customers with well informed RMs with appropriate knowledge about the destination and its tradition.
+ Create a questionnaire for the initial phase of RM profiles, the questionnaire will assist and work in collaboration with the matcher tool, to effectively match the RM with the customer. This means that there must be a singular questionnaire to Build RM profile based on the criteria in the questions.
+ System adjusts RM profiles constantly based on RMs performance in selling. The system will adapt and change when the RM is upskilled and constantly reaching KPIs.
+ A database will store a target list for outbound calls, each customer is in the form of <potential customer, product proposed>.
+ The target list will use the skill matcher to match the appropriate RM. Potentially have a target list go into a ‘RMs target list’ file for each individual RM. This collated target list will be provided to the RM everyday with new a new list.
+ Create a preloaded criteria for inbound customers. There must be a certain number of questions or criteria that the system will present to the customer to answer using their keypad to assist in routing the call.
+ Calculate skill score based on RM’s previous call duration and profile.
+ Customers with high scores get more priority.
+ RMs can alternate between inbound and outbound calls by selecting whether they want to receive calls or make calls. The system will generate the target list automatically to make calls once outbound calls are selected.
+ RMs can put themselves on ‘NOT ready’ option to stop the inflow of calls if they need to follow up with their existing customers who they have dealt with before.
+ When customers are routed to an unsuitable RM they are able to transfer directly to the suitable RM so the customer doesn't have to wait in the queue again. RM will know they are unsuitable due to the customer profile.
+ RMs are able to put their customers on hold to investigate complex situations further, the system will play music when ‘hold status’ is active. RMs can also put themselves on MUTE if they need to do quick investigating.
+ Customers can choose their language before the call is routed to ensure optimum selectability and routing to RMS.

## Project Backlog
### User Stories
**Customer User Stories**
+ As a customer, I want to be matched with a relationship manager who has the knowledge and experience of the holiday package I am looking for.
+ As a customer, I want to be able to speak with a relationship manager despite the busy times.
+ As a customer, I want to be notified about all the packages that are available and be informed of any promotional activities.
+ As a customer, I want the relationship manager to have a record of my previous conversation with the company, so I do not have to repeat my needs or concerns.
+ As a customer, I want to have a smooth experience from the customer service of the travel company.
+ As a customer, I want to be able to be connected with the same relationship manager for the ease of communication and understanding my perspective.
+ As a customer, I want to speak to a relationship manager who knows and understands my culture and social area.
+ As a customer, I want to receive a follow up call if there were any changes in my order or other promotional benefits are offered.
+ As a customer, I want to be able to connect with a Relationship manager who understands my language that I am comfortable in conversing in.

**RM User Stories**
+ As an RM, I want to be connected to customers who require my skills so I can help them to the best of my ability. 
+ As an RM, I want to be connected to customers with higher scores first to encourage quick and repeat sales. 
+ As an RM, I want to be asked accurate questions during my questionnaire so I am not matched with a customer who I am not able to help.
+ As an RM, I want the customer target list to be similar so I can use similar guidelines and scripts to perform the best service. 
+ As an RM, I would like to be given the repeat customers file to ensure a similar experience as their previous one and to encourage repeat sales. 
+ As an RM, I want customers to be informed of our holiday packages wherever possible to ensure a quicker sale.

### Backlog
![Product Backlog](https://github.com/jyotsnaarora1/ISDM/blob/master/Diagrams/Product%20Backlog%20Final.png "Product Backlog")

## Use Case Diagram
## Use Case Narratives
### Use Case Narrative 1
### Use Case Narrative 2
### Use Case Narrative 3
### Use Case Narrative 4
## Activity Diagrams
### Activity Diagram 1
### Activity Diagram 2
### Activity Diagram 3
### Activity Diagram 4
## Class Diagram
## Collaborative Diagram
## Competitive Advantage
Having a competitive advantage puts a firm in a favourable position over other businesses in the market. The travel company with an effective call management centre system will ensure that the company is reducing costs and able to carry out effective conversations to potentially convert every call into revenue. Companies are able to use their business systems to leverage the company against competitors as it can have positive effects on business functions.

**Reducing Costs**

Reducing costs is crucial for any company. Reducing costs while still maintaining an appropriate operational performance is advantageous in a competitive market. When calls are managed through the CMC, the end customers and relationship managers are matched appropriately. This will allow for less wastage time, more sales and reducing operational costs such as time spent on phone without sales and phone bills. Another form of costs may be the excess of travel agency stores. With the adoption of an efficient CMC, companies are able to cut commercial rent costs, employees and other costs working in brick and mortar stores. A CMC will digitise the customer experience and further be able to increase the traffic as time spent with customers is reduced. For example, an RM in a call centre using a CMC will have more foot traffic than an employee in a traditional brick and mortar store resulting in greater traffic and increased conversions hence cutting costs whilst increasing profits for the firm.

**Customer loyalty and intimacy**

Furthermore, the CMC will be able to match the customers wants and needs with the profile of the RM. Customers who are understood and being approached in a relatable matter are more likely to purchase products or in this case travel packages. The CMC will help the RMs learn about the customer upon opening an account or through the specified target list. Having RMs know crucial details about customers aid in engaging in conversation, building rapport, insights to wants, needs and pain points. After this, RMs are able to use empathy and critical problem-solving skills to convert the conversation into a sale. For example, a customer is calling in to find packages for flights and accommodations for Dubai and can only speak Arabic, the RM matched will be bilingual in Arabic and have proficient knowledge on Dubai. The overarching idea here is that a CMC can help gain insights on customers and match RMs based on similar criteria. This will boost customer experience and satisfaction, resulting in increased customer loyalty and intimacy, in turn putting the firm in a leading position. 

**Productivity and Efficiency**

Essentially, the overarching goal of the new system will be to improve and maintain productivity and efficiency. The system route calls by skill, therefore, allows customers to be on the phone for a shorter period of time and overall gives the customer a more effective experience. When an agent is able to secure a sale at minimum touchpoints, the agent is being more efficient and productive than just simply routing the calls to correct people or searching for information to give the customer. The system can make outbound calls using the target list which routes call to the appropriate customer, this results in reduced idle times where the agent is not merely waiting for a call to come through, therefore the agent is more productive. By implementing these features into the system the company is leveraging its operations to remain and sustain a competitive advantage.

## Agile Methodology - Scrum
The scrum methodology is the most suitable and appropriate methodology to be utilised in this project. Since the development of this plan is somewhat complicated and unpredictable, despite there being instructions there isn’t a fully defined process to how the project should be done as many changes can be made, or some requirements are not understood yet. Our team decided that there will be required deliverables; a backlog to be completed in increments. These increments will be developed or curated in the form of sprints with a specific time to have them completed by. When a deliverable is completed, such as diagrams section in the assignment, the sprint is then reviewed and the team then looks for ways we can improve.

The team will use GitHub to submit work in iterations based on the backlog which includes the necessary deliverables to be submitted into the final report. Github allows the team to have version control and records all changes made that we can revert back to, compare changes over and see who has modified the files. Through collaborating on GitHub, we were able to edit each others work and create more backlog deliverables for the next sprint.

