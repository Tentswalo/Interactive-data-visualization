# Interactive Data Visualization Portfolio - MVP Specification

<img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*Qn4sp28csHcEGfnv-AoIHw.png" alt="Description of the image">

## Introduction 👋

Welcome to the **Interactive Data Visualization Portfolio** project. This platform is designed to enable users to visualize, interact with, and analyze complex data sets in real-time. By leveraging powerful data visualization tools, users can gain meaningful insights from their data efficiently and intuitively.

- **Deployed Project Application**: [Interactive Data Visualization Portfolio](https://github.com/Tentswalo/Tentswalo.io)
- **Final Project Blog Article**: [Project Blog Article](https://medium.com/@mpenane1/the-purpose-of-the-interactive-data-visualization-portfolio-is-to-create-a-robust-user-friendly-6bb62913aa6d )

## Installation 🛠️

To set up the project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/interactive-data-visualization-portfolio.git
    cd interactive-data-visualization-portfolio
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up the database**:
    ```bash
    flask db init
    flask db migrate -m "Initial migration"
    flask db upgrade
    ```

5. **Run the application**:
    ```bash
    flask run
    ```

    The application should now be running on `http://127.0.0.1:5000`.

## Usage ✍

1. **Uploading Data**:
    - Navigate to the upload page and select your data file (e.g., CSV).
    - The data will be processed and visualizations will be generated in real-time.

2. **Interacting with Visualizations**:
    - Use the interactive tools to explore your data.
    - Customize your dashboard by selecting different visualizations and adjusting their parameters.

3. **Real-Time Data Updates**:
    - As new data is added, the visualizations will update in real-time.
    - This feature is particularly useful for monitoring live data streams.

## Features 🔎

- **Real-time Data Visualization**: Visualize data in real-time with interactive charts and graphs.
- **Dynamic Dashboard**: Customize and save personalized dashboards to monitor specific metrics.
- **Data Upload and Processing**: Upload data files (e.g., CSV) for immediate visualization and analysis.

## Contributing 🤝

We welcome contributions to improve the **Interactive Data Visualization Portfolio**. To contribute:

1. **Fork the repository**.
2. **Create a new branch** for your feature or bugfix:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. **Commit your changes**:
    ```bash
    git commit -m "Description of your changes"
    ```
4. **Push to the branch**:
    ```bash
    git push origin feature/your-feature-name
    ```
5. **Open a pull request** and describe your changes.

## Languages and Tools 💻

- **Python**: Backend development
- **Flask**: Web framework
- **Flask-SocketIO**: Real-time communication
- **D3.js**: Data visualization library
- **HTML/CSS**: Frontend development
- **JavaScript**: Frontend interactivity


## Related Projects 🗃️

- [D3.js](https://d3js.org/): The JavaScript library used for data visualizations.
- [Flask](https://flask.palletsprojects.com/): The web framework used for the backend.
- [Flask-SocketIO](https://flask-socketio.readthedocs.io/): The extension used for real-time communication.

## Licensing 🔒

Author: Michelle Penane 👩

---

Thank you for visiting the **Interactive Data Visualization Portfolio** project! If you have any questions or feedback, feel free to reach out through the contact information provided on the project’s landing page.
