# HR Management System (RPA Platform)

![Project Status](https://img.shields.io/badge/status-active-brightgreen)
![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## Created By
- **Sairam Peddigari** - Lead Developer
- **Naveen Shankar** - System Architect
- **Sumukh Shrote** - Backend Developer
- **Abhishek Chhabra** - Frontend Developer

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [System Architecture](#system-architecture)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [License](#license)

 Overview
A comprehensive HR Management System built as a Robotic Process Automation (RPA) platform. This system automates various HR processes including employee management, attendance tracking, leave management, and payroll processing.

## # HR Management System (RPA Platform)

![Project Status](https://img.shields.io/badge/status-active-brightgreen)
![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## Created By
- **Sairam Peddigari** - Lead Developer
- **Naveen Shankar** - System Architect
- **Sumukh Shrote** - Backend Developer
- **Abhishek Chhabra** - Frontend Developer

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [System Architecture](#system-architecture)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [License](#license)

## Overview
A comprehensive HR Management System built as a Robotic Process Automation (RPA) platform. This system automates various HR processes including employee management, attendance tracking, leave management, and payroll processing.

## Features

### 1. Employee Management
- Add/Update employee information
- Employee profile management
- Department-wise organization
- Document management

### 2. Attendance System
- Automated clock-in/clock-out
- Real-time attendance tracking
- Overtime calculation
- Attendance reports generation

### 3. Leave Management
- Multiple leave types support
- Leave application and approval workflow
- Leave balance tracking
- Calendar integration

### 4. Payroll System
- Automated salary calculation
- Tax deduction management
- Allowance handling
- Payslip generation
- Payroll history tracking

### 5. Reporting
- Custom report generation
- Department-wise analytics
- Attendance patterns
- Leave statistics
- Payroll summaries

## Technology Stack
- **Backend:** Python 3.8+
- **Frontend:** Gradio
- **Database:** File-based system with CSV
- **Dependencies:**
  - pandas
  - numpy
  - gradio
  - pytz

## Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/hr-management-system.git
cd hr-management-system
```

2. Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

## Usage

1. Start the application
```bash
python main.py
```

2. Access the web interface at `http://localhost:7860`

3. Default test credentials:
```
Employee ID: EMP0001
Manager ID: MGR0001
```

## System Architecture

### Components
- **Database Manager:** Handles data persistence and retrieval
- **Attendance Tracker:** Manages attendance records
- **Leave Manager:** Handles leave applications and processing
- **Payroll Generator:** Processes salary calculations
- **Web Interface:** Gradio-based user interface

### Data Flow
```
User Input → Validation → Business Logic → Database → Response
```

## Documentation

### Employee Management
```python
# Add new employee
employee_data = {
    'first_name': 'John',
    'last_name': 'Doe',
    'email': 'john.doe@company.com',
    'department': 'IT'
}
hr_system.add_employee(employee_data)
```

### Attendance Tracking
```python
# Record attendance
hr_system.record_attendance('EMP0001')
```

### Leave Management
```python
# Submit leave request
leave_data = {
    'employee_id': 'EMP0001',
    'start_date': '2024-03-15',
    'end_date': '2024-03-20',
    'leave_type': 'Annual'
}
hr_system.process_leave_request(leave_data)
```

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
- Thanks to all contributors who have helped with the project
- Special thanks to the testing team for their valuable feedback
- Gradio team for the amazing interface framework

## Support
For support, email:
- sairam.peddigari@example.com
- naveen.shankar@example.com
- sumukh.shrote@example.com
- abhishek.chhabra@example.com

## Project Status
- Current Version: 1.0.0
- Last Updated: March 2024
- Status: Active Development

---
© 2024 HR Management System Team. All Rights Reserved.Features

### 1. Employee Management
- Add/Update employee information
- Employee profile management
- Department-wise organization
- Document management

### 2. Attendance System
- Automated clock-in/clock-out
- Real-time attendance tracking
- Overtime calculation
- Attendance reports generation

### 3. Leave Management
- Multiple leave types support
- Leave application and approval workflow
- Leave balance tracking
- Calendar integration

### 4. Payroll System
- Automated salary calculation
- Tax deduction management
- Allowance handling
- Payslip generation
- Payroll history tracking

### 5. Reporting
- Custom report generation
- Department-wise analytics
- Attendance patterns
- Leave statistics
- Payroll summaries

## Technology Stack
- **Backend:** Python 3.8+
- **Frontend:** Gradio
- **Database:** File-based system with CSV
- **Dependencies:**
  - pandas
  - numpy
  - gradio
  - pytz

## Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/hr-management-system.git
cd hr-management-system
```

2. Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

## Usage

1. Start the application
```bash
python main.py
```

2. Access the web interface at `http://localhost:7860`

3. Default test credentials:
```
Employee ID: EMP0001
Manager ID: MGR0001
```

## System Architecture

### Components
- **Database Manager:** Handles data persistence and retrieval
- **Attendance Tracker:** Manages attendance records
- **Leave Manager:** Handles leave applications and processing
- **Payroll Generator:** Processes salary calculations
- **Web Interface:** Gradio-based user interface

### Data Flow
```
User Input → Validation → Business Logic → Database → Response
```

## Documentation

### Employee Management
```python
# Add new employee
employee_data = {
    'first_name': 'John',
    'last_name': 'Doe',
    'email': 'john.doe@company.com',
    'department': 'IT'
}
hr_system.add_employee(employee_data)
```

### Attendance Tracking
```python
# Record attendance
hr_system.record_attendance('EMP0001')
```

### Leave Management
```python
# Submit leave request
leave_data = {
    'employee_id': 'EMP0001',
    'start_date': '2024-03-15',
    'end_date': '2024-03-20',
    'leave_type': 'Annual'
}
hr_system.process_leave_request(leave_data)
```

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
- Thanks to all contributors who have helped with the project
- Special thanks to the testing team for their valuable feedback
- Gradio team for the amazing interface framework

## Support
For support, email:
- sairam.peddigari2021@vitstudent.ac.in
- naveenshankar.choudhury2021@vitstudent.ac.in
- sumukh.shrote2021@vitstudent.ac.in
- abhishek.chhabra2021@vitstudent.ac.in

## Project Status
- Current Version: 1.0.0
- Last Updated: March 2024
- Status: Active Development

---
© 2024 HR Management System Team. All Rights Reserved.
