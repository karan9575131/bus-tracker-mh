🚀 Features

View available bus routes across Maharashtra

Choose boarding and destination stops

Calculates:

Total travel distance

Estimated travel time (based on avg speed = 55 km/h)

Next bus arrival (random 1–10 min simulation)

Fully interactive command-line interface

Simple loop-based implementation (no advanced libraries needed)

📌 Example Routes Included
South Maharashtra

Stops: wai → akkalcoate → satara → mahabaleshwar

Distances (km): 115, 45, 38

Central Maharashtra

Stops: pune → nashik → chakan → rajgurunagar → narayangao

Distances (km): 57, 111, 203, 115

North Maharashtra

Stops: dhule → shirpur → jalgaon

Distances (km): 99, 116

📂 Project Structure
📦 Bus Route Simulator
 └── transport_system.py

🧠 How It Works

User selects a bus route

User selects start & destination stops

Program calculates:

Total distance by summing segments

Travel time using formula:

time (minutes) = (distance / 55 km/h) * 60


Random bus arrival time (1–10 minutes) is generated

A travel summary is printed

▶️ Running the Program

Ensure you have Python 3 installed.

Run the script:
python transport_system.py

📷 Sample Output
=== BUS ARRIVAL maharashtra ===

Available Bus Routes:
1. South maharashtra
2. Central maharashtra
3. North maharashtra

Select a route number: 1

You selected: South maharashtra
Stops: wai → akkalcoate → satara → mahabaleshwar

Choose your boarding stop:
1. wai
2. akkalcoate
3. satara
4. mahabaleshwar
Start stop number: 1

Choose your destination stop:
1. wai
2. akkalcoate
3. satara
4. mahabaleshwar
Destination stop number: 3

=== RESULT ===
Next bus arrives in: 7 minutes
Distance between stops: 160 km
Estimated travel time: 175 minutes

Have a safe journey!

🛠️ Technologies Used

Python 3

Built-in modules only (random)

🤝 Contributions

Contributions, suggestions, and improvements are welcome!
Feel free to fork this repository and submit a pull request.

📜 License

This project is licensed under the MIT License.
Author-
Karan Kumar Gupta
