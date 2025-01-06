# Simple Accounting

Simple Accounting is a customizable web application designed to help users efficiently manage their daily accounting tasks. With features like a dashboard, category management, sub-user management, and detailed reports, it offers an all-in-one solution for streamlined financial tracking.

## Features

### 1. Dashboard
- Provides a concise overview of all important data.
- Displays key metrics like:
  - Total Revenue
  - Total Cost
  - Total Boxes
  - Total Locations
  - Total Sub-Users
  - Total Donations
- Data is presented in both card view and table view for easy analysis.

### 2. Category Management
- Allows users to create and maintain categories and sub-categories.
- Categories are used in invoices for expenses, deposits, or donations.
- Examples of categories: Cash, Bank Cash, Cheque, etc.

### 3. User Management
- Create and manage sub-users.
- Assign sub-users to locations, boxes, donors, etc.
- Define permission rules for each sub-user.

### 4. Location Management
- Create and manage locations.
- Locations can be assigned to multiple sub-users.

### 5. Box Management
- Create and manage boxes.
- Assign boxes to locations or sub-users.

### 6. Donor Management
- Users and sub-users can create and manage donors.
- Sub-users cannot delete donors.
- If the main user deletes a donor, all sub-users receive a notification with a description of the deletion.

### 7. Deposit Management
- Users and sub-users can make deposits from a box or donor.
- Supported deposit methods: Bank, Bkash, Cheque, etc.

### 8. Expense Management
- Users and sub-users can record expenses for various purposes.

### 9. Settings
- Contains web application-related configurations and settings.

### 10. Reports
- Comprehensive reporting section with various filters:
  - Date
  - Box
  - Location
  - Sub-User
  - Category
  - Sub-Category

### 11. Login Panel
- Secure login panel for accessing the application.

![Simple Accounting Dashboard](https://i.ytimg.com/vi/mYt-LaO44aU/maxresdefault.jpg)

<div style="display: flex; justify-content: space-between;">
  <img src="https://i.ytimg.com/vi/mYt-LaO44aU/maxresdefault.jpg" alt="Image 1" style="width: 48%; height: 200px;">
  <img src="https://i.ytimg.com/vi/mYt-LaO44aU/maxresdefault.jpg" alt="Image 2" style="width: 48%; height: 200px;">
</div>

<div style="text-align: center; margin-top: 20px;">
  <img src="https://i.ytimg.com/vi/mYt-LaO44aU/maxresdefault.jpg" alt="Image 3" style="width: 50%; height: 300px;">
</div>


## Getting Started

### Prerequisites
- A modern web browser.
- Internet connection.

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>  # Clone the repository to your local machine.
   echo "Cloning repository..."  # Debug log: Notify repository cloning starts.
   ```
2. Navigate to the project directory:
   ```bash
   cd simple-accounting  # Change directory to the project folder.
   echo "Changed directory to project folder."  # Debug log: Directory change success.
   ```
3. Install dependencies:
   ```bash
   npm install  # Install all required packages and dependencies.
   echo "Installing dependencies..."  # Debug log: Installation begins.
   ```
4. Start the application:
   ```bash
   npm start  # Start the development server.
   echo "Starting development server..."  # Debug log: Server starting.
   ```
5. Open the application in your browser:
   ```
   http://localhost:3000  # Access the application locally.
   echo "Application started at http://localhost:3000"  # Debug log: Confirm local app start.
   ```

## Usage
1. Log in using your credentials.
   ```bash
   echo "Login process initiated."  # Debug log: Login check.
   ```
2. Navigate to the desired feature from the sidebar menu.
   ```bash
   echo "Navigating to feature..."  # Debug log: Navigation action.
   ```
3. Use the dashboard for a quick overview of financial metrics.
   ```bash
   echo "Loading dashboard..."  # Debug log: Dashboard loading.
   ```
4. Add categories, sub-users, locations, and boxes as needed.
   ```bash
   echo "Managing categories, sub-users, or locations."  # Debug log: Management initiated.
   ```
5. Record deposits and expenses to maintain accurate financial records.
   ```bash
   echo "Recording deposits or expenses."  # Debug log: Record action.
   ```
6. Generate detailed reports using filters to analyze data.
   ```bash
   echo "Generating reports..."  # Debug log: Report generation initiated.
   ```

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name  # Create a branch for your feature.
   echo "New branch created: feature/your-feature-name"  # Debug log: Branch creation.
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your message here"  # Commit your changes with a descriptive message.
   echo "Changes committed with message: Add your message here"  # Debug log: Commit log.
   ```
4. Push your changes:
   ```bash
   git push origin feature/your-feature-name  # Push your branch to the remote repository.
   echo "Changes pushed to remote repository."  # Debug log: Push success.
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License.

## Support
If you have any questions or need assistance, please contact [info@softwareelevate.com].
