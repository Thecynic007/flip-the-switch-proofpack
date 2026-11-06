# Junior Backend Developer — Sam

0 requirements supported, 3 partly supported, and 3 missing.

## Requirements and evidence map

| Requirement | Status | Evidence and limits |
|---|---|---|
| Build and maintain REST APIs in Node.js | Partly supported | Student Notes API is a small Node.js service that saves and lists notes in a database. The description does not establish REST conventions or maintenance history. AI wrote most of the code; Sam can explain the main parts. |
| Write SQL queries and work with databases | Partly supported | Databases coursework covers basic SQL, and the Notes API uses an unspecified database. No project SQL use or database technology is identified. |
| Write automated tests | Missing | Sam says there has been no testing. |
| Deploy services to the cloud (AWS preferred) | Missing | Sam says there has been no cloud use. |
| Work with teammates using Git and code reviews | Partly supported | The Weather App has a GitHub repository. No team project, code review, or collaborative Git workflow is described. |
| Docker (nice to have) | Missing | No Docker experience was shared. |

## Flagged claims

The evidence does not support saying that Sam built or maintained a production REST API, used SQL in the Notes API, wrote automated tests, deployed to AWS or another cloud, participated in code reviews or team Git workflows, or used Docker. Avoid implying that Sam independently authored most of the Notes API code: the supplied account says AI wrote most of it and Sam can explain the main parts. The Weather App being used by classmates supports real use, but not a particular scale or formal deployment.

## Risky claim and honest wording

| Risky claim | Honest wording |
|---|---|
| “I independently built and maintained REST APIs in Node.js.” | “I made a small Node.js Notes API that saves and lists notes; I used AI for most of the code and can explain its main parts. I have not described its REST conventions or maintenance.” |
| “I used SQL in my database project.” | “I studied basic SQL in coursework. My Notes API uses a database, but I haven’t specified its technology or whether I used SQL in that project.” |
| “I write automated tests.” | “I haven’t written automated tests yet.” |
| “I deployed services to AWS.” | “I haven’t used cloud services yet.” |
| “I collaborate through Git and code reviews.” | “My Weather App has a GitHub repository; I haven’t described team Git work or code reviews.” |
| “I have Docker experience.” | “I haven’t used Docker yet.” |

## Honest next steps for missing requirements

Each step is scoped to be achievable within 7 days.

- **Automated tests:** Add tests for the Notes API’s save and list behavior, run them, and document the command and results.
- **Cloud/AWS:** Deploy a minimal Notes API to an AWS service and record the setup steps and live endpoint. If AWS access is unavailable, practice in another cloud and name it accurately.
- **Docker:** Write a Dockerfile for the Notes API, build and run the container locally, and document the commands and result.

## Interview questions

1. In the Notes API, what happens when a note is saved or listed, and which parts did AI help write?
2. What database does the Notes API use, how does it store notes, and what basic SQL query from coursework can you explain?
3. How does the Weather App get weather data from the free service, and what did you do when a response was missing or invalid?
4. How did classmates use the Weather App, and what feedback or issue did that use reveal?
5. What does the GitHub repository show about your own changes, and what would you need to add before calling the work collaborative or code-reviewed?
