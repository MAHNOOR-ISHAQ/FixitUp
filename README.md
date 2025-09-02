Community Service & Issue Reporting Portal

This is a web platform built with Flask and MongoDB where community members can report issues such as broken streetlights, road damage, robbery, etc. Users can upload photos with their reports, track the issue status (Pending, In Progress, Resolved), and give feedback once resolved.

The system uses sentiment analysis on user feedback with TextBlob. Only positive feedback is displayed on the main page to highlight community satisfaction.

Admins can manage reported issues, update their status, and track progress. The system also provides dashboards for both users and admins, as well as an email notification system to keep users updated about their reports.

Features:

Users can:

Report issues with description and photo

Track issue status (Pending, In Progress, Resolved)

Give feedback on resolved issues

View positive feedback on the main page

Receive email notifications about issue updates

Join community discussions through dashboard

Admin can:

Manage reported issues

Update issue status and assign authorities

View and analyze user feedback

Send email notifications automatically

Access a dedicated dashboard for monitoring issues

Technology Stack:

Backend: Flask

Database: MongoDB

Frontend: HTML, CSS, Bootstrap

Authentication: Flask-Login, Bcrypt (if used)

Sentiment Analysis: TextBlob

Email System: Flask-Mail 
