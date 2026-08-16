# Exercise 1 - BPMN Models

Vedika Choudhary

Here are my BPMN diagrams for the three exercise scenarios.

## 1. Employee Leave Approval

In this scenario, we model the leave application process. It begins with the employee submitting a request. Next, the HR system verifies the available leave balance. If there isn't enough balance, it sends an error notification and stops. If the balance is fine, the manager reviews the request. Depending on the manager's decision, the system either sends an approval message and updates the balance, or it just sends a rejection email. 

## 2. Online Purchase Order Processing

This is a standard checkout process for an online store. After the customer places an order, the system checks the inventory. If the item is out of stock, the customer is alerted and the process terminates. Otherwise, it tries to process the payment. A failed payment stops everything and notifies the customer. A successful payment means the order gets confirmed, prepped, and shipped out, ending with a tracking/shipping confirmation.

## 3. IT Service Request

This diagram covers how IT support tickets are managed. An employee puts in a ticket, and the help desk logs it. They check the severity to decide who gets it: low severity goes to standard support, and high severity goes to a senior tech. Once assigned, the technician looks into it. If they can solve it themselves, they fix it. If not, they pass it on to an external service provider. In both cases, the ticket status gets updated and the employee is notified at the very end.

## Viewing the files

I uploaded these as .bpmn files. You can drag and drop them into Camunda Modeler or use bpmn.io to check out the visual flowcharts.