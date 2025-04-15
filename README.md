# Enhanced Coaching Dashboard

A comprehensive coaching dashboard application for fitness professionals to manage their clients. This dashboard includes detailed tracking of nutrition protocols, training programs, cardio protocols, body measurements, weekly check-ins, and more.

## Features

- **Client Management**: Track all your clients in one place
- **Comprehensive Dashboard**: Visual overview of client progress and metrics
- **Nutrition Tracking**: Detailed nutrition protocol management
- **Training Programs**: Track exercise programs, volume, and progression
- **Body Measurements**: Monitor and visualize changes in body measurements
- **Weekly Check-ins**: Streamlined process for client check-ins
- **Health Markers**: Track important health indicators
- **PED Program Management**: Secure tracking of PED protocols
- **Goal Setting**: Set and monitor short, medium, and long-term goals
- **Visual Analytics**: Charts and graphs to visualize progress

## Technology Stack

- **Frontend**: React.js with Hooks
- **Routing**: React Router
- **Styling**: Tailwind CSS
- **Charts**: Recharts
- **Icons**: Lucide React
- **HTTP Client**: Axios
- **State Management**: React Context API

## Getting Started

### Prerequisites

- Node.js (v14+)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/alaweimm/coaching-app.git
   cd coaching-app
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```bash
   npm start
   # or
   yarn start
   ```

4. The application will be available at [http://localhost:3000](http://localhost:3000)

### Environment Variables

Create a `.env` file in the root directory with the following variables:

```
REACT_APP_API_BASE_URL=http://localhost:3001/api
```

## Project Structure

```
coaching-app/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── Header.js
│   │   ├── Sidebar.js
│   │   ├── Login.js
│   │   ├── ClientsList.js
│   │   └── ...
│   ├── context/
│   │   └── ClientContext.js
│   ├── services/
│   │   └── api.js
│   ├── App.js
│   ├── EnhancedDashboard.js
│   ├── index.js
│   └── index.css
├── package.json
├── tailwind.config.js
└── README.md
```

## Backend API

This frontend application is designed to connect to a RESTful API. The API endpoints follow this structure:

- **Authentication**: `/api/auth/login`
- **Clients**: `/api/clients`
- **Client Data**: `/api/clients/:id`
- **Measurements**: `/api/clients/:id/measurements`
- **Nutrition**: `/api/clients/:id/nutrition`
- **Training**: `/api/clients/:id/training`
- **Check-ins**: `/api/clients/:id/checkins`
- **Goals**: `/api/clients/:id/goals`
- **Health Markers**: `/api/clients/:id/health-markers`
- **Supplements**: `/api/clients/:id/supplements`
- **PED Program**: `/api/clients/:id/ped-program`

## License

This project is licensed under the MIT License.

## Acknowledgements

- Created by Meshal Alawein
- Dashboard design inspiration from various fitness coaching applications
