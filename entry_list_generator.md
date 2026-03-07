# About Entry List Generator
**Entry List Generator** is a tool that allows for easy editing of Entry Lists for the game [Assetto Corsa Competizione](https://store.steampowered.com/app/805550/Assetto_Corsa_Competizione/)

Entry Lists are lists defined on a dedicated server that define:
- The teams
- The drivers within teams
- The car properties of the team

This tool allows for the following:
- Create new entry lists
- Import existing entry lists from **JSON** files
- Import existing entry lists from **CSV** files
- Export entry lists into **JSON** files that the server understands
 
# Why this tool?
There are many tools and web GUIs that allow for server configuration and even starting servers, but for our community we had specific requirements: being able to convert CSV files to entry lists.
Our workflow was as follow:
1. Admins create a google form
2. Participants would fill in the forms
3. A GSheet with entries gets filled automatically
4. Convert this GSheet to an entrylist.json file
5. Upload this file to the server
6. Run our race event!

For step 4 non of the tools that I found at the time met our requirements, so I made my own.

# Media
_A sample of how our entries looked in GSheet_

<img alt="A sample of how our entries looked in GSheet" src="https://github.com/user-attachments/assets/ac2e2919-1640-4abf-ad12-9adc80c5e105" />

_And then imported into this tool, allowing for exporting into JSON_

<img alt="And then imported into this tool, allowing for exporting into JSON" src="https://github.com/user-attachments/assets/ac56249c-f8fe-4daf-93d6-272ab02a581a" />


For more details see [Github](https://github.com/GeertCocu/Entry-List-Generator).
