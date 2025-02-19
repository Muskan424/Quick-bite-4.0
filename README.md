# 📦 Food Delivery App with 24/7 AI Consultancy

## 🚀 Overview
This is a *food delivery app* developed for a hackathon, integrated with *Meta AI* to provide *24/7 AI-powered consultancy*. The AI assistant helps customers with order-related queries, restaurant recommendations, and general food-related guidance.

## 🛠 Tech Stack
- *Frontend:* React Native / Flutter
- *Backend:* Node.js / Express
- *Database:* MongoDB / Firebase
- *AI Integration:* Meta AI (LLM-based chatbot)
- *Hosting:* AWS / Vercel / Firebase

## 🔗 Features
✅ *24/7 AI Consultancy* using Meta AI for instant customer support.  
✅ *Smart Recommendations* based on user preferences and past orders.  
✅ *Live Order Tracking* with real-time updates.  
✅ *Secure Payments* with multiple gateway options.  
✅ *Restaurant & Food Suggestions* based on AI insights.

## 🛠 Setup & Installation
1. Clone this repository:
   sh
   git clone https://github.com/your-repo/food-delivery-app.git
   cd food-delivery-app
   

2. Install dependencies:
   sh
   npm install  # or yarn install
   

3. Set up environment variables (.env file):
   sh
   META_AI_API_KEY=your_meta_ai_api_key
   

4. Run the development server:
   sh
   npm start  # or yarn start
   

## 🎯 AI Integration
We have integrated *Meta AI* to provide a seamless user experience. It helps in:
- Answering common user queries.
- Giving food suggestions based on taste preferences.
- Providing restaurant recommendations.

### Example API Call to Meta AI
js
fetch('https://api.meta.com/v1/chat', {
  method: 'POST',
  headers: {
    'Authorization': `Bearer ${process.env.META_AI_API_KEY}`,
    'Content-Type': 'application/json'
  },
  body: JSON.stringify({
    prompt: 'Suggest a good Italian restaurant near me.',
    max_tokens: 100
  })
})
.then(response => response.json())
.then(data => console.log(data));


## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙌 Acknowledgments
Special thanks to *Meta AI* for providing powerful AI capabilities for seamless customer support.

---
Feel free to modify as per your project’s needs! 🚀
