# EditReadme
ReadMe File for PROG6212 Part2
 Claims Submission System

## Introduction

This is a web application developed using ASP.NET Core that allows lecturers to submit claims for their work hours, which can then be verified and approved by Programme Coordinators and Academic Managers. The application features a user-friendly interface, file upload capabilities, claim tracking, and robust error handling.

## Features

1. **Claims Submission for Lecturers**:
   - Lecturers can easily submit their claims using a simple and intuitive form.
   - The form includes fields for hours worked, hourly rate, and additional notes.
   - An `Upload` button is provided to allow the submission of supporting documents (e.g., .pdf, .docx, .xlsx).

2. **Claims Verification by Coordinators and Managers**:
   - A dedicated view for Programme Coordinators and Academic Managers to oversee pending claims.
   - Each claim displays relevant information for easy verification.
   - Options to `Approve` or `Reject` claims are available.

3. **Document Uploading**:
   - Lecturers can upload supporting documents with file type restrictions and size limits to ensure security.
   - Uploaded document names are displayed on the submission form.

4. **Claim Status Tracking**:
   - Claims status is visibly updated as they move through the approval process (e.g., 'Pending', 'Approved', 'Rejected').
   - Real-time updates occur whenever a claim is acted upon.

5. **Consistent and Reliable Information**:
   - Comprehensive unit tests are written to ensure that key functionalities are thoroughly tested.
   - Detailed error handling mechanisms display meaningful messages to users in case of issues.
