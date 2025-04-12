Birthday Love Letter 💌
A heartwarming surprise for your loved one on their special day! This interactive web app lets you take your partner through a mini-quest, filled with fun moments and charming animations, leading up to a beautiful love letter. Because, after all, every moment with them is a romantic adventure.

Features 🌟
Mini Quest: A sweet journey where your partner answers questions about the most romantic moments you’ve shared.

3 Chances: Three attempts to answer, with playful wrong answers that make the experience even more special.

Beautiful Animations: Lottie animations bring the quest to life, with a heartwarming touch every time they answer wrong.

Responsive Design: Fully optimized for all devices, ensuring the surprise works anywhere.

Love Letter: After completing the quest, they’ll discover a heartfelt love letter, wrapping up the surprise.

Tech Stack 💻
Next.js: For building the app with ease.

Tailwind CSS: Stylish, modern, and responsive design made simple.

Lottie: Beautiful animations to make the quest unforgettable.

React: For building a smooth, interactive experience.

How to Get Started 💡
Prerequisites
Make sure you have these installed:

Node.js (latest LTS version)

npm (Node Package Manager)

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/birthdayloveletter.git
Navigate into the project directory:

bash
Copy
Edit
cd birthdayloveletter
Install dependencies:

bash
Copy
Edit
npm install
Run the app locally:

bash
Copy
Edit
npm run dev
Visit http://localhost:3000 to see the magic unfold.

Production Build
To build for production:

bash
Copy
Edit
npm run build
npm start
Customizing the Animations ✨
To make the experience even more special, swap out the default animations (heartAnimation.json and wrongAnimation.json) with your own in the public/animations folder.

Folder Structure 🌷
bash
Copy
Edit
/public
    /animations
        heartAnimation.json      # Heart animation when the adventure begins
        wrongAnimation.json      # Animation for wrong answers
/src
    /app
        page.tsx                # The main page with the quest and love letter
    /components
        Quest.tsx               # The mini-quest component
        LoveLetter.tsx          # The love letter component
    /styles
        globals.css             # Global styles with Tailwind
License
This project is open-source and available under the MIT License.