# Passion Catalyst

Passion Catalyst is an open-source platform designed to help individuals explore, discover, and engage with their passions while balancing their practical responsibilities. Whether it’s poetry, art, music, or storytelling, Passion Catalyst connects you with tools, inspiration, and a like-minded community to ignite your creativity and make time for what truly matters.

---Poets society

## Features

### Passion Exploration
- **Personalized Recommendations**: AI-curated suggestions for poetry, art, or other creative pursuits based on user preferences.
- **Interactive Tools**: Create and share art, poetry, or other projects in a collaborative digital space.

### Mindful Productivity
- **Creative Time Management**: Integrates with productivity apps to schedule time for creative activities.
- **Micro-Moments of Passion**: Daily suggestions for small, meaningful activities, such as reading a poem or writing a haiku.

### Community and Connection
- **Social Networking**: Connect with like-minded individuals who share your creative interests.
- **Virtual Clubs**: Participate in online workshops, poetry readings, or creative brainstorming sessions.

### AI-Driven Creativity Assistant
- **Creative Prompts**: Generate poetry ideas, art concepts, or music compositions using AI.
- **Interactive Feedback**: Receive constructive suggestions to refine and enhance your creative projects.

### Metrics for Meaning
- **Meaningful Engagement Tracking**: Track time spent on activities that bring joy and personal growth, rather than just productivity metrics.

---

## Installation

### Prerequisites
- [Node.js](https://nodejs.org/) (>=14.x)
- [Python](https://www.python.org/) (>=3.8) for AI-driven backend services
- [PostgreSQL](https://www.postgresql.org/) for database management

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/ObiwanKenobee/passion-catalyst.git
   cd passion-catalyst
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up the backend:
   ```bash
   cd backend
   python -m venv env
   source env/bin/activate
   pip install -r requirements.txt
   ```

4. Configure environment variables:
   - Create a `.env` file in the root directory and add the following:
     ```env
     DATABASE_URL=your-database-url
     API_KEY=your-api-key
     ```

5. Run the application:
   - Start the backend server:
     ```bash
     python app.py
     ```
   - Start the frontend:
     ```bash
     npm start
     ```

---

## Technologies Used

### Frontend
- **React.js** for user interfaces
- **Tailwind CSS** for design

### Backend
- **Flask** for RESTful APIs
- **PostgreSQL** for data storage
- **OpenAI API** for AI-driven creative suggestions

### Other Tools
- **Docker** for containerization
- **Redis** for caching

---

## Contributing

We welcome contributions from the community! Here’s how you can help:

1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push your branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request and describe your changes.

---

## Roadmap

### Phase 1: MVP
- Core platform functionality (recommendations, creative tools)
- Basic user authentication

### Phase 2: Advanced Features
- AI-driven creativity assistant
- Virtual clubs and events
- Metrics for meaningful engagement

### Phase 3: Scaling
- Mobile app development
- Multi-language support
- Integrations with external creative platforms (e.g., Spotify, Canva)

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For questions or feedback, please contact [your-email@example.com](mailto:eugeneochako@gmail.com).

---

## Join Us

Contribute to building a platform that inspires creativity and connects people through their passions. Together, let’s create something meaningful. 🚀
