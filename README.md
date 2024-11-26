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
Focus on setting up foundational functionalities for managing groups and sending notifications.  

### **User Stories**  

1. **Create a Life Group**  
   - **As a user**, I want to create a life group and add members with their name, date of birth, and email so that the group can be organized efficiently.  

2. **Add Members to the Group**  
   - **As a user**, I want to hard-code member details (name, date of birth, email) for now so that the initial data is prepared.  

3. **Send Birthday Notification**  
   - **As a system**, I want to check each member's date of birth and send an email notification 7 days before their birthday so that they feel appreciated.  

4. **Generate Notification Links**  
   - **As a system**, I want to generate a link in the email notification for members to acknowledge or respond to the message.  

---

## **Sprint 2: Message Card Functionality**  
Introduce message cards where users can add or view messages.  

### **User Stories**  

1. **Create an Empty Message Card**  
   - **As a user**, I want to create an empty message card that everyone in the group can see so that the card can act as a shared communication space.  

2. **View All Messages**  
   - **As a user**, I want to view all message cards in the group so that I can see what has been shared.  

3. **Omit Empty Messages in View**  
   - **As a user**, I want the view to omit empty message cards so that I only see meaningful content.  

4. **Check Empty Messages with Admin Code**  
   - **As an admin**, I want to access empty message cards by entering a random alphanumeric admin code so that I can manage them if needed.  

---

## **Sprint 3: Advanced Message Features and Printing**  
Expand message card functionalities and add print options.  

### **User Stories**  

1. **Edit Own Message**  
   - **As a user**, I want to edit only my own message card so that I can share and update my thoughts or information without interference.  

2. **Add Text and Picture to Message**  
   - **As a user**, I want to add text and a picture to my message card so that it is visually engaging.  

3. **Return All Cards**  
   - **As a system**, I want to return all message cards, including empty ones, so that I have a complete view of group activity.  

4. **Return Non-Empty Cards**  
   - **As a user**, I want to return only non-empty message cards so that I can focus on relevant content.  

5. **Print Non-Empty Cards**  
   - **As a user**, I want to print non-empty message cards so that I have a physical record of shared messages.  

---

## **Sprint 4: Notifications and System Enhancements**  
Finalize the notification process and improve system usability.  

### **User Stories**  

1. **One-Time Birthday Notification**  
   - **As a system**, I want to ensure that each member receives only one birthday notification email to avoid spamming them.  

2. **Refine Notification Logic**  
   - **As a system**, I want to accurately check if a member’s birthday is within the next 7 days so that notifications are sent on time.  

3. **Usability Testing and Debugging**  
   - **As a developer**, I want to test all functionalities comprehensively so that the system performs as expected under various scenarios.  

---

## **Sprint Plan Summary**  

| Sprint  | Focus                                   | User Stories                                                                                   |
|---------|-----------------------------------------|-----------------------------------------------------------------------------------------------|
| Sprint 1 | Basic Group and Notification Setup    | Create a life group, add members, send birthday notifications, generate links.                |
| Sprint 2 | Message Card Basics                   | Create message cards, view messages, omit empty cards, admin access.                          |
| Sprint 3 | Advanced Messaging Features           | Edit messages, add text/pictures, return/print cards.                                         |
| Sprint 4 | Notifications and System Enhancements | Refine notifications, ensure one-time emails, usability testing.                              |  

---

