# Sticky Notes Application - Sequence Diagram

## Creating a Note

```
User -> Browser: Click "Create Note"
Browser -> Django View (note_create): GET request
Django View -> Form: Render empty form
Form -> Browser: HTML form
Browser -> User: Display form

User -> Browser: Fill form and submit
Browser -> Django View: POST request with data
Django View -> Form: Validate data
Form -> Django View: Valid
Django View -> Model (Note): Create instance
Model -> Database: Save note
Database -> Model: Success
Model -> Django View: Success
Django View -> Browser: Redirect to note_list
Browser -> User: Show note list