# Lernsy
## Project Overview
This project introduces an all-in-one educational platform designed to address the challenges students face in finding organized and reliable learning resources. The app consolidates key tools for students and educators, aiming to enhance productivity and engagement in learning.

## Problem Description
Even with the growth of ed-tech, students struggle to find well-organized educational resources across multiple platforms. Key statistics include:
- **60%** of students report difficulty focusing due to scattered resources (Pew Research Center).
- **70%** of students wish for a unified platform for all study materials (National Education Association).
- Students spend **3.5 hours/day** searching for educational resources, leading to feelings of overwhelm (McKinsey & Company).
- **85%** of educators believe integrated tools would boost student engagement and success (Educause).

## Problem Validation
Surveys and interviews highlight the need for a platform that combines key educational resources, collaborative tools, and learning management solutions. Educators have emphasized the importance of interactive features that support smooth learning.

## Existing Solutions and Their Limitations
Most platforms only offer specific content types, such as videos or documents, and lack an all-in-one approach. Common limitations include:
- Absence of collaborative classrooms.
- No comprehensive task management.
- Limited or no interactive study aids.
- Lack of screen time management tools.

## Solution and Uniqueness
This app fills these gaps by providing a comprehensive platform for students and educators. Key features include:
- **Video Recommendations**: ML-powered search for finding relevant educational videos.
- **Comprehensive Resource Access**: Centralized access to materials, textbooks, PYQs, and mock tests.
- **Collaborative Classrooms**: Real-time spaces for group discussions and learning.
- **Task Master**: A tool for managing study schedules with reminders.
- **Screen Time Alarms**: Alerts for study time management.
- **AI-Powered Virtual Assistant**: Real-time interactive assistant for support.

## Technical Description and Feasibility
The app will be built with cross-platform frameworks, ensuring compatibility on web and mobile devices. Key technologies include:
- **Machine Learning Algorithms**: Collaborative and content-based filtering for personalized video recommendations.
- **NLP Models**: GPT and BERT for the virtual assistant's responses.
- **Cloud Storage**: Supports data management and real-time collaboration.

### Algorithms and Tools

#### 1. Video Recommendation Algorithm
- **Description**: Uses collaborative and content-based filtering for video suggestions.
- **Tools**: Python (Scikit-learn, Pandas, NumPy), TensorFlow, YouTube Data API.

#### 2. Task Prioritization Algorithm
- **Description**: Organizes tasks based on deadlines and user-set priorities.
- **Tools**: Python, APScheduler, Django for backend, SQLite for data storage.

#### 3. NLP for AI-Powered Virtual Assistant
- **Description**: An interactive assistant for answering questions and clearing doubts.
- **Tools**: Python, SpaCy, NLTK, pre-trained GPT-3.5 models, Speech Recognition APIs.

#### 4. Screen Time Alarm System
- **Description**: Monitors and manages time spent on the platform.
- **Tools**: JavaScript, React Native, Push Notification APIs.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Athish06/Lernsy.git
   cd Lernsy
