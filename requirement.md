
# Workshop <NUMBER> – Requirements

## Overview
This document describes the **tasks and requirements** for this workshop.

Complete all **mandatory tasks**.  
Optional tasks are provided for additional practice.

---

## General Rules
- Work only inside the `starter/` folder
- Do not change the repository structure unless instructed
- Commit your work regularly with meaningful commit messages
- Do **not** commit `node_modules`

---

## Mandatory Tasks

### Task 1 – <Task Starting the Server>
**Description**  
With the Port decided to be on 3000 and server already created with http module. I was tasked with creating a server.listen on the same port, and to log a message when the server starts within the server.js file inside starter folder. Additionally, I add optional route logs for a better user experience which included the index.html, about.html, and contact.html

**Requirements**
- Create server.listen() on port 300
- Used console.log to log a welcome message when the server starts
- Show available routes as a bonus through console.log when server starts

---

### Task 2 – <Task Adding Routing>
**Description**  
The URL paths for all HTML files inside public folder should be mapped so users should be able to access them depending on the url. The filePath variable alongside if and else conditions to display the correct page depending on the path and conditions met

**Requirements**
- Using / should go to index.html
- Using /about should go to about.html
- Using /contact should go to contact.html
(note - either error page or direct to home should be selected when unknown url used, elaborated in further tasks)
---

### Task 3 – <Task Serve HTML files>
**Description**  
To find, locate, determine and read file types utilize fs.readFile and conditionals to showcase correct pages or errors with http responses.

**Requirements**
- Files read using fs.readFile()
- Error handling if no file present or server error 
- if sucessful, response is sent with code 200, with required content type and sends file content

---

### Task 4 – <Task Serve CSS files and Security Check>
**Description**  
Make sure requests that are for CSS files in /styles/ folder are permitted. As well, check path is within public folder only, anything trying access out of public folder given error, so URL's must be follow chosen structure or else gives error

**Requirements**
- Server checks and handles requests for CSS files in styles folder
- Showcases error if traversal attack
- showcases error if invalid url not in public folder directory

---

### Task 5 – <Task Error Handling>
**Description**  
Create two functions to handle different error events one for 404 and the other for 500, utilize the HTML pages to display these errors

**Requirements**
- Function handle404 is created to show 404 HTML when requested page is not found
- Function handleServerError is created to show 500 HTML when server has an error
- if HTML pages are missing, will show plain text instead of custom page

---

## Optional Tasks (Bonus)
These tasks are **optional** and not required for completion.
### Task 6 – <Task API Endpoint>
- 
- 
- 

---

## Validation / Acceptance Criteria
Your solution will be considered complete if:
- The application runs without errors
- All mandatory tasks are implemented
- Code is readable and well-structured
- No unnecessary files are committed

---

## Submission Checklist
Before submitting, make sure that:
- [ ] All mandatory tasks are completed
- [ ] Application starts successfully
- [ ] Code is pushed to GitHub
- [ ] Repository does not contain `node_modules`
- [ ] README instructions were followed

---

## Evaluation Criteria (If Graded)
Your submission may be evaluated based on:
- Correctness of implementation
- Code quality and structure
- Proper use of Git
- Fulfillment of requirements

---

## Notes
- Ask questions if requirements are unclear
- Partial solutions may receive partial credit
- Late submissions follow course policy

---

Good luck! 💪
