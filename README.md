### Usecases

##### Create a life group
-	Add members to the group (hard coded for now)
    - Name
    - Date of birth
    - email


##### Send notifications
- check each member's date of birth (the notification will be only sent one time per person)
- send an email to each member of the group
- generate link
- if  dob == current_date + seven_days -> send email

##### Create a message card
- the message card is empty
- everyone can see the other messages but can only edit own message


##### View messages 
- Omit empty messages
- Check empty messages with admin code (random alphanumeric)
- return all cards
- return non empty cards

##### Update message
-	The user adds text messages and a picture. 

##### Print a message card
  - print non empty cards




# User Stories and Sprint Plan  

---

## **Sprint 1: Basic Group Creation and Notifications**  

### **Frontend Tasks**    
1. Design a rough UI template for message cards
2. Design a UI for message cards with figma
3. Design email tempalte for notification

### **Backend Tasks**  
1. Hardcode life group and member details.  
2. Implement logic to check members’ dates of birth and identify if a notification needs to be sent.  
3. Generate unique notification links for each email.  
4. Integrate with an email service provider to send notifications.  

---

## **Sprint 2: Message Card Functionality**  

### **Frontend Tasks**  
1. Design a UI for a form to creating a message card.  
2. Display all message cards in a list or grid format.  
3. Add a filter to omit empty message cards in the view.  
4. Create an admin-only view to display empty message cards upon entering a code.  

### **Backend Tasks**  
1. Create an API endpoint to handle creating and saving message cards.  
2. Implement logic to filter non-empty message cards.  
3. Add admin verification logic to access empty cards.  
4. Create an API endpoint to retrieve all or non-empty message cards.  

---

## **Sprint 3: Advanced Message Features and Printing**  

### **Frontend Tasks**  
1. Add functionality for users to edit their own message cards.  
2. Implement a file upload feature for adding pictures to message cards.  
3. Display text and pictures in the message cards.  
4. Create a printable view for non-empty message cards.  

### **Backend Tasks**  
1. Create an API endpoint to allow users to edit their message cards.  
2. Add support for uploading and storing images associated with message cards.  
3. Update the API endpoint to handle both text and picture updates.  
4. Add logic to return non-empty message cards for printing.  

---

## **Sprint 4: Notifications and System Enhancements**  

### **Frontend Tasks**  
1. Add visual feedback on the notification sent to members (e.g., a status indicator).  
2. Create a dashboard or panel for admins to monitor birthday notifications.  
3. Add user-friendly error messages for notification-related issues.  

### **Backend Tasks**  
1. Implement logic to ensure each member receives only one birthday notification.  
2. Refine the notification-sending process to check for birthdays 7 days in advance.  
3. Perform comprehensive testing of the system’s functionality and fix any bugs.  

---

## **Task Summary: Frontend vs Backend**  

| Sprint  | Frontend Tasks                                            | Backend Tasks                                               |
|---------|-----------------------------------------------------------|------------------------------------------------------------|
| Sprint 1 | UI for life group creation, member profile view          | APIs for saving members, sending notifications, links      |
| Sprint 2 | Message card UI, filter for empty cards, admin-only view | APIs for message cards, filtering, and admin access        |
| Sprint 3 | Edit message UI, image upload, printable view            | APIs for message editing, image handling, non-empty cards  |
| Sprint 4 | Notification dashboard, user feedback                    | Logic for one-time notifications, birthday checks, testing |
