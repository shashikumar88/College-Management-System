# University-Management-System

### Description

This is a simple Python-based University Management System that allows users to:

- Create colleges
- Add teachers and students to a specific college
- Display teacher and student details
- Validate teacher and student email registration using OTP verification via SMTP

### Features

- Object-Oriented Programming (OOP) design with classes for `Person`, `Student`, `Teacher`, and `College`.
- Secure email verification using OTP authentication.
- Interactive command-line interface for user input.

### Prerequisites

Before running the program, ensure you have the following:

- Python 3.x installed
- Required Python libraries:
  - `smtplib`
  - `email`
  - `random`

### Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/college-management-system.git
   ```
2. Navigate to the project directory:
   ```sh
   cd college-management-system
   ```
3. Install required dependencies (if any):
   ```sh
   pip install -r requirements.txt
   ```

### Usage

1. Run the script:
   ```sh
   python main.py
   ```
2. Follow the prompts to:
   - Create a new college
   - Add teachers and students
   - Display details

### Configuration

- Update the SMTP credentials (`username` and `password`) in the script before running the program.
- Ensure that "Less secure apps access" is enabled for your Gmail account if using Gmail for SMTP.

### Security Notice

- Using hardcoded email credentials is **not recommended**. Consider using environment variables for better security.
- Enable two-factor authentication (2FA) and use an **app password** instead of your primary password for SMTP authentication.

### License

This project is licensed under the MIT License - see the LICENSE file for details.

### Author

K Shashi Kumar

