# GDSC Discord Bot 🚀  

This is a sDiscord bot made for the GDSC tech round 2 assignment.  
It includes basic commands, event handling, and API integration.

## Features  
Responds to commands (`!hello`, `!ping`, etc.)  
Integrates with the **Gemini API**   to add simple chatbot like features that can respond to simple questions like "rock, paper, scissors" or "how many colours in a rainbow?"

I created 3 seperate codes for implementing 3 seperate functionalities to the same bot. These codes do not work alongside yet(I tried fixing it) but individually they perform their respectiive tasks. The first code, simply reads discord messages, its sender and acknowledges a hello with a greeting. The second code allows the bot to play music and has features like start, stop, resume, join, leave. (this bot only works once you clear the first bot with a ctrl C on windows terminal and reload the bot on terminal. Finally, the last bot-code has google gemini integration alongside.

Currently, I am working on combining all 3 codes to make a single bot that can perform all these functions. I'm facing issues with VSCode so I switched to Idle which worked better(surprisingly). Before, the interview, I also aim to make my bot able to create polls, auto delete expired members, create-delete-modify reminders as well as make the AI commands more efficient. Most importantly, though, before the interview I want to be able to systematically hide my token and key from the main code so as to ensure security(for an actual real world bot).

## Installation & Setup  
To run this bot locally, follow these steps:

1. **Clone the repository**  
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
   cd YOUR_REPO
   
2. Install dependencies
bash
Copy code
pip install -r requirements.txt
(on windows Terminak)

3. Run the bot with changed tokens(becasue original token key is mine)
