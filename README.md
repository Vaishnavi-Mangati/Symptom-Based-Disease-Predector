# Symptom-Based Disease Predictor

## Overview
This application allows users to input symptoms and get predictions on possible diseases along with match rates. Users can also look up specific diseases for information, find nearby specialists or hospitals based on their location, and access precautionary measures.

## Features
- **Symptom-Based Disease Prediction:** Select symptoms to get a list of possible diseases with match rates.
- **Disease Lookup:** Search for a specific disease to get detailed information.
- **Nearby Hospital/Specialist Finder:** Uses user location to recommend nearby hospitals or specialists based on symptoms.
- **Precautionary Measures:** Provides guidance on how to handle suspected illnesses.
- **YouTube Integration:** Links to instructional videos for better understanding.

## Tech Stack
- **Frontend:** React.js
- **Backend:** Node.js with Express.js
- **Database:** PostgreSQL (via Supabase)
- **Hosting & API Management:** Supabase for database and authentication
- **Location Services:** Integrated with location-based APIs to fetch nearby medical facilities

## Setup Instructions
### Prerequisites
- Node.js and npm installed
- Supabase account and project set up
- API keys for location services (if applicable)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Symptom-Based-Disease-Predector.git
   cd your-project-folder
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables:
   - Create a `.env` file in the root directory
   - Add Supabase credentials and API keys
4. Start the development server:
   ```sh
   npm start
   ```

## Usage
1. Open the app in your browser.
2. Enter symptoms to get disease predictions.
3. Search for a specific disease to get details.
4. Allow location access to find nearby hospitals or specialists.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.

---
Feel free to update this README with additional details as the project evolves!

