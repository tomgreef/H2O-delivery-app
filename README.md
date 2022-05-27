# H2O Watercoolers - Delivery App

## Table of Contents

1.  [Overall Description](#overall-description)

    1. [Introduction](#introduction)
    2. [Purpose](#purpose)
    3. [Intended Use](#intended-use)
    4. [Participants and Users](#participants-and-users)
    5. [Scope](#scope)
    6. [Definitions and Acronyms](#definitions-and-acronyms)

2.  [System Features and Requirements](#system-features-and-requirements)
    1. [Functional Requirements](#functional-requirements)
    2. [External Interface Requirements](#external-interface-requirements)
    3. [Non-functional Requirements](#non-functional-requirements)
    4. [Deployment Environment](#deployment-environment)
    5. [Price and Cost](#price-and-cost)

## Overall Description

### Introduction

H2O Watercoolers is a water dispenser rental and water delivery company that works in the Costa del Sol, Spain. Due to their continuous growth they are in need for an logistic solution for their daily deliveries.

### Purpose

The purpose of this project is to improve their daily routes by reducing delivery times, improving communications between administration and the driver, and automating their administration.

### Intended Use

This will be primarily used by the driver to complete orders and to follow-up on the next client. As a secondary user, we will have administration that will be entering the orders.

### Participants and Users

- **Driver**: Company worker that will execute the deliveries.

### Scope

We will cover the application needed for the driver as the application for administration, while also setting up the necessary communication tools to improve the logistics and business of H2O Watercoolers.

### Definitions and Acronyms

T.B.A.

## System Features and Requirements

### Functional Requirements

- The system will be able to login users.
- The system will be able to see a list of clients in that are set to receive a delivery on a specified date.
- The system will be able to change the specified date of a delivery list.
- The system will be able to order the clients of a delivery day by the most optimal delivery time.
- The system will be able to see all the details of a client, such as contact information, delivery address, notes, bottles possessed and subscriptions.
- The system will be able to synchronize the clients details with Google People.
- The system will be able to open a Google Maps route to the clients address.
- The system will be able to add a new client.
- The system will be able to remove a client.
- The system will be able to update a client.
- The system will be able to remember the login credentials.
- The system will be able to add multiple clients to a planned delivery.
- The system will be able to remove multiple clients of a delivery list.
- The system will notify the user on any insert, update, delete or error.
- The system will validate user input.
- The system will show a loading spinner when fetching data.
- The system will have sidebar navigation.
- The system will be able to keep track of the total of bottles per customer.
- The system will allow the driver to complete a delivery by swiping the client to the left.
  - The system will allow the driver to specify the amount of bottles returned, as default it will be the amount given.
  - The system will allow the driver to change the amount of bottles given.
  - The system will have plus and minus icon to update the inputs.
  - The system will ask the driver to see the next direction on Google Maps.
- The system will keep track of the trucks total bottles.
- The system will keep track of the total of bottles in the warehouse.
- The system will notify about needing refills for bottles.
- The system will authorize actions by roles.
- The system will allow the user to add broken bottles to a client.
- The system will allow the user to add lost bottles to a client.
- The system will show when the rent is due for a client on a delivery list.
- The system will be able to update the delivery date of a client by swiping right.
- The system will be able to delete the delivery of a client by swiping right.
- The system will ask the user to enter the amount of bottles for the delivery of a client, or list of clients in a one by one order.
- The system will ask the user to enter the delivery date.
- The system will always show the default settings on creating a delivery.
- The system will be able to configure the default settings of a client, such as amount of water ordered, route day, weekly/monthly delivery and position in route.
- The system will be able to create a delivery of any product.
- The system will show in the delivery list each product that is meant to be given to the client.
- The system will show the total amount do of the delivery.

### External Interface Requirements

- MySQL Database.
- Mobile device with internet.

### Non-functional Requirements

- Only administration will be able to register users by SQL queries.
- All SQL queries must be audited.
- All external queries must take less than 2000 ms to complete.
- The password will have 8 digits minimum.
- The system must verify the total amount of bottles to be delivered.

### Deployment Environment

T.B.A.

### Price and Cost

T.B.A.
