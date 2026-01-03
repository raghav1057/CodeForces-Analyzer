# CodeForces Analyzer 

A web-based application for analyzing **CodeForces** competitive programming problems and contests. This tool helps competitive programmers track their progress, analyze problem difficulty, compare contest results, and discover random problems for practice.

---

## ✨ Features

- **Problem Analysis**: Fetch and analyze problems from CodeForces
- **Contest Information**: View upcoming contests and contests statistics
- **Problem Comparison**: Compare multiple problems side-by-side
- **Random Problem Generator**: Get a random problem for practice
- **User-Friendly Dashboard**: Clean, intuitive web interface
- **Real-time Data**: Fetches latest data from CodeForces API

---

##  Tech Stack

- **Backend**: Python (Flask)
- **Frontend**: HTML5, CSS3, JavaScript
- **API**: CodeForces REST API
- **Styling**: Custom CSS with responsive design

---

## Installation

### Prerequisites
- Python 3.7 or higher
- pip (Python package manager)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/raghav1057/CodeForces-Analyzer.git
   cd CodeForces-Analyzer
   ```

2. **Create a virtual environment** (optional but recommended)
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   python Analyzer/main.py
   ```

5. **Access the application**
   - Open your browser and navigate to `http://localhost:5000`

---

## 🚀 Usage

### Main Features:

1. **Home Page**: Browse and search problems
2. **Problem Analysis**: View detailed problem information
3. **Compare Results**: Compare multiple problems or solutions
4. **Upcoming Contests**: View all upcoming CodeForces contests
5. **Random Problem**: Get a random problem for daily practice

---

## 📁 Project Structure

```
CodeForces-Analyzer/
├── Analyzer/
│   ├── main.py              # Flask application entry point
│   ├── static/              # Static files (CSS, images, JS)
│   │   ├── style.css        # Main stylesheet
│   │   ├── style2.css       # Additional styles
│   │   ├── loader.css       # Loading animation styles
│   │   ├── index.html       # Main page HTML
│   │   ├── result.html      # Result display page
│   │   ├── results.html     # Multiple results page
│   │   ├── contest.html     # Contest information page
│   │   ├── random_problem.html     # Random problem page
│   │   ├── upcoming_contests.html  # Upcoming contests page
│   │   ├── error.html       # Error page
│   │   └── images/          # Image assets
│   └── templates/           # Flask templates
│       ├── index.html       # Home template
│       ├── results.html     # Results template
│       ├── loader.html      # Loading template
│       └── error.html       # Error template
└── README.md
```

---

## 🔌 API Integration

This application integrates with the **CodeForces API** to fetch:
- Problem details (difficulty, tags, acceptance rate)
- Contest schedules and information
- User statistics and submissions

### Example API Calls:
- `https://codeforces.com/api/problemset.problems` - Get all problems
- `https://codeforces.com/api/contest.list` - Get contest list

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 👤 Author

**Raghav** - [@raghav1057](https://github.com/raghav1057)

---

## 🙏 Acknowledgments

- [CodeForces](https://codeforces.com/) for the amazing problem platform and API
- All competitive programmers who use this tool

---

## 📧 Contact

For questions or suggestions, feel free to reach out or open an issue on GitHub.

**Happy Coding! 🚀**
