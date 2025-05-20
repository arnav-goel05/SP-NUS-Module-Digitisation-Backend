# Overview

This repository contains the source code for a back-end of the web application. The project is designed to ensure modularity and separation of concerns.

## Folder Structure

### `config` Folder

* config.json: This file includes essential environment information such as database credentials. It is crucial for setting up and maintaining connections to the database.

### `models` Folder

* Database Schema: Contains the database schema definitions for each table in the database. These schema files define the structure and relationships of the data stored in the database.

### `patches` Folder

* Sequelize Patch: Contains a custom patch for the Sequelize npm package. This patch addresses a bug that was preventing the code from being built successfully.

### `routes` Folder

* API Calls: This folder includes all the API endpoint definitions for the frontend of the website. It handles how the data in the database is being manipulated and accessed by the frontend applications.
