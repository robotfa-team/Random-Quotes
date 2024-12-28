# Random Quotes API - Free

## Introduction
The Random Quotes API is a free and simple tool designed to deliver inspiring, humorous, or thought-provoking quotes. With this API, developers can seamlessly integrate random quotes into their applications, websites, or services.

---

## Key Features
- **Random Quote Retrieval**: Fetch random quotes on-demand.
- **Inspirational Content**: Access quotes from a diverse range of topics and authors.
- **Free and Easy to Use**: No complex setup required, perfect for quick integration.

---

## Applications
- **Motivational Tools**: Add daily quotes to productivity apps or websites.
- **Creative Writing**: Provide inspiration for writers and content creators.
- **Entertainment**: Share fun and interesting quotes in your app or social media platforms.

---

## Getting Started

### Requirements
- A RapidAPI account.

### Steps to Access
1. **Sign Up on RapidAPI**
   - Visit [RapidAPI](https://rapidapi.com/robotfa-robotma/api/multilingual-famous-quotes/) and create a free account.

2. **Subscribe to the Random Quotes API**
   - Search for "Random Quotes API" on RapidAPI's marketplace.
   - Click "Subscribe" and choose the free plan.

3. **Get Your API Key**
   - Go to the "Endpoints" section of the API page on RapidAPI.
   - Copy your unique API key (token) from the dashboard.

4. **Start Making Requests**
   - Use your API key to authenticate your requests. Example:

     ```bash
     curl -X GET "https://multilingual-famous-quotes.p.rapidapi.com/random" \
     -H "X-RapidAPI-Key: YOUR_API_KEY" \
     -H "X-RapidAPI-Host: multilingual-famous-quotes.p.rapidapi.com"
     ```

---

## API Endpoints

### 1. Fetch a Random Quote
Retrieve a random quote:
```bash
GET /random
```
**Sample Response:**
```json
{
  "quote": "The only way to do great work is to love what you do.",
  "author": "Steve Jobs"
}
```


---

## Contribution
Contributions are welcome! If you have suggestions for new features or improvements, feel free to open an issue or submit a pull request.

---

## License
This API is provided under the MIT License. See the LICENSE file for more details.

