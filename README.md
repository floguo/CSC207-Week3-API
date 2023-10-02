# CSC207-Group-Project
The project we are doing is towards developing a note-taking application.

### Group Members
Corinna (Yuxing) Ma (Github: cor1nnama) \
Flora Guo (GitHub: floguo)\
Imtiaz Kidwai (Github: imtiaz-kidwai)

Note: this is our group's 2nd repo. We created a new project because we did not set up the Java dependency files during initial project creation.
Our first repo can be found here: https://github.com/cor1nnama/CSC207-Group-Project

### An Overview of Note-Taking Industry

The note-taking application field is a dynamic and evolving sector that is dedicated to creating tools that help
individuals and organizations capture, organize, and manage information in a digital format, which serves as digital 
alternatives to traditional pen-and-paper note-taking methods, offering numerous 
advantages in terms of accessibility, organization and data retrieval.

Market Competition:\
The note-taking application field is highly competitive, with numerous players offering a wide array of features and 
pricing models. Popular note-taking apps include Evernote, OneNote, Notion, Bear, Apple Notes, and a growing number of 
specialized apps tailored to specific niches and needs.

Future Trends:\
The future of note-taking applications is likely to include advancements in AI-driven features, enhanced integrations 
with other productivity tools, improved natural language processing, and a continued focus on user experience and 
accessibility.

### A Brief Description of the Project
We are targeted towards a note-taking system that encourage collaboration among users, fostering a community with the
share of knowledge, at the same time, implanted with easy and efficient way of making your notes look concise and 
understandable with a variety of font and graphs you could easily import.

### API
See https://github.com/cor1nnama/CSC207-Group-Project#:~:text=Commit%20time-,Documentation%20of%20useful%20API,-creation%20of%20api
for more information on the API that are useful in the project.

### Tryout of API Using Hoppscotch
![image](https://github.com/floguo/CSC207-Week3-API/assets/144290310/6635df25-3670-4920-9f86-e20e39f50315)


### Example Output of Running Java Code
Here is an example of the sample output in JSON format:

{
  "kind": "calendar#events",
  "etag": "\"etag_value\"",
  "summary": "Your Calendar Summary",
  "description": "Your Calendar Description",
  "updated": "2023-10-10T12:00:00.000Z",
  "timeZone": "Your Time Zone",
  "accessRole": "owner",
  "defaultReminders": [
    {
      "method": "popup",
      "minutes": 30
    }
  ],
  "nextSyncToken": "sync_token_value",
  "items": [
    {
      "kind": "calendar#event",
      "etag": "\"etag_value\"",
      "id": "event_id",
      "status": "confirmed",
      "htmlLink": "https://www.google.com/calendar/event?eid=event_id",
      "created": "2023-10-10T10:00:00.000Z",
      "updated": "2023-10-10T10:30:00.000Z",
      "summary": "Sample Event",
      "description": "Event Description",
      "location": "Event Location",
      "colorId": "5",
      "creator": {
        "email": "creator@example.com",
        "self": true
      },
      "organizer": {
        "email": "organizer@example.com",
        "self": true
      },
      "start": {
        "dateTime": "2023-10-11T09:00:00+02:00",
        "timeZone": "Your Time Zone"
      },
      "end": {
        "dateTime": "2023-10-11T10:00:00+02:00",
        "timeZone": "Your Time Zone"
      },
      "iCalUID": "iCalUID_value",
      "sequence": 0
    }
    // Additional events may follow here...
  ]
}


### List of Technical Problems
Authentication Errors:\
Blocker: Incorrect or missing authentication credentials to access user's Gcal.
Solution: Ensure that you have valid and properly configured authentication credentials, such as API keys, OAuth 2.0 tokens, or service account JSON files.
Authorization Issues:

Blocker: Insufficient permissions or incorrect scope.\
Solution: Verify that your application has been granted the necessary permissions to access Google Calendar data. Double-check the scopes you've requested.

HTTP Request Errors:\
Blocker: Incorrectly formatted HTTP requests or missing required parameters.
Solution: Review the API documentation to ensure you're sending the correct HTTP requests, including required headers and query parameters.
