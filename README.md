Aracnid Validation System
A Java Swing desktop application that captures personal details through a form and validates every field live, giving instant feedback as the user types instead of only after clicking a button.
Built for the Advanced Programming II module (Data Validation System assignment) at Gauteng City College.
Features
Live, per-field validation using `DocumentListener` — no need to click Validate to see errors
Every field gets its own status label, colour-coded green (`Validated!`) or red (specific error)
Presence, type, length, format and range checks, applied per field as appropriate
A themed UI (dark header, spider/web graphic) instead of default Swing styling
Fields and Validation
Field	Checks Applied
Name and Surname	Presence, minimum 2 characters
ID / Student Number	Presence, numeric only, 6–13 characters
Date of Birth	Presence, format (`YYYY-MM-DD` or `DD/MM/YYYY`), year between 1920–2010
Gender	Presence (Male / Female / Other)
Contact Number	Presence, numeric only, exactly 10 digits
Email Address	Presence, standard email format
Tech Stack
Java (Swing, `JFrame`/`JPanel`)
Apache NetBeans IDE
`java.time.LocalDate` for date parsing/validation
Getting Started
Prerequisites
Java JDK 8 or later
Apache NetBeans IDE (recommended, since the GUI was built with the NetBeans Form Editor)
Running the project
Clone the repository:
```
   git clone https://github.com/GeorgeSew/Input-Validation-System.git
   ```
Open the project folder in NetBeans (File → Open Project).
Locate `Validation.java` in the Source Packages.
Right-click it and select Run File (or run the project's main class directly).
The Aracnid Validation System window will open. Fill in the fields — validation feedback appears live under each one.
Project Structure
```
src/
 └── Validation.java   # Main form, validation logic, and UI event handling
```
Author
George Sewata Motseatsea — Gauteng City College, Advanced Programming II
Documentation
Full project documentation (design rationale, validation explanations, and testing evidence) is included separately as part of the assignment submission.
