# 🌤️ Weather Forecast API Testing with Postman

This project showcases manual and script-based API testing for a Weather Forecast service using **Postman**. The objective was to validate the correctness, performance, and stability of weather-related API endpoints.

## 🔍 What I Did
- Tested RESTful endpoints for current weather, 5-day forecast, and city-based search.
- Validated response codes (200, 400, 404, etc.) and data formats (JSON).
- Wrote test scripts in Postman to automate validations like temperature range, city name match, and error handling.
- Used environment variables and collection runners to simulate different test cases.
- Documented edge cases such as missing parameters, invalid city names, and API key errors.

## 🧪 Tools Used
- Postman
- JavaScript (for scripting tests)
- JSON
- REST API principles

## 📁 What's Included
- `WeatherAPI.postman_collection.json`: Main collection with all test cases
- `WeatherAPI.postman_environment.json`: Environment file with base URL and variables
- `README.md`: Project overview and usage

## 💡 How to Use
1. Import the collection and environment into Postman.
2. Set your API key in the environment.
3. Run the collection using Postman or Newman (optional).
4. Check test results in the Test Results tab.

## 📄 Sample Test Scenarios
- ✅ Verify response for a valid city
- ❌ Verify error for an invalid city
- 🔄 Test data-driven city inputs
- ⚠️ Test response time and status codes

## 🤝 Contributing
Suggestions and improvements are welcome!

---

Let me know if you'd like a sample `.postman_collection.json` file structure or want me to generate it.
