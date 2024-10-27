### QuickStatements 3.0 Homepage Features

The QuickStatements 3.0 homepage provides a user-friendly interface for interacting with the batch processing system. Below is an overview of the main features available:

#### 1\. **Header: Welcome to QuickStatements 3.0**

-   The homepage greets users with a clear header, displaying: "Welcome to QuickStatements 3.0."

#### 2\. **Navigation Menu**

-   A navigation bar at the top of the page allows users to access key parts of the application:
    -   **QuickStatements 3.0(Home)**: The Home link is part of the main navigation menu and redirects users to the homepage. It is represented by the clickable text QuickStatements 3.0, which appears in the navigation bar at the top of the page. 
    -   **New Batch**: Takes users to the page where they can create a new batch for processing.
    -   **Last Batches**: This section (currently not linked) will show recent batches processed by the system.
    -   **Git Repository**: Links to the QuickStatements GitHub repository where users can view the source code and contribute.
    -   **User Information**: 
          - Depending on whether the user is logged in or anonymous, the following options are displayed:
            - If **anonymous**: A **Login** text is shown to authenticate users.
            - If **logged in**: The username and a link to view their last batches are displayed

#### 3\. **New Batch Button**

-  When users click on the New Batch button, they are redirected to the New Batch Creation page. On this page, users can initiate a new batch process by filling out the following form fields:
    - Command Format: Users must select the format of the commands they wish to input. The available options are:
      - v1: The original QuickStatements command format.
      - csv: A format that allows users to input commands in CSV format.
    - Batch Name: Users can assign a custom name to the batch they are creating, making it easier to identify and manage multiple batches.
    - Command Input: This section is where users enter the actual commands they want to execute. The commands should follow the format selected in the "Command Format" field.

#### 4\. **Batch ID Input Form**

-   A form is available to check details of an existing batch by entering a **Batch ID**:
    -   Input type is **number**.
    -   A submit button labeled "See batch details" allows users to view details related to the batch entered.

#### 5\. **Username Input Form**

-   Users can also search for batches associated with a specific username:
    -   Input type is **text**.
    -   A submit button labeled "See batches by user" displays batches submitted by the specified username.


#### 6\. **Visual Layout**

-   The layout follows a simple and responsive design powered by **PicoCSS**, ensuring a clean and modern look across devices.