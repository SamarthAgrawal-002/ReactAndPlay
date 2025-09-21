🎭 Dumb Charades Online  
Relive childhood memories. Play anytime, anywhere.



 About the Project
Dumb Charades Online is a fun, family-friendly game that brings people together across distances.  
Inspired by the classic childhood game of acting and guessing movies, our platform makes it possible for friends and families to connect, laugh, and compete — no matter where they are.  

Built for the Google Developer Society Hackathon, this project is designed to be:  
 Simple – quick to join and play  
 Engaging – relive the nostalgia of offline charades  
 Accessible – works on the web, no installs required  



Key Features
 Create or join private game rooms  
 Random movie prompts for acting  
 Built-in timer for each round  
 Scoreboard to track guesses  
 Play with family and friends from anywhere  


Designs
All screens and flows were designed in Figma with a focus on clean, bold, and nostalgic visuals.  

 [View Figma Prototype](https://figma.com/)  



 Tech Stack
 Frontend: React (exported via Lovable)  
 Database: Supabase (realtime game state, players, prompts)  
 Hosting: Vercel (GitHub auto-deploy)  
 Design: Figma  
 Collaboration: GitHub  



Live Demo
Try it out here (hosted on Vercel):  
[Play Dumb Charades Online](https://your-vercel-app.vercel.app)  



 Database Schema (Supabase)
  rooms → stores active rooms & codes  
  players → player details & scores  
  prompts → movie prompts for the game  

Schema export: [`/database/schema.sql`](./database/schema.sql)  

Screenshots
| Landing Page | Game Room | Scoreboard |

| ![Landing](./demo/landing.png) | ![Room](./demo/room.png) | ![Scoreboard](./demo/scoreboard.png) |


Team
Hackathon project by [Your Team Name]
 [Member 1 Name] – Idea & Design  
 [Member 2 Name] – Frontend Dev  
 [Member 3 Name] – Backend & Supabase  
 [Member 4 Name] – Pitch & Docs  


Contributing
Want to improve this game? Fork the repo, create a feature branch, and send a pull request.  

bash
git clone https://github.com/<your-username>/dumb-charades-online.git
cd dumb-charades-online
