# Software Requirement Specifications

## Problem Statement

- Task management and note taking apps on the market have limited flexibility and customizability.

- I want a software that allows me to select functionalities based on what type of list-format document I need. 

- After investigation over the current solutions available to the users, we found that: Google Keep does not provide a due date feature; Monday.com is web-based and is heavily aimed at team collaboration; Microsoft ToDo only supports document printing but does not allow exporting to text file; Outlook is highly coupled with the other Microsoft Office softwares; almost all of them require users to upload their lists to the cloud.

## Potential Clients

- Students

- Employees

- Manager

- Team collaborators

- Multitasker

## Proposed Solution

- A functionality-flexible list management software where users can select features upon creating a document.
- The app is web-based and designed to be RESTful.
- Documents (lists) are stored in the database. Each list contains a number items and is able to do certain functionalities. When creating a list, the user can select to have different functionalities: have a duedate and startdate, store a side note in addition to the content shown in the item, automatically fit items in schedule, be able to do limited autocorrection, convert associated images into text, convert associated voice entries into text, etc.

## Functional Requirements

### Must have

- As a multitasker, I want different groups of features to be selectable to my different types of lists, so that I don’t need to go to multiple apps for different features.

- As a note-taker, I want to have an extension to record my random thoughts, so that I can look back and use some of the ideas.

- As a student or employee, I want to have a time management extension to manage my to-do lists, so that I can work efficiently.

- As a user, I want to mark my emails and convert the marked sections to a note in the app, so that I can easily make reminders

- As a collaborator, I want to push an item entry to be visible to some other users.

	- As a owner of some lists, I want the lists only visible to me and the collaborators.

	- As a collborator, I want the lists that marked me as a collaborator to be visible to me, but not the ones that I do not have business with.

### Nice to have

- As a busy user, I want to have an optional auto-scheduling function that can match my tasks with my available time slots. 

- (May not be realizable in web-base design) As a manager, I want my to-do lists to be only stored locally, so that I don’t need to worry about the sensitive information of the company.

- As an employee, I want to upload my notes or to-do list on the cloud.

- As a team collaborator, I want to have my to-do list visible and shareable to my team, so that everyone knows how hard I work.

- As a student or employee, I may want to link my to-do list in the notes.

- As busy user, I want to convert an image that contains notes into text.

- As a user, I want to upload a and convert a voice recording into text

- As a PowerPoint user, I want to convert my list into a PowerPoint file, so that I can easily create slides from my previous notes.

## Software Architecture

- Client-server architecture

- Server stores user documents (local and cloud), client allows user interaction and graphical elements.

## Prototype GUI
![alt text](./prototypeappgui.drawio.png)
