# ADR4: Application Permissions

Date: February 16, 2024

**Status**

Proposed

**Context**

Here are the following permissions the application requires:

- Location

  Allowing the location can be optional but this will help in terms of locating other student, club activities location, event locations, locating classrooms and locating classrooms.

- Cameras and Photos

  This permission will allow user to upload photos in the application whether for their profile picture or sharing photo document to their fellow student, colleague or professors. This will also allow the user to perform a video chat through the app.

- Storage

  This permission is necessary for storing app data, caching content for offline use or accessing the any file from the phone to upload.

- Notification

  This permission will allow the app to send push notification to inform users about new announcements, assignment deadlines, and other relevant event.

- Network Connection

  This permission will allow the application to connect to a network for communication and synchronization.

- Authentication

  Since University has an existing Active Directory System, this permission is required to authenticate user and verify their identities securely.

- Calendar

  This permission will allow the application to access the device's calendar for the student classes, school events, and sessions.

**Decision**

Based on the user needs provided it is decided to acquire permissions on the following that is listed above.

**Consequence**

Requesting sensitive permissions can raise user privacy concerns.
Users might be hesitant to allow those permissions.
Allowing multiple permission in an app can reduce the battery life.
