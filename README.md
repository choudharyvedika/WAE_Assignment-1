<img width="3390" height="726" alt="Scenario2_Online_Purchase_Order_Processing" src="https://github.com/user-attachments/assets/13a6b9c1-4e5e-4bf4-8f22-6ba0c807e04e" /># Exercise 1 - BPMN Models

Vedika Choudhary

Here are my BPMN diagrams for the three exercise scenarios.

## 1. Employee Leave Approval

In this scenario, we model the leave application process. It begins with the employee submitting a request. Next, the HR system verifies the available leave balance. If there isn't enough balance, it sends an error notification and stops. If the balance is fine, the manager reviews the request. Depending on the manager's decision, the system either sends an approval message and updates the balance, or it just sends a rejection email. 

<img width="2502" height="726" alt="Scenario1_Employee_Leave_Approval" src="https://github.com/user-attachments/assets/93222693-bcfb-4a49-aa26-21881199bb09" />
This diagram maps out how an employee's time-off request is processed. It starts when the employee submits the request. The HR system first checks if they have enough leave balance. If they don't, it sends a notification and the process stops there. If they do have enough balance, the request goes to the manager. From there, if the manager approves, the system updates the balance and sends a confirmation. If the manager rejects it, it just sends a rejection notification instead.


## 2. Online Purchase Order Processing

This is a standard checkout process for an online store. After the customer places an order, the system checks the inventory. If the item is out of stock, the customer is alerted and the process terminates. Otherwise, it tries to process the payment. A failed payment stops everything and notifies the customer. A successful payment means the order gets confirmed, prepped, and shipped out, ending with a tracking/shipping confirmation.

<img width="3390" height="726" alt="Scenario2_Online_Purchase_Order_Processing" src="https://github.com/user-attachments/assets/8815625a-dc01-43c2-b32c-de45d56d286f" />
This model shows what happens when a customer places an order online. First, the system checks if the product is actually in stock. If it's out of stock, it notifies the customer and ends. If the product is available, it moves on to process the payment. If the payment fails, the customer gets an error notification and the process stops. If the payment is successful, the order is confirmed, prepared for shipment, and finally shipped out, ending with a shipping confirmation email to the customer.


## 3. IT Service Request

This diagram covers how IT support tickets are managed. An employee puts in a ticket, and the help desk logs it. They check the severity to decide who gets it: low severity goes to standard support, and high severity goes to a senior tech. Once assigned, the technician looks into it. If they can solve it themselves, they fix it. If not, they pass it on to an external service provider. In both cases, the ticket status gets updated and the employee is notified at the very end.

<img width="4242" height="630" alt="Scenario3_IT_Service_Request_Fixed" src="https://github.com/user-attachments/assets/f02d35ca-04bc-49ba-8752-1968c7b824f7" />
This outlines how an IT help desk handles support tickets. Once an employee submits a ticket, the help desk registers it and checks how severe the issue is. Low severity issues go to a regular support technician, while high severity ones go straight to a senior technician. The assigned technician investigates. If they can fix it internally, they do. If they can't, they escalate it to an outside service provider. Either way, it ends with the help desk updating the ticket status and letting the employee know it's resolved.

## Viewing the files

I uploaded these as .bpmn files. You can drag and drop them into Camunda Modeler or use bpmn.io to check out the visual flowcharts.
