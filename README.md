# RPA--CAPSTONE-PROJECT
## Capstone Project - Google Forms Creation and Sending via Gmail and WhatsApp Using UiPath

**Aim**:  
To create and automate the process of generating a Google Form and sending the form link through Gmail and WhatsApp using UiPath Studio.

**Equipment Required**:
- UiPath Studio (installed on the system with a valid trial or license).
- A Google Account (for accessing Google Forms and Gmail).
- Computer with a compatible operating system (Windows).
- Basic system requirements such as:
  - Minimum 4 GB RAM.
  - Minimum 2.0 GHz CPU.
  - .NET Framework 4.6.1 or later installed.

## **Procedure**:

### 1. **Start a New Project**
   (i) Open UiPath Studio.  
   (ii) Under the **New Project** tab, select **Process**.  
   (iii) Enter the project name, e.g., `UiPath Google Form Automation`.  
   (iv) Optionally, add a description for the project.  
   (v) Click on **Create** to begin.

#### 2. **Open Main Window**
   (i) In the project dashboard, click on the **Open Main Window** link to navigate to the workflow editor.

#### 3. **Set Up Required Packages**
   (i) Open the **Manage Packages** section (by clicking the `Package Manager` icon or pressing `CTRL + P`).  
   (ii) Install the following packages:
   - **UiPath.Web.Activities** for web automation.
   - **UiPath.Mail.Activities** for sending emails via Gmail.
   - **UiPath.Community.WhatsApp** (if available) for sending messages via WhatsApp Web.

#### 4. **Automate Google Form Creation**
   (i) Open the **Activities** tab on the left-hand side.  
   (ii) Use the **Open Browser** activity to open the Google Forms page. Provide the URL `https://forms.google.com`.  
   (iii) Use a series of **Click** and **Type Into** activities to:
   - Click on **Blank Form** to create a new form.
   - Set the form title and description using **Type Into**.
   - Add questions using repetitive **Click** and **Type Into** activities for question titles and options.

#### 5. **Save and Copy Form Link**
   (i) Use the **Click** activity to click on the **Send** button in Google Forms.  
   (ii) In the pop-up, click on the **Link** icon.  
   (iii) Use the **Get Text** activity to copy the form link for sharing.

#### 6. **Send Google Form Link via Gmail**
   (i) Use the **Open Browser** activity to navigate to `https://mail.google.com`or Use Send Option Which is Placed top of the Form.  
   (ii) Use **Click** and **Type Into** activities to:
   - Click on **Compose** to create a new email.
   - Enter the recipient's email address.
   (iii) Use the **Click** activity to click on **Send**.

#### 7. **Send Google Form Link via WhatsApp**
   (i) Use the **Open Application** activity to navigate to whatsapp Application.  
   (ii) Use **Type Into** and **Click** activities to:
   - Search for a contact or group in the search bar.
   - Paste the Google Form link in the message box.
   - Click the **Send** button.

#### 8. **Save the Project**
   (i) Press `CTRL+S` or use the save icon to save the workflow.

#### 9. **Run the Workflow**
   (i) In the top-right corner of the window, click on the **Debug File** drop-down menu.  
   (ii) From the list, select **Run** to execute the workflow.

### **Observe the Output**:
   (i) Upon successful execution, a Google Form will be created, and the form link will be sent via Gmail and WhatsApp.

### **UiPath Workflow**:
   Use UiPath activities like **Open Browser**, **Click**, **Type Into**, **Send Mail Message**, and **WhatsApp Web Automation** for creating and sending the form.
 ![WhatsApp Image 2024-11-24 at 09 50 49_577185f0](https://github.com/user-attachments/assets/09b7ba13-e41b-4bdb-bd96-66f0bfbb71c0)

 ![image](https://github.com/user-attachments/assets/d265acc4-7e94-4479-99d4-f584adc0dd24)

 ![image](https://github.com/user-attachments/assets/5895b382-1f1c-4dbd-9590-0f3b5971c222)

![image](https://github.com/user-attachments/assets/23e12e1f-f09f-487e-af72-0fdac5d8b4f7)

![image](https://github.com/user-attachments/assets/0ff34c0a-8817-4a37-a274-6e3e564c51cf)

![image](https://github.com/user-attachments/assets/96b3c347-c596-4007-914c-716fbc5c1c88)

![image](https://github.com/user-attachments/assets/df4317ef-7c0f-4933-bdf3-69c30713be9d)

![image](https://github.com/user-attachments/assets/af7f30ed-4c69-49f7-a467-878fe28905ca)

![image](https://github.com/user-attachments/assets/90b3067e-da54-4c21-8c80-98d9e56049d3)

![image](https://github.com/user-attachments/assets/709ade80-874a-406e-8c3f-4abb46333392)

![image](https://github.com/user-attachments/assets/5a37167c-a5b1-4c9f-9aee-ac87bc16d9cd)

![image](https://github.com/user-attachments/assets/395b985f-2581-445d-a741-01a5994e8e2a)

![image](https://github.com/user-attachments/assets/a046c452-e1e1-4388-952d-4ee420299ca0)

![image](https://github.com/user-attachments/assets/c9a0c55d-cd06-4d2e-afa5-40f1be006ba2)

![image](https://github.com/user-attachments/assets/f730dd44-12eb-46c6-af09-3151b8961b04)

![image](https://github.com/user-attachments/assets/20c6f954-8766-4013-9f65-0d04bbf1bc2a)

![image](https://github.com/user-attachments/assets/f34fa360-9b52-404e-a8af-c1503440713c)

![image](https://github.com/user-attachments/assets/827ccb5f-9465-44e7-9b7a-a86166195157)

![image](https://github.com/user-attachments/assets/d86985ac-e73d-4f22-83f0-6af883fe304b)

## Output:
![image](https://github.com/user-attachments/assets/b15e21a3-d05a-4075-9c8c-7382c5a27d45)
![image](https://github.com/user-attachments/assets/36a21597-7eef-4a12-9c6c-4685375f6fd4)
![image](https://github.com/user-attachments/assets/f8dd0aa1-0b67-45c1-ab4e-860005e39928)
![image](https://github.com/user-attachments/assets/cf6de456-b29b-43ae-9bac-b79c082b0bcc)
![image](https://github.com/user-attachments/assets/ec8f3d7c-b948-447e-bd12-d61b17f37096)



### **Result**:
   The Google Form was successfully created and the form link was sent through Gmail and WhatsApp using UiPath Studio.

