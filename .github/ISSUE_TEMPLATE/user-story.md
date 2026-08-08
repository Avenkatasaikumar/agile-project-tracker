---
name: User Story
about: Template for creating a user story
title: "[USER STORY] "
labels: enhancement
assignees: Avenkatasaikumar
---

## User Story

**As a** registered user
**I need** to log in with my email and password
**So that** I can access my personal dashboard securely

## Acceptance Criteria

```gherkin
Scenario: Successful login with valid credentials
  Given I am on the login page
  When I enter a valid email and password and submit the form
  Then I am redirected to my dashboard and see a welcome message

Scenario: Failed login with invalid credentials
  Given I am on the login page
  When I enter an incorrect email or password and submit the form
  Then I see an error message and remain on the login page
```

## Additional Notes
This template can be duplicated for each new user story. Update the As a/I need/So that fields and acceptance criteria scenarios to match the specific requirement.
