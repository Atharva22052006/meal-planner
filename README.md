# Meal Planner Application

A Flask-based meal planning application that generates personalized meal plans.

## Local Development

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Set up environment variables:
- Create a `.env` file with:
  ```
  FLASK_SECRET_KEY=your-secret-key
  GEMINI_API_KEY=your-gemini-api-key
  ```

3. Run the application:
```bash
python app.py
```

## API Endpoints

### Generate Meal Plan
- **URL**: `/api/generate_meal_plan`
- **Method**: `POST`
- **Body**: JSON object containing user data
- **Response**: JSON object containing meal plan

## Required Environment Variables
- `FLASK_SECRET_KEY`: Secret key for Flask session
- `GEMINI_API_KEY`: API key for Gemini AI 