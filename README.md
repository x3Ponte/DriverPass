# DriverPass System Design Portfolio

## Project Summary
The DriverPass project involved designing a comprehensive, web-based system for a local driving school owned by my client, Liam. The primary goal was to address a 65% failure rate on DMV driving tests by providing a structured, centralized platform for both online education and on the road training... I designed a system that manages student enrollment, tracks a fleet of 10 cars and their assigned drivers, maintains a secure audit trail of all reservations, and provides a live notification feed from the DMV to keep training materials current.

---

# Portfolio Reflection

## What I Did Well

I believe I was particularly successful in bridging the gap between high level business needs and also the technical architecture. Within Project One I identified critical nonfunctional requirements such as SSL/TLS encryption and role nased access control that laid the groundwork for a professional grade system. Then in Project Two I successfully translated these into a cloud native design using AWS/Azure infrastructure, ensuring the system is scalable, low-maintenance, and secure enough to handle sensitive financial data. My UML diagramming, specifically the Class Diagram that I created effectively modeled complex data relationships between students, instructors, and vehicles.

## Areas for Revision

If I were to revise these documents I would definitely spend more time refining the Sequence Diagrams to account for more complex edge cases. While my current design handles the ideal path of a successful lesson reservation, adding logic for payment failures, driver call-outs, or vehicle maintenance downtimes would make the system more realistic for everyday world operations. Additionally on top of that I would connect a few of the system objectives directly to specific stakeholder needs to strengthen the Business Background section.

## Interpreting User Needs

I interpreted the user’s needs by analyzing the specific frustrations of the stakeholders: Liam needed to work from home with Excel compatible reports, the Secretary needed a streamlined dashboard for scheduling, and the Drivers needed mobile access while on the road. Considering the user's needs is vital because as I noted in my project reflections, a system that is technically perfect but fails to accommodate the workflow of the people using it will ultimately be ignored or misused. For example implementing a mobile responsive interface was a direct response to the trainers need for field based performance logging.

## My Software Design Approach

My approach to software design is centered on utilizing UML modeling techniques including Use Case, Activity, and Sequence diagrams which I am able to visualize the logic and data flow before a single line of code is written. In the future I will continue to use these strategies to identify potential bottlenecks or security risks early in the SDLC. I also believe in the value of having separate teams for coding and testing to prevent "developer blindness" ensuring that the final product is as polished and error free as possible.
