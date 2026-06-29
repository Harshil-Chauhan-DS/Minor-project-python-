# Minor-project-python
Unlox Academy Minor Project 1 of the data science course, showcasing basic data analytics and data handling
# GroupDNA - Whatsapp Group Chat decoder
A Python tool that reads a WhatsApp chat export and generates a full personality and activity report about your group — who spams, who ghosts, who's up at 3am, and what words you're all obsessed with.
  
**Name:** Harshil Chauhan
  
**Personal Output ScreenShots**
<img width="635" height="720" alt="Screenshot 2026-06-29 155858" src="https://github.com/user-attachments/assets/f759325d-e59c-462d-8363-5e71811b0d1f" />

<img width="608" height="616" alt="Screenshot 2026-06-29 155915" src="https://github.com/user-attachments/assets/6a69a7d0-31bc-4966-9f9b-0f8d0083a3c4" />

<img width="627" height="386" alt="Screenshot 2026-06-29 155933" src="https://github.com/user-attachments/assets/53358a7b-1ae6-4803-af2b-f430ae5073cd" />

<img width="667" height="492" alt="Screenshot 2026-06-29 155941" src="https://github.com/user-attachments/assets/877d2233-4b10-47b2-b795-5cc270cff53c" />

(Names are redacted for privacy reasons)
# What it does
Reads a raw WhatsApp .txt export and produces:
Group overview with message counts per person
Most active day and hour (with a full 24-hour bar chart)
Activity heatmap built using NumPy (6 people × 24 hours)
Top 10 most used words across the group
Top word per person
Average response time and fastest/slowest replier
Longest silent streaks per person
Personality archetype for every member (Spammer, Group Mom, Night Owl, Storyteller, Drama Queen, Ghost, Comedian, Question Master)
Full archetype score breakdown

# Constraints followed:
No pandas
No matplotlib
No collections.Counter
No regex
Only Python fundamentals + NumPy + datetime
To run on your own WhatsApp chat:

# how to run
Open any WhatsApp group → three dots → More → Export chat → Without media
Save the .txt file next to the notebook
Enter the filename
