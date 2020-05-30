# Travel Company Call Management Centre

## 1. Problem Definition
A major travel company performs sales of various holiday packages over calls in their call management centre (CMC). Relationship Managers (RM) are expected to provide information to customers about the variety and nature of the holidays packages they offer encouraging them to purchase it.

Currently, the inbound customers are connected to the fist available Relationship Manager (RM) at the CMC. This sometimes can cause issues as some of the new RM’s may not have enough information about the holiday package and can discourage the customer from purchasing a holiday package. During busy time, customers may be directed to an Interactive Voice Response resulting in low customer engagement and loss of opportunities. Customers can also hang up if they suffer from a long wait time in the queue.

RMs are looking to improve the call routing system and the call flow rate for both inbound and outbound calls to improve their service to their end and potential customers. 

## 2. Objectives
The objectives of the project is to:

+ Provide efficient call routing and dynamic call flow control allowing RMs to serve their end and potential customers.
+ Reduce wait times for inbound customers.
+ Improve customer experience by matching RMs that have the product knowledge required by the customers.
+ Improve the customer experience for repeat customers to encourage more purchases.

## 3. Stakeholders
The stakeholders involved in this project are:

+ Relationship Managers
+ Customers
+ Profiler Tool
+ Call Management Centre

## 4. Project Assumptions
1. The target list for RMs is updated regularly to maintain a certain amount of calls being made.
2. There is ‘hold’ music in place for customers in the queue.
3. Assuming that all the customers who call the company are willing to share information for the customer profile when they initially call such as answer privacy questions before beginning the conversation based off their profiles specific criteria; such as DOB, Full Name and Address.
4. The pre-loaded criteria is an automated pre-recorded questionnaire which greets the customer.
5. The system will make outbound calls using the target list to customers if the RM is in an idle state (not receiving incoming calls).
6. The RM skill score is updated at the end of every day.
7. RMs will write compulsory notes on the customers profile based on their conversation in order to have information for the next interaction with the customer.

## 5. Empathy Maps
#### 5.1 Company Empathy Map
**Think & Feel:**
+ Travel Company is struggling to provide the level of customer service which would attract and maintain customer loyalty.
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

**Say & Do:**
+ The company will attempt to develop a much more efficient system to combat the issues.
+ They will let the customers know that they are in the process of improving.
+ They will hire better relationship managers.
+ They will train their relationship managers so they can assist the customers better.

**Pain:**
+ The company is losing customers due to the poor customer services provided by the relationship managers.
+ They are unable to increase the sales of the packages because some relationship managers do not have enough knowledge about every package.
+ Competitors are taking advantage of the company’s loss of customers.

**Gain:**
+ The company will highly benefit from the score-based system where they can attend customers who are more likely to make purchases. This way they can retain a loyal customer base.
+ By allocating customers to the right relationship manager depending on their enquiry allows customers to receive the best customer service.
+ Relationship managers who are specialised in certain packages can use this as their advantage and increase sales.
+ The efficiency of outbound calls will be enhanced when the relationship manager is provided with a script and details from a database that familiarises them with customer interests.

#### 5.2 Customer Empathy Map
**Think & Feel:**
+ They know about a travel company who has several holiday packages that suit each person’s needs and price ranges.
+ They feel that the travel company has poor customer service, especially the call management centre.
+ The relationship manager does not have enough knowledge of the package which I am interested in.

**See:**
+ They see the offers which the travel company is offering.
+ They notice that their family and friends are moving away from this travel company because of customer service.
+ They see the online reviews and ratings of the company.

**Hear:**
+ They hear that during busy times their call takes much longer to be answered.
+ They hear the comments of their family and friends about the poor customer service this travel company offers.

**Say & Do:**
+ The customers will talk about their experience with the company to their family and friends.
+ They will write reviews of their experience online.
+ They might opt out of the company after facing unsatisfactory customers service. 

**Pain:**
+ Customers are linked to relationship managers who do not explain the different packages clearly.
+ When customers are linked to relationship managers who have no knowledge about certain packages which a customer is interested in.

**Gain:**
+ Customers are connected to a Relationship manager with a short waiting time.
+ Relationship managers have the knowledge about the package which a customer is inquiring for.
+ Customers are informed about all packages and promotions which the company is offering.

## 6. Brainstorming of Solution
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

## 7. Project Backlog
### 7.1 User Stories
**Customer User Stories**
+ **US-101:** As a customer, I want to be matched with a relationship manager who has the knowledge and experience of the holiday package I am looking for.
+ **US-102:** As a customer, I want to be able to speak with a relationship manager despite the busy times.
+ **US-103:** As a customer, I want to be notified about all the packages that are available and be informed of any promotional activities.
+ **US-104:** As a customer, I want the relationship manager to have a record of my previous conversation with the company, so I do not have to repeat my needs or concerns.
+ **US-105:** As a customer, I want to have a smooth experience from the customer service of the travel company.
+ **US-106:** As a customer, I want to be able to be connected with the same relationship manager for the ease of communication and understanding my perspective.
+ **US-107:** As a customer, I want to speak to a relationship manager who knows and understands my culture and social area.
+ **US-108:** As a customer, I want to receive a follow up call if there were any changes in my order or other promotional benefits are offered.
+ **US-109:** As a customer, I want to be able to connect with a Relationship manager who understands my language that I am comfortable in conversing in.

**RM User Stories**
+ **US-201:** As an RM, I want to be connected to customers who require my skills so I can help them to the best of my ability. 
+ **US-202:** As an RM, I want to be connected to customers with higher scores first to encourage quick and repeat sales. 
+ **US-203:** As an RM, I want to be asked accurate questions during my questionnaire so I am not matched with a customer who I am not able to help.
+ **US-204:** As an RM, I want the customer target list to be similar so I can use similar guidelines and scripts to perform the best service. 
+ **US-205:** As an RM, I would like to be given the repeat customers file to ensure a similar experience as their previous one and to encourage repeat sales. 
+ **US-206:** As an RM, I want customers to be informed of our holiday packages wherever possible to ensure a quicker sale.

### 7.2 Backlog
![Product Backlog](https://github.com/jyotsnaarora1/ISDM/blob/master/Diagrams/Product%20Backlog%20Final.png "Product Backlog")

## 8. Use Case Diagram
![Use Case Diagram](https://github.com/jyotsnaarora1/ISDM/blob/master/Diagrams/use%20case%20diagram.jpg "Use Case Diagram")

## 9. Use Case Narratives
#### 9.1 Use Case Name: Connect Customers to RM in busy times
|**Use Case ID**|UC102: Connect Customers to RM in busy times|
|:---|:---|
|**User Story**|US102: As a customer, I want to be able to speak with a relationship manager despite busy times.|
|**Goal**|Reduce the wait times when custoer contacts the relationship manager.|
|**Priority**|High|
|**Actors**|Primary- Customers <br> Secondary- Relationship Managers|
|**Pre-Conditions**|Customers would have had to wait until the next relationship manager is available. Even the customers who have purchased a product and are calling for an enquiry are placed in line with customers who are learning about different packages.|
|**Post-Conditions**|Customers are assignment to relationship managers according to a priority list. This speeds up the wait time and hence improving customer service.|
|**Trigger**|The travel company launches this automatic branch exchange system. A skill score is introduced to measure the likelihood of purchase by a given customer.|
|**Main Flow**|1.	The customer calls the travel company for the first time. <br><br> 2.	There is a wait time before being connected to the RM <br><br> 3.	After the call, the automatic system calculated a skill score based on the RM’s previous call duration and profile. <br><br> 4.	A score from 1-10 is calculated determining the likelihood to purchase a product is given to a customer according to a preloaded criterion. <br><br> 5.	Customers who repeat calls are given a high score. <br><br> 6.	Customers with higher score are marked as higher priority and served first.|
|**Exceptions**|1.	If the customer who had a higher score fails to make a purchase or is taking significantly longer in the call, their score will be deducted. <br><br> 2.	If a RM is receiving only customers with a much lower score it indicates that RM’s skills are below expectations. <br><br> 3.	There might be a delay during the times when some RM’s are only going to focus on outbound call list.|
|**Includes/Extends/Inherits**|**Includes:** <br> - Select Language <br> - Profiler Tool matches customer to RM <br><br> **Extends:** <br> - Wait time music is played <br><br> **Inherits:** <br> - N/A|
|**Supporting Information**|Customer service management centre has its own private automatic branch exchange to route the calls.|
|**Non-functional Requirements**|Call routing should not take more than 1 minute to connect.|

#### 9.2 Use Case Name: Access to Customer Files to RM
|**Use Case ID**|UC104: Access to Customer Files to RM|
|:---|:---|
|**User Story**|US104: As a customer, I want the relationship manager to have a record of my previous conversation with the company, so I do not have to repeat my needs or concerns.|
|**Goal**|To increase quality of customer service and make efficient calls.|
|**Priority**|High|
|**Actors**|Primary- Customers <br> Secondary- Relationship managers|
|**Pre-Conditions**|Customers are called by the relationship managers and are asked repetitive question. They are unaware that another RM has already contacted this customer and have asked the few standard questions.|
|**Post-Conditions**|Customers are called by the relationship manager who continues the call from what has happened previously.|
|**Trigger**|The company’s outbound calls develop a target list system that retrieves customer details from a database.|
|**Main Flow**|1.	The customer calls the company <br><br> 2. Customers are assigned to a relationship manager. <br><br> 3. The customer is put on hold while the connected RM reviews the script of their previous conversation. <br><br> 4. Relationship Manager enquires about issue discussed previously. <br><br> 5. Customer discusses their issues and concerns. <br><br> 6. This conversation is also recorded for future use.|
|**Exceptions**|1. If the customer calls for the first time, then the standard questions will be asked but that conversation will be recorded. <br><br> 2. If the customer wants to enquire about another package, then the conversation will start from the beginning.|
|**Includes/Extends/Inherits**|N/A|
|**Supporting Information**|The Relationship managers will have a list such as “potential customer, product proposed etc”.|
|**Non-functional Requirements**|The outbound call should no longer be than 5 minutes.|

#### 9.3 Use Case Name: Match Customers to RMs
|**Use Case ID**|UC201: Match Customers to RMs|
|:---|:---|
|**User Story**|US201: As an RM, I want to be connected to customers who require my skills so I can help them to the best of ability.|
|**Goal**|To connect customers with the right RMs.|
|**Priority**|High|
|**Actors**|Primary- Customers <br> Secondary- Relationship Managers|
|**Pre-Conditions**|Relationship Managers have filled out the questionnaire during the hiring process.|
|**Post-Conditions**|None|
|**Trigger**|Customers express interest during their pre-recorded questions which directs them to an RM.|
|**Main Flow**|1. The customer calls the call management centre and answers the pre-recorded questions which are used to give them a score. <br><br> 2. This score is then used to connect them with an RM.|
|**Exceptions**|1. The call is outbound.|
|**Includes/Extends/Inherits**|N/A|
|**Supporting Information**|N/A|
|**Non-functional Requirements**|N/A|

#### 9.4 Use Case Name: Capture RM Skills via Questionnaire
|**Use Case ID**|UC203: Capture RM Skills via Questionnaire|
|:---|:---|
|**User Story**|US203: As an RM, I want to be asked questions during my questionnaire, so I am not matched a customer who I am not able to help.|
|**Goal**|To accurately assess the RM's skills|
|**Priority**|High|
|**Actors**|Primary- Relationship Managers <br> Secondary- Travel Company|
|**Pre-Conditions**|Relationship Managers have been hired by the company.|
|**Post-Conditions**|None|
|**Trigger**|RMs have been hired by the travel company and have been given the questionnaire.|
|**Main Flow**|1. The RMs go through the hiring process. <br><br> 2. The RMs are successful in filling the role. <br><br> 3. The RMs have been given the questionnaire to be completed. <br><br> 4. The RMs complete the questionnaire honestly and do not embellish on their skills or interests.|
|**Exceptions**|1. The new RM is not successful in landing the role.|
|**Includes/Extends/Inherits**|N/A|
|**Supporting Information**|N/A|
|**Non-functional Requirements**|N/A| 

## 10. Activity Diagrams
#### 10.1 UC: Connect Customers to RM in busy times
![Activity Diagram 1](https://github.com/jyotsnaarora1/ISDM/blob/master/Diagrams/Activity%20Diagram%20Shreya%201.png "Activity Diagram 1")

#### 10.2 UC: Access to Customer Files to RM
![Activity Diagram 2](https://github.com/jyotsnaarora1/ISDM/blob/master/Diagrams/Activity%20diagram%20Shreya%202.png "Activity Diagram 2")

#### 10.3 UC: Match Customers to RM
![Activity Diagram 3](https://github.com/jyotsnaarora1/ISDM/blob/master/Diagrams/Activity%20diagram%20Sabrina%201.png "Activity Diagram 3")

#### 10.4 UC: Capture RM Skills via Questionnaire
![Activity Diagram 4](https://github.com/jyotsnaarora1/ISDM/blob/master/Diagrams/Activity%20diagram%20Sabrina%202.png "Activity Diagram 4")

## 11. Class Diagram
![Class Diagram](https://github.com/jyotsnaarora1/ISDM/blob/master/Class%20diagram%20with%20UML%20notation.jpeg "Class Diagram")

## 12. Collaborative Diagram
![Collaborative Diagram](https://github.com/jyotsnaarora1/ISDM/blob/master/Diagrams/collaborative%20diagram.png "Collaborative Diagram")

## 13. Competitive Advantages and Outcomes
Having a competitive advantage puts a firm in a favourable position over other businesses in the market. The travel company with an effective call management centre system will ensure that the company is reducing costs and able to carry out effective conversations to potentially convert every call into revenue. Companies are able to use their business systems to leverage the company against competitors as it can have positive effects on business functions.

#### 13.1 Reducing Costs
Reducing costs is crucial for any company. Reducing costs while still maintaining an appropriate operational performance is advantageous in a competitive market. When calls are managed through the CMC, the end customers and relationship managers are matched appropriately. This will allow for less wastage time, more sales and reducing operational costs such as time spent on phone without sales and phone bills. Another form of costs may be the excess of travel agency stores. With the adoption of an efficient CMC, companies are able to cut commercial rent costs, employees and other costs working in brick and mortar stores. A CMC will digitise the customer experience and further be able to increase the traffic as time spent with customers is reduced. For example, an RM in a call centre using a CMC will have more foot traffic than an employee in a traditional brick and mortar store resulting in greater traffic and increased conversions hence cutting costs whilst increasing profits for the firm.

#### 13.2 Customer loyalty and intimacy
Furthermore, the CMC will be able to match the customers wants and needs with the profile of the RM. Customers who are understood and being approached in a relatable matter are more likely to purchase products or in this case travel packages. The CMC will help the RMs learn about the customer upon opening an account or through the specified target list. Having RMs know crucial details about customers aid in engaging in conversation, building rapport, insights to wants, needs and pain points. After this, RMs are able to use empathy and critical problem-solving skills to convert the conversation into a sale. For example, a customer is calling in to find packages for flights and accommodations for Dubai and can only speak Arabic, the RM matched will be bilingual in Arabic and have proficient knowledge on Dubai. The overarching idea here is that a CMC can help gain insights on customers and match RMs based on similar criteria. This will boost customer experience and satisfaction, resulting in increased customer loyalty and intimacy, in turn putting the firm in a leading position. 

#### 13.3 Productivity and Efficiency
Essentially, the overarching goal of the new system will be to improve and maintain productivity and efficiency. The system route calls by skill, therefore, allows customers to be on the phone for a shorter period of time and overall gives the customer a more effective experience. When an agent is able to secure a sale at minimum touchpoints, the agent is being more efficient and productive than just simply routing the calls to correct people or searching for information to give the customer. The system can make outbound calls using the target list which routes call to the appropriate customer, this results in reduced idle times where the agent is not merely waiting for a call to come through, therefore the agent is more productive. By implementing these features into the system the company is leveraging its operations to remain and sustain a competitive advantage.

#### 13.4 Adverse Effects of Failure
There are various reasons for a system failing to be implemented, reasons such as having too many features and customizations, poor design process, interdependent teams and management not communicating enough or effectively. As a consequence of these factors, the adverse effects are substantial and may be difficult to recover from. Core adverse effects may include:

1. Large misuse of labour and capital causing issues with strategic financial goals.
2. Customer satisfaction and loyalty reduce, creating a bad reputation in customer service.
3. Loss of market share in the travel industry as competitors may have a more efficient and effective system.
4. Unable to create strong relationships with customers and acquire long term or repeat customers.
5. Employee turnover will start to occur if systems aren’t able to perform to their expectation or ‘get the job done’ well enough.
6. Can cause downtime; when the business has to pause all operations temporarily resulting in financial stress.


## 14. Agile Methodology - Scrum
The scrum methodology is the most suitable and appropriate methodology to be utilised in this project. Since the development of this plan is somewhat complicated and unpredictable, despite there being instructions there isn’t a fully defined process to how the project should be done as many changes can be made, or some requirements are not understood yet. Our team decided that there will be required deliverables; a backlog to be completed in increments. These increments will be developed or curated in the form of sprints with a specific time to have them completed by. When a deliverable is completed, such as diagrams section in the assignment, the sprint is then reviewed and the team then looks for ways we can improve.

The team will use GitHub to submit work in iterations based on the backlog which includes the necessary deliverables to be submitted into the final report. Github allows the team to have version control and records all changes made that we can revert back to, compare changes over and see who has modified the files. Through collaborating on GitHub, we were able to edit each others work and create more backlog deliverables for the next sprint.

