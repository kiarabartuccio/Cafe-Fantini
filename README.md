# Café Fantini Inventory Management System

A database-backed inventory-management web application developed for **Café Fantini Canada Inc.**, a business-to-business distributor of coffee beans, coffee capsules, and juices. The system centralizes inventory information, makes stock easier to manage, and provides role-based access for the business owner and secretary.

## Live Demo

**Application:** [https://cafefantinidb.web.app/](https://cafefantinidb.web.app/)


## Features

- Secure login with separate admin and secretary roles
- Inventory dashboard with clear stock summaries
- Add, view, update, and delete products
- Update the quantity available for each product
- Organize products into categories
- Search, filter, and sort inventory records
- Identify products with low stock
- Store product details such as name, category, price, quantity, and barcode
- Track stock updates in the database
- Responsive, user-friendly interface for daily business use

## User Roles

### Administrator

The administrator has full system access and can:

- Add new products
- Edit product information and pricing
- Update stock quantities
- Delete products
- Search and organize inventory
- View all inventory records and dashboard information

### Secretary

The secretary has restricted access designed for daily inventory entry, including adding new inventory items without receiving full administrative control.

## Technologies and Concepts

- Web application development
- Firebase Hosting
- Database-backed CRUD operations
- Authentication and role-based authorization
- Inventory and stock-management logic
- Responsive user-interface design
- Git and GitHub

## Database Design

The application is organized around four main data areas:

- `USERS` – account information and user roles
- `CATEGORIES` – product groupings such as coffee beans, capsules, and juices
- `PRODUCTS` – product information, price, barcode, and current quantity
- `STOCK_UPDATES` – inventory quantity changes and update history

## Business Purpose

Café Fantini previously relied primarily on Sage 50 for accounting and basic inventory tracking. This project provides a more focused and user-friendly inventory system that centralizes stock information, improves product visibility, reduces the risk of stock mismanagement, and supports the company's growing operations.

The system was designed for a B2B distributor serving hotels, cafés, restaurants, and grocery stores.

## Quick Start

The easiest way to test the project is through the [live demo](https://cafefantinidb.web.app/) using the demonstration credentials above.

To work with the source code:

1. Clone or download the repository.
2. Open the project in your preferred code editor.
3. Install any dependencies listed in the project configuration files.
4. Add your own Firebase configuration and environment values where required.
5. Run the project using its included development command or local server.

Do not commit private production credentials or secret configuration values to a public repository.

## What I Worked On

I primarily contributed to the **front-end development** and helped lead the project documentation. My work focused on translating the client's inventory requirements into a clean, accessible interface and supporting the team's overall system design.

## Team

- **Kiara Bartuccio** – Front-end development and project documentation
- **Oliver D’Avino** – Back-end development
- **Shayne Uzan** – Database development

## Academic Context

This system was created as a Vanier College System Development project for a real business client. The project included client interviews, requirements analysis, user stories, usability testing, UML diagrams, database design, prototyping, and iterative development.
