# Dormitory Management System

A web-based dormitory management system built with Java, providing comprehensive features for managing student housing.

## Features

- Multi-level user authentication (System Admin, Dormitory Admin)
- Student management
- Building management
- Room allocation
- Absence records
- Move-out management

## Tech Stack

- Java
- MariaDB/MySQL
- JSP
- Tomcat
- Maven

## Database Structure

The system uses the following key tables:

- student: Student information
- dormitory: Room information
- building: Building details
- dormitory_admin: Dormitory administrator accounts
- system_admin: System administrator accounts
- absent: Absence records
- moveout: Move-out records

## Getting Started

1. Import database:

````bash
mariadb -u root -p < dormitory.sql

## Setup for Arch Linux Users
1. Install required packages:
```bash
sudo pacman -S mariadb tomcat10 maven
2. Statr MariaDB service:
```bash
sudo systemctl enable --now mariadb
3. Start tomcat10 service
```bash
sudo systemctl start tomcat10.service
or
Find the Tomcat10 HOME/bin, and run startup/shutdown as root.
(Tomcat's HOME always at `/usr/share/tomcat10/`)
````
