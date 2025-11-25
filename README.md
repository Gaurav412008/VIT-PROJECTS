Faculty Cabin Management System
Overview
This Python script allows users to search for faculty members and their assigned cabin numbers, and provides an owner/admin mode for updating the list by adding or deleting entries. The script is interactive, user-friendly, and designed for use in educational institutions to quickly find staff office locations or manage the cabin directory.

Features
Search for faculty cabins by full or partial name.

Owner (admin) authentication for secure access to update records.

Add or delete faculty-cabin assignments in owner mode.

Persistent loop for multiple queries until the user exits.

How to Use
1. User Mode (Search)
Run the script.

When prompted, select user mode by entering 1 or user.

Input the full or partial name of the faculty member.

The script will display all matching faculty names and their cabin numbers.

If no matches are found, you will see "Data not available".

Choose to exit or continue searching.

2. Owner Mode (Admin Operations)
Select owner mode by entering 2 or owner.

Enter the username (Gaurav) and password (VITBPL) for admin access.

Choose to add a new faculty (by entering 1 or add) or delete an existing faculty (by entering 2 or delete).

For adding: Input the faculty name and cabin, confirm details, and the entry will be added.

For deleting: Input the exact faculty name to remove the entry.

Option to exit or continue updating after each operation.

Example
text
enter if you are a user(1)/owner(2) user
Enter the name (or part of the name) of the faculty: baseera
dr. baseera a : G-01
do you want to exit(1)/not exit(2) 1
Notes
All operations are case-insensitive for name search.

Owner credentials are fixed as Gaurav and VITBPL. Change them in code for security.

The initial faculty list is stored in a Python dictionary within the script and does not persist after the program ends. To make data changes persistent, consider adding file write/read features.

Use exact faculty names as stored in the dictionary for delete operations.

Limitations
No database or file storage; changes exist only during program runtime.

Only basic error handling.

Consider feature enhancements (such as file I/O or GUI interface) for broader use.
