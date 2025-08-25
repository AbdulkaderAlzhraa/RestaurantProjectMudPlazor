# Restaurant Management System

A web application for full restaurant management, built using **C# and MudBlazor**, allowing control over users, menus, tables, and orders in an organized and user-friendly way.

---

## Overview

This system aims to simplify restaurant management through a modern web interface using MudBlazor for each type of user.  
The system supports two main roles:

1. **Supervisor**: Responsible for creating food items, managing users such as admins or cashiers, and assigning tables to customers.  
2. **Cashier/User**: Responsible for receiving orders, registering them in the system, and updating order status.

---

## User Roles

### 1️⃣ Supervisor
- Create and edit food items (name, description, price).  
- Create new users (Admins or Cashiers).  
- Assign tables to customers and link them with the selected meals.  
- Monitor current orders and table statuses.

### 2️⃣ Cashier/User
- Receive orders from customers.  
- Register orders in the system and link them to the appropriate tables.  
- Update order status (In preparation, Ready, Delivered).  
- View order history and daily reports.

---

## Features

- Menu management: add, edit, and delete food items.  
- User management: create admins or cashiers with proper permissions.  
- Table management: assign tables to customers and link them with orders.  
- Receive and track orders in real time.  
- Instant notifications for new orders.  
- Daily reports on orders and sales.  
- Modern and fast user interface using MudBlazor.

---

## Requirements

- **.NET 8 or higher**  
- **Visual Studio 2022 or higher**  
- **SQL Server**  
- **MudBlazor** (for the UI library)  

---

## Installation & Running the Project

### Backend & Frontend (Blazor Server)
1. Clone the repository:
```bash
git clone https://github.com/username/restaurant-management.git
cd restaurant-management
