# ISDM Report

[Click here for our group presentation.](https://www.youtube.com/watch?v=lMPybOUR97U&feature=youtu.be&fbclid=IwAR3WWlQorupc2ormCRzPkDWHOOksrgVc_5wQ5GvEDiYFjjWMu4bqh0NYp5Q)

---

## 1. Problem Definition & Project Objectives

The travel company currently faces difficulties in dealing with differing varieties of holiday packages and the methods used to match clients with RM. Thus, it is necessary to improve the process of matching customers to the best suited RM based on specific factors of both the customer and the RM by creating a more automated system that can more efficiently match customers according to RM performance and product knowledge.

In doing so, RM can reduce complications associated with differing holiday packages and reduce costs by decreasing the lead times and servicing times on the phones. Additionally, by suiting a customer to the most appropriate RM, the travel company will likely see an increase in customer turn over due to their needs being better met, which can ultimately have a positive effect on revenue.

Another issue for the travel company is long lead times during busy periods in which customers get frustrated and hang up the phone. A system to manage long waiting times for customers will to be implemented.

The project aims to develop an improved information system for a travel company which enables a more productive and efficient Call Management System (CMC) which will allow the Relationship Managers (RM) to improve client servicing.

---

## 2. Stakeholders

Travel Company Owner/CEO

- Interest: High
- Influence: High

Development Team

- Interest: High
- Influence: High

Travel Company Hiring Manager

- Interest: High
- Influence: Medium

Other Travel Company Employees

- Interest: High
- Influence: Low

Customers

- Interest: High
- Influence: Low

---

## Empathy Maps

<img src="Empathy map CEO.png"
style="float: none; margin-left: 10px; margin-right: 10px; margin-top: 10px; margin-bottom: 10px; border-style: groove;"/>

---

<img src="Empathy map customer.png"
style="float: none; margin-left: 10px; margin-right: 10px; margin-top: 10px; margin-bottom: 10px; border-style: groove;"/>

---

<img src="Empathy map RM.png"
style="float: none; margin-left: 10px; margin-right: 10px; margin-top: 10px; margin-bottom: 10px; border-style: groove;"/>

---

## POV Statements

### Owner/CEO

- I want to increase performance and sales
- I want to improve the customer's experiences
- The transition from system to system should be as seamless as possible
- I want improved monitoring of RMs performance

### Customers

- I prefer to speak with an RM that understands and has a lot of knowledge about the destination I want to travel to
- I prefer to spend as little amount of time as possible waiting on the phone
- I would prefer to speak my native language with the RM
- I need my details to be saved securely to speed up the booking process next time
- I prefer to speak to an RM that I know

### Relationship Managers

- I want to speak to returning customer as much as possible since I have built rapport with them
- I want to speak to customers who are interested in destinations that I am very knowledgeable about
- I don't like having to redirect customers to other RMs if I can't answer their questions
- I would prefer to view a quick summary of a customer before speaking to them
- I want the ability to leave feedback and rate customers

---

## How We Might Statements

- How might we assign customers to the most suited RM?
- How might we minimize customer waiting time?
- How might we ensure customer & RM details are secure?
- How might we prioritize customers who are more likely to purchase?
- How might we allow RMs to view and edit customer profiles?

---

## 3. Approach

The solution must divert time invested away from the RM, without causing additional stresses to the customers in order to retain the business. For this to be successful - the approach must use the data collected about both the customers and the relationship managers to streamline the process, rather than relying on automated survey systems on the customer's end.

This narrows the possible solutions down. The system will have to be automated to manage the large quantity of both customers and staff. Therefore, the system will connect customer with RM's based on one of the following criteria:

1. Predefined attributes given to each party upon contact with the company, based on evaluation, that match the RM's skills with the customer's requirements.
2. Attributes that are self identified by the RM and customer, that establish the RM's personal understanding of their skill set, and the customer's personal requirements in a relationship manager.

Unfortunately these values are static, modifiable only through manual changes. It will therefore require a more dynamic process afterwards to ensure the relevancy of the data. This could be achieved via a dynamic system: a process that evaluates the interactions RM's have with the customers based on the outcome - did the customer buy a product? Did they send a complaint? And uses this information to create a portfolio for each RM and customer with information about positive and negative outcomes. This portfolio can link RM's and customers with each other based on the previous experiences they had with similar RM's or customers.

---

## 4. Agile Methodology

A system development project cycle can be an unpredictable and challenging process where adaptation may be required to keep up with developing requirements and technology. To allow for more flexibility, we decided to utilize the Scrum framework. Scrum is an agile project management methodology which is characterized by consistent meetings (sprints), regular feedback and collaboration between team members.

The main scrum activity employed during this project were sprints. Sprints are allotted time periods where the development team takes on more specific, focused tasks and delivers them by the end of the time frame. It is very beneficial to a team to divide up a sizable project into smaller segments with regular interaction between members. In this case, we decided that sprint lengths of 3 to 5 days were appropriate.

To prepare for a sprint, we would meet and discuss what we would like to complete for this sprint and how we plan to do so. During the sprints we would continue to communicate as much as possible to ensure we could properly respond to any changes to the sprint plan. This amount of communication allowed us to keep each other ‘in the loop’ with each other's progress whilst being able to focus on our own tasks.

---

## 5. Assumptions

To understand where improvements can be made by the new proposed system, first we must understand exactly how the existing CMC works. By analysing the existing system we will know its flaws and strengths which allows us to determine what may be kept and integrated into the proposed system. In order to do so, we had to make a number of assumptions about the CMC, the RMs and Inbound & Outbound Calls. They are as follows:

CMC system

- The major travel company’s existing CMC isn’t sufficient enough to respond to the customer demand
- Inbound calls were being placed into a queue waiting to be rerouted by a receptionist to the first available RM.
- The best suited RM were not being assigned to the correct calls.
- The existing profiler tool will be sufficient enough to support the new proposed system in creating customer profiles.

RM

- RMs sales would improve if correctly assigned to customers
- All current RMs have a customized profile
- RMs are more likely to successfully sell to returning customers

Inbound Calls

- Customers kept waiting for too long will hang up
- Inbound calls that are more likely to become end-customers are not currently being prioritized by the CRC
- Customer details are being stored in the database after an inbound call
  
Outbound Calls

- Potential customer information being pulled from the database are previously inbound calls

---

## 6. Products & Models

Activity Diagram

The activity diagram goes into more detail by illustrating all the activities taking place. The system targets a potential customer and matches them with a suitable relationship manager. The customer details and the script are then presented to the relationship manager who then makes the sale. However, if the customer calls first the subsequent steps are shown in the activity diagram starting from the customer dialling the call centre to them speaking with the relationship manager or hanging up due to the wait which is where the flow is terminated.  

<img src="Screen Shot 2020-05-22 at 3.05.36 pm.png"
style="float: none; margin-left: 10px; margin-right: 10px; margin-top: 10px; margin-bottom: 10px; border-style: solid;"/>

---

Use Case Diagram

The use case diagram describes the business goal that the system is supposed to satisfy and acts as a starting point to highlight the user requirements. This diagram shows how the relationship manager, who is one of the actors calls the customer and makes sales by reading the script generated by the system. He then proceeds to finalise the sale.In some cases, the customer might ring the call centre first at which point they will be directed to a relationship manager if they are available. The relationship manager will then use the guidelines generated to make and finalise the sale. However, during busy periods the customer’s call will be directed to an interactive voice response. The customer will have the option of waiting for their turn to speak to the relationship manager or they can choose to hang up.

<img src="Screen Shot 2020-05-22 at 12.28.12 pm.png"
style="float: none; margin-left: 10px; margin-right: 10px; margin-top: 10px; margin-bottom: 10px; border-style: solid;"/>

---

Class Diagram

The class diagram then shows the structure of the system. The many to many relationships between the customer and relationship manager indicates that relationship managers and customers can change for each call. Each relationship manager has to fill out a questionnaire. This questionnaire is also filled out by many relationship managers. Each customer has a profile created by the profiler tool. A relationship manager can sell many products and the same product can be sold by many relationship manager.

<img src="Screen Shot 2020-05-26 at 9.12.53 pm.png"
style="float: none; margin-left: 10px; margin-right: 10px; margin-top: 10px; margin-bottom: 10px; border-style: solid;"/>

---

Collaboration Diagram

The collaboration diagram then captures the interaction that represents the flow of message. The customer is matched with the relationship manager after they were selected from the target list. If it is true, then the relationship manager calls the customer and then proceeds to sell the product and finalises the sale. Otherwise, the customer calls the CMC first. The call is then directed and a score is calculated for the customer. If the score is high the call is answered straight away, if not they are further directed to an integrated voice response. The customer is then matched with a relationship manager. If they find a match the call is answered, if not they have to wait some more or they can choose to hang up.

<img src="Screen Shot 2020-05-28 at 4.18.12 pm.png"
style="float: none; margin-left: 10px; margin-right: 10px; margin-top: 10px; margin-bottom: 10px; border-style: solid;"/>

---

## 7. Advantages and Disadvantages

The automatic adjustment of customer requirements, and the lack of automated surveys ensures the customer is treated to the best service at little to no expense on their part. This provides an important connection between the company and its customers.

While the company's objective is to help customers more efficiently, this also helps the customer get what they want faster, building even stronger relationships between the two.

The reliance on the system to create matches between RMs and customers creates an unfortunate situation in which any failure in the new system could be critical for business operations. The documentation it creates however, regarding RM and customer portfolios, can allow for functional connections to be made during shutdown, but this is not a perfect solution. Similarly, if data is lost or destroyed the system will not function correctly.

---

## Conclusion

This system will make it more efficient for RMs while also making the customer's journey with the company that much easier. While it does have the same flaws any system does, it is very much worth working around them to use the system, as it can definitely and substantially benefit the company.
