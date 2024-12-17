# WeezLeagues

WeezLeagues is a fantasy football companion website designed to enhance features missing from the Sleeper platform. This project includes a React frontend (`frontend_weezleagues`) and a Django backend (`backend_weezleagues`).

## Project Goals

### Current Focus

- **Display a Table of Players**:
  - Sort players by their recent fantasy output.
  - Toggle between player positions (e.g., QB, RB, WR, TE) at the top of the table.
  - Filter players based on a selected week range.

### Technology Stack

- **Frontend**:
  - React with MUI X DataGrid for table display.
  - Features include sorting, toggling, and filtering.
- **Backend**:
  - Django for managing data and APIs.
  - Integration with fantasy football data sources (e.g., Sleeper API).

## Setup Instructions

### Prerequisites

- Node.js and npm installed for the frontend.
- Python and virtual environment setup for the backend.

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd WeezLeagues
   ```
2. Set up the backend:

   ```bash
   cd backend_weezleagues
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   pip install -r requirements.txt
   python manage.py migrate
   ```
3. Set up the frontend:

   ```bash
   cd ../frontend_weezleagues
   npm install
   npm start
   ```

## Features in Progress

- **Player Table**:
  - MUI X DataGrid demo in place.
  - Adding functionality for toggling positions and week range filtering.

## Future Plans

- Additional analysis tools for team and player performance.
- Enhanced league visualization and insights.
- Integration with Sleeper's API to pull real-time data.

---

Feel free to contribute or suggest ideas to make WeezLeagues the ultimate fantasy football companion!
