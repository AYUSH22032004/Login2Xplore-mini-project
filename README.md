# Login2Xplore-mini-project
Micro Project Work 
Here is an example of a GitHub README file for the provided project, which uses a JSON database to manage student data:

---

# Student Management Form

This is a simple web-based application for managing student information using a JSON database. It allows users to add, update, and view student details like roll number, full name, class, birth date, address, and enrollment date.

The project uses HTML, JavaScript, and Bootstrap for the front-end, and it interacts with a JSON-based database through a simple API to store and retrieve student records.

## Features

- **Student Form**: The form allows users to input details such as Roll Number, Full Name, Class, Birth Date, Address, and Enrollment Date.
- **Primary Key (Roll Number)**: Roll number is treated as a unique primary key, ensuring that no duplicate records are created.
- **Save and Update Records**: Users can either save a new student record or update an existing one.
- **Real-time Validation**: The application checks if a record with the provided roll number already exists and either enables the "Update" button for editing or the "Save" button for new entries.
- **API Integration**: The app communicates with an external API to interact with the JSON database, sending `PUT` and `UPDATE` commands to save and modify records.

## Technology Stack

- **HTML** for the structure and layout.
- **CSS** (via Bootstrap) for responsive and styled components.
- **JavaScript** for form validation and API interactions.
- **JSON Database** for storing student records.
- **API** (http://api.login2explore.com:5577/api/irl) for backend interaction.

## Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/student-management-form.git
   ```

2. **Open the `newf.html` file** in a browser to use the form.

3. **Interact with the form**:
   - Enter the student's roll number in the "Roll Number" field. If the roll number already exists, the form will fill the student data, enabling the "Update" button.
   - If the roll number doesn't exist, the form will allow the user to enter the rest of the details and save the record.

4. **Buttons**:
   - **Save**: Saves the record if the roll number is not already present in the database.
   - **Update**: Updates the existing record with the new information.
   - **Reset**: Resets the form fields.

## API Endpoints

- **PUT**: Adds a new student record or updates an existing one.
- **UPDATE**: Modifies the existing student record using the roll number.

## How to Contribute

1. Fork the repository.
2. Clone your fork locally.
3. Create a new branch for your changes.
4. Commit your changes and push to your fork.
5. Open a pull request.



--
