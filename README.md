# BookBuddy-
BookBuddy is your personalized book recommendation  chatbot that matches you with the perfect read based on your preference. Whether you're in the mood for a chilling horror novel, fun kid's,  gripping mystery or imagination fiction. BookBuddy makes finding your next favorite read effortless and accurate.


➡️*PROJECT STRUCTURE*

book-chatbot/
├── functions/
│   └── book-recommend.js
├── assistant/
│   └── dialog.json
├── data/
│   └── books.json (optional)
├── frontend/
│   └── index.html
├── README.md

➡️ How It Works (Flow)
1.User opens chatbot (web or IBM Watson Assistant interface)

2.User types message (e.g., "Can you recommend a mystery book?")

3.Watson Assistant processes intent (Book_Recommendation)

4.Cloud Function is triggered with parameters (genre = mystery)

5.Cloud Function calls Google Books API or uses data from Cloudant

6.Bot responds with a list of recommended books
