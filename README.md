# Interactive Data Visualization Portfolio - MVP Specification

<img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*Qn4sp28csHcEGfnv-AoIHw.png" alt="Description of the image">

## Introduction 👋

Welcome to the **Interactive Data Visualization Portfolio** project. This platform was born out of my passion for leveraging complex data in chemistry and transforming it into meaningful insights through interactive visualizations. As a chemist, I often found myself overwhelmed with data that required deeper analysis than conventional tools could provide. This project aims to bridge that gap by offering a user-friendly interface where data can be visualized, analyzed, and interpreted in real-time.

- **Deployed Project Application**: [Interactive Data Visualization Portfolio](https://github.com/Tentswalo/Tentswalo.io)
- **Final Project Blog Article**: [Project Blog Article](https://medium.com/@mpenane1/the-purpose-of-the-interactive-data-visualization-portfolio-is-to-create-a-robust-user-friendly-6bb62913aa6d )

## Inspiration and Technical Challenge 💡
The inspiration for this project came from my experience as a chemist grappling with large datasets. I set out to create a tool that not only visualizes data but also allows for interactive exploration and analysis. One of the significant technical challenges I faced was designing an efficient data processing pipeline that could handle diverse data formats seamlessly. I chose to implement Data Visualization Library
- Chosen Technology: Plotly
- Alternative: Matplotlib

The Plotly Advantages is that it provides built-in support for interactive graphs and visualizations, which are essential for creating a user-friendly and dynamic web application. It is also seamlessly integrated with Dash, which makes it easier to create web applications with interactive plots. While the Matplotlib Advantages are simplicity and that It's one of the most widely used plotting libraries in Python with a large community and many resources available. Taking into account the trade-offs, Plotly is more complex and has a steeper learning curve compared to Matplotlib. However, the interactivity offered by Plotly outweighs the simplicity of Matplotlib for this project, leading to the decision to use Plotly for its advanced features and ease of creating interactive visualizations.

## A Story Demo Video 🎬 🎥 🔴 ▶

Check out a quick demo which features an honest overview of the struggles faced and what I envision for a next-iteration:

[![A story Demo Video](https://img.youtube.com/vi/FnlQBUePh8c/0.jpg)](https://www.youtube.com/watch?v=FnlQBUePh8c)

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

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

Author: Michelle Penane 👩

---

Thank you for visiting the **Interactive Data Visualization Portfolio** project! If you have any questions or feedback, feel free to reach out through the contact information provided on the project’s landing page.
