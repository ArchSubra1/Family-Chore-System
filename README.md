# Family-Chore-System
Simple family chore system using Todoist + Google Sheets /Calendar

This repo documents a No-Code / Low-Code / Free family task management system that focuses on:

Visibility

Ownership

Simple execution

Optional rewards

High-Level Process Flow

Google Sheets

Initial master list of all house tasks

Tasks categorized by frequency and assignee

Exported as CSV

Todoist

Execution and day-to-day operational tool

Tasks imported from CSV

Sections used for Daily / Weekly / Monthly tasks

Google Calendar

Todoist tasks synced to individual calendars

Shared family calendar enables Sunday planning

Google Sheets (Rewards)

Completed tasks logged

Rewards calculated by task frequency

Optional automation using Apps Script

Setup Steps
1. Create the Task Template (Google Sheets → CSV)

Use a simple Google Sheets template

One row per task

Key columns:

Task name

Frequency (Daily / Weekly / Monthly)

Assigned family member

Sections and frequency keywords are the key design choice

(See sample CSV in this repo)

2. Import into Todoist

Create a new Todoist project

Add family members

Import the CSV

Verify tasks and sections, then save

Each family member:

Sees their tasks in their own app

Can reschedule or reassign as needed
This dramatically improved execution and collaboration.

3. Enable Google Calendar Sync

Todoist supports native Google Calendar sync

Each member syncs their Todoist tasks

Calendars are shared with the family

This makes Sunday planning simple and visual — no extra meetings or reminders.

4. (Optional) Rewards with Google Apps Script

A lightweight Apps Script logs completed tasks

Rewards are calculated based on task frequency

No points are hard-coded into task names

If you don’t want to code or don’t want rewards:

Skip this step entirely

The system still works well without it

(Script included in this repo for reference) 

Code.gs

Tools Explored (and Dropped)

Notion
→ Too much setup and friction for kids

Google Tasks
→ Simple, but weak for shared family ownership
