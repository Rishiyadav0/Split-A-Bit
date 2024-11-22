# Split-A-Bit
SplitAbit is a Django-based web application that simplifies expense sharing and tracking among groups. It allows users to create groups, add expenses, and automatically split costs among members, making it ideal for managing shared expenses for trips, households, or other group activities.

**Features**

**User Management**:

Custom user model with secure authentication.
Signup and login functionality.
Email notification upon registration.

**Group Management**:

Create and manage multiple groups.
Add or view group members.
Delete groups (restricted to group creators).

**Expense Tracking**:

Record expenses with details such as amount, payer, and description.
Associate expenses with specific groups.

**Expense Splitting**:

Automatically calculate and display balances for each member.
View detailed expense summaries for each group.

**User Dashboard**:

List all groups a user belongs to.
View detailed breakdowns for each group.

**Tech Stack**
Backend: Django (Python)
Frontend: HTML, CSS (Django Templating System)
Database: SQLite (default Django database, configurable for others)
Email Integration: Django's email framework for notifications
