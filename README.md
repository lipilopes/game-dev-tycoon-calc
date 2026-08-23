# Game Dev Tycoon Helper

## 📌 About The Project

This project is a web-based companion tool for the popular simulation game **Game Dev Tycoon**. It is designed to help players maximize their review scores and sales by calculating the most optimal development combinations. By inputting a game topic, the application provides data-driven recommendations for genres, platforms, target audiences, and development stage slider allocations.

You can access the live version here: **[https://game-dev-tycoon.netlify.app](https://game-dev-tycoon.netlify.app)**.

## ✨ Features

* **Topic Selection:** Choose from a comprehensive dropdown list of game topics (e.g., Abstract, Aliens, Cyberpunk, Fantasy).


* **Genre Matching:** See how well different genres (Action, RPG, Simulation, etc.) pair with your selected topic, rated from low (`---`) to highly recommended (`+++`).


* **Target Audience & Platform Optimization:** Identifies the ideal age demographic (Young, Everyone, Mature) and the most compatible consoles for your specific genre and topic.


* **MVP Calculator (🌟 Melhor Combinação):** Automatically highlights the "perfect combination" where the topic, platform, genre, and audience perfectly align to create a highly successful game.


* **Development Stage Sliders:** Provides the exact percentage allocations needed for all three development phases (Engine, Gameplay, Story/Quests, Dialogs, Level Design, AI, World Design, Graphics, and Sound) based on the chosen genre.



## 🚀 How to Use

1. **Select a Topic:** Open the application and choose the game topic you want to develop from the dropdown menu.


2. **Choose a Genre:** Click on one of the recommended genre buttons that appear below the dropdown. (Genres with a green outline and `+++` are the best choices).


3. **Check the MVP (Optional):** If a perfect platform/audience match exists for your combination, it will appear at the top highlighted in green as the "Best Combination".


4. **Review Data:** Check the recommended target audiences and platforms displayed in the info panels.


5. **Set Your Sliders:** Scroll down to the "Fases Do Desenvolvimento" (Development Stages) section. Match the percentages shown in the progress bars with the sliders in your actual Game Dev Tycoon playthrough.



## 🛠️ Built With

This project is built using standard web technologies with no external libraries or frameworks required:

* **HTML5**

* **CSS3** (Custom properties, grid, and flexbox for styling)


* **Vanilla JavaScript** (Logic for filtering data and dynamically generating UI elements)



## 💻 Local Setup

Since this is a static web page, no complex installation is required.

1. Clone or download the repository.
2. Open the `index.html` file directly in any modern web browser.
