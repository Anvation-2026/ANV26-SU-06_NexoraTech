# VoltGrid — EV Charging Optimizer

## About
VoltGrid optimizes EV fleet charging based on electricity prices, grid capacity, solar energy, battery constraints, and vehicle priorities.

## Features
- Fleet and charger management
- Smart charging optimization
- Solar and tariff integration
- Live Digital Twin of the EV depot
- Live charging simulation and monitoring
- Charging schedules and compliance reports
- Naive vs Optimized comparison

## Tech Stack
- Frontend: Next.js, TypeScript, Tailwind CSS
- Backend and database: Supabase
- Optimization: Python, SciPy, HiGHS
- Charts: Recharts

## Setup
1. Install Node.js and Python.
2. Create a Supabase project.
3. Add Supabase credentials to `.env.local`.
4. Run the SQL migration to create database tables.
5. Install dependencies using `npm install`.
6. Start the frontend using `npm run dev`.
7. Start the Python optimization service.

## Digital Twin
Vehicles appear immediately when added to the fleet, even before optimization. The Digital Twin displays simulated vehicle movement, charger assignments, SOC, and charging status.

## Disclaimer
VoltGrid is a software simulation. It does not control physical vehicles or chargers.
