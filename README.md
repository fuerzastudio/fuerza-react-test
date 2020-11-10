# Fuerza Studio (React) Coding Assessment

## Overview

To complete this assessment, you will need to write a simple [React](https://facebook.github.io/react/) web app, using the code from this repo as starter.

The purpose of this assessment is to assess your **skills and approach to composing a simple web app** given an API feed. We will also assess the **generated HTML, CSS, and JS** output.

This assessment is expected to take about 3-5 hours.

## What to do?

Your goal is to implement a simple React application, where users will be able to create journals.

Although its a very basic exercise, we will be looking for simple, well-designed, well-commented and clear code in the submission.

## How should the application work?

The user of this react application should be able to create an account, login and create a journal and on the journal create notes.

1. Create an account
2. Login.
3. Create Journal.
4. Create notes.
5. List Journals.
6. List notes.

## API Usage

API can be launched using npm start. You will need to run npm install once you starting working on the project to install dependencies.

| Endpoint             | Result                      |
| -------------------- | --------------------------- |
| /auth/login          | Login                       |
| /auth/signup         | Sign up                     |
| /journal/entries/:id | List all journals from user |
| /journal/entries/:id | List all journals from user |

---

## API

- post => '/auth/login', user.login'
- post => '/auth/signup', user.signup'

- get => '/journal/entries/:id', journal.getEntries'
- get => '/journal/:id', journal.getJournal'

- post => '/journal/', journal.create' _title : String_
- post => '/journal/entry/:id', journal.addEntry' _{content,title} : Object_

- put => '/journal/entry/:id', journal.updateEntry' _{content,title} : Object_
- put => '/journal/:id', journal.updateJournal' _title : String_
