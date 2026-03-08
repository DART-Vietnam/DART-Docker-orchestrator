# DART Docker orchestrator

Simple Docker Compose file setup to orchestra DART containers, including:
- [`DART-Caddy`](https://github.com/DART-Vietnam/DART-Caddy), for reverse proxying requests to the different web-apps
- [`DART-Vis-app`](https://github.com/DART-Vietnam/DART-Vis-app), web-app for the DART Visualisation work package
- [`DART-Pipeline-GUI`](https://github.com/DART-Vietnam/DART-Pipeline-GUI), Python-based Streamlit web-app, a thin GUI wrapper for [`DART-Pipeline`](https://github.com/kraemer-lab/DART-Pipeline)
- [`DART-Forecasting`](https://github.com/DART-Vietnam/DART-Forecasting), the dengue incidence forecasting work package, packaged into a container using tuned ML learners

