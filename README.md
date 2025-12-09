Automation Website for St. Xavier’s Catholic College of Engineering
I developed an automation website for St. Xavier’s Catholic College of Engineering that allows students to easily access their academic information.
Key Features:
Phone Number Login
Students can log in using their 10-digit mobile number. No passwords are required, simplifying access.
Local Authentication Storage
The login phone number is stored only in the user’s browser (local storage).
When the user logs out, the stored number is immediately erased, ensuring privacy.
100% Static Frontend (HTML-based)
The entire website frontend is built using pure HTML, making it lightweight and fast.
Secure Data Access
Although the website is static, student data is securely fetched from the college database server.
The phone number acts as a key to request the student’s academic details and marks.
Direct Data Fetching
Upon request, the browser sends the key (phone number) to the college server, retrieves the data, and displays it directly to the user.
Data transfer remains secure, and the fetched information is always specific to the authenticated student.
End-to-End Flow
The data retrieval process begins with the user and ends in the user’s browser.
No data is stored permanently on the website or by me — everything is handled securely between the college server and the student’s device.
