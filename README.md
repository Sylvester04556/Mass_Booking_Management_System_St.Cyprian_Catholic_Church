# Mass_Booking_Management_System_St.Cyprian_Catholic_Church
A simple command-line interface (CLI) tool for managing Mass intentions in Catholic parishes.

## Problem Statement

In many Catholic parishes particularly St.Cyprain Catholic Church, managing Mass intentions requests made by parishioners to offer a Mass for a specific person or intention can become overwhelming, especially when handled using paper. This often leads to:

* Double bookings for the same date

* Missing or lost records

* Inefficient updates and cancellations

* Ineffieciency to track daily mass intention that has been booked for a long time.


This mini project seeks to use Python-based tool to manage Mass bookings efficiently.

## Features
 * Add New Intention: Parish staff can record Mass intentions, including the name, contact info, purpose, and offering amount.

 * Update Existing Intention: Modify any field of a previously booked Mass intention.

 * Delete Intention: Cancel and remove bookings when necessary.

* Check Daily Intentions: View all Masses scheduled for a specific date.

 * Persistent Storage: All data is stored in a CSV file (mass_bookings.csv) for easy backup and portability.

## How It Works
When the program runs:

* It loads all previously saved intentions from mass_bookings.csv.

* It prompts the user with options: add, upd, del, check, or exit.

* Based on user input, it performs the corresponding action.

* All changes are saved automatically.

This CLI program is ideal for small to medium-sized parishes that want to move away from paper and use digital records without needing complex software or internet access.
