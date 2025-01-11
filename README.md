# **🎯 Career Crafter – Placement App**

A centralized mobile application designed to streamline placement-related information for college students. This app bridges the gap between students and placement officers by efficiently managing job updates, preparation materials, and college announcements.


## **Features**
**🎨 User-Friendly Interface**: Intuitive and visually appealing design created using Figma.

**🖥️ Two Panels**:
  - **Admin Panel**: Allows placement officers to upload job details, deadlines, and resources.
  - **User Panel**: Enables students to access categorized job postings, preparation materials, and deadlines.

**📂 Categorization of Job Listings**:
  - *Active Hirings*: Displays job opportunities with active deadlines.
  - *Expired Hirings*: Automatically archives jobs past their deadlines.

**📣 Notification System**: Immediate updates for students upon admin submissions.

**🔍 Search Feature**: Helps students quickly find specific jobs or study materials.


## **Tech Stack**
**🌐 Frontend**: Flutter, Dart  

**⚙️ Backend**: Node.js  

**📦 Database**: MongoDB  

**🎨 UI Design Tool**: Figma  


## **Key Functionalities**
1. **🛠️ Admin Panel**:
   - Upload job details, preparation materials, and deadlines through forms.
   - Trigger immediate notifications to students upon submission.

2. **👨‍🎓 User Panel**:
   - Access categorized listings of active and expired jobs.
   - View and download preparation materials.
   - Search for specific job postings or resources.

3. **📂 Automated Categorization**:
   - Job postings are automatically categorized into *Active Hirings* and *Expired Hirings* based on deadlines.


## **Project Workflow**
**📤 Admin Upload**:
   - Admin fills out a job form and uploads relevant study resources.
   - Submitted data is processed and stored in MongoDB.
   - Notifications are sent to students.

**📥 Student Access**:
   - Students can view categorized job postings in the *User Panel*.
   - The app reduces manual tracking efforts by centralizing information.


## **Benefits**
**👩‍🎓 For Students**:
  - Saves time by providing a centralized platform for placement-related updates.
  - Ensures no missed opportunities due to disorganized information.
  - Simplifies job search with categorized listings and search functionality.

**👩‍🏫 For Placement Officers**:
  - Streamlines the process of sharing job updates and resources.
  - Reduces dependency on scattered communication channels like WhatsApp.


## **🚀 How to Run**
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/career-crafter.git


2. **Navigate to the project directory**:
     ```bash
    cd career-crafter
   
3. **Install dependencies for the frontend and backend**:
  - Frontend:
    ```bash
    flutter pub get
  - Backend:
    ```bash
    npm install
    
4. **Start the backend server**:
    ```bash
    node server.js

5. **Run the Flutter app**:
   ```bash
   flutter run
