# Role-Reversal-Med-Bot
# MedBot

MedBot is an AI-powered chatbot designed for medical students and professionals. It consists of two main components:
- **Trainee Bot**: Assists medical students by providing relevant information and answering medical queries.
- **Doctor Bot**: Designed exclusively to clear doubts and provide expert guidance to trainees.

## Features
- AI-based chatbot for medical queries
- Real-time responses for medical students
- Secure and role-based interaction (Trainee & Doctor Bot)
- Integration with a medical database
- User authentication and access control

## Installation

### Prerequisites
Ensure you have the following installed:
- Node.js (latest LTS version recommended)
- MongoDB (for database management)
- npm or yarn

### Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/somyagupta05/medbot.git
   ```
2. Navigate to the project directory:
   ```sh
   cd medbot
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Set up environment variables:
   Create a `.env` file in the root directory and add the following:
   ```env
   MONGO_URI=mongodb://localhost:27017/medbot
   PORT=5000
   ```
5. Start the server:
   ```sh
   npm start
   ```
6. Access the application at `http://localhost:5000`

## Technologies Used
- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **AI Model**: OpenAI API (or any other ML model for medical Q&A)

## Contribution
Contributions are welcome! Follow these steps:
1. Fork the repository
2. Create a new branch (`feature-branch`)
3. Commit your changes
4. Push to your fork
5. Submit a Pull Request

## License
This project is licensed under the MIT License.

## Contact
For any queries, contact:
- **GitHub**: [somyagupta05](https://github.com/somyagupta05)
- **Email**: somyagupta052003@gmail.com

