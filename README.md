# Little Rewards

## Table of Contents
1. Introduction
2. Project Overview
3. UX/UI Design
4. Features
5. Usage Instructions
6. Technologies Used
7. Tools Used
8. Testing
9. Deployment
10. AI Assistance
11. Challenges and Learnings
12. Credits
13. Key Updates

1️. Introduction

Little Rewards is an engaging task and reward system designed to help children aged 4 to 10 to develop responsibility, perseverance, kindness, and a sense of achievement in both academic and everyday settings. By offering small but meaningful incentives, the program motivates kids to complete tasks like homework, chores, and acts of kindness, transforming goal-setting into a fun experience. Parents can personalise challenges to match their child's development, reinforcing positive behavior through structured guidance and thoughtful rewards. With a colorful, intuitive interface, uplifting visuals, and a smooth user experience, Little Rewards makes learning and personal growth exciting, rewarding, and impactful. Experience Little Rewards firsthand! Visit the deployed site here: [Live Demo](https://mariama-ny21.github.io/little-rewards)

2️. Project Overview

The main objective is to develop a website using HTML and CSS. The inspiration behind Little Rewards came from the need to make learning, chores, and good behavior more engaging for kids. This system helps parents guide children through everyday tasks while reinforcing accomplishments with fun rewards.

3️. UX/UI Design

- The design prioritises simplicity and child-friendly visuals:
- Warm vibrant colours such as gold, darkorange, blue and navy are used throughout the site to enhance motivation
- Readable fonts (Macondo, cursive & Livvic, sans-serif) and colorful visuals used to capture attention
- Accessible navigation for both parents and kids
- Responsive layout for seamless experience on desktop and mobile

4. Features

Core features include:
- Home - Introduction to the platform
- About - Purpose and structure
- Tasks - Details of different task category
- Rewards - Reward Tier and Incentives
- Contact - FAQ and how users can reach out
- Interactive UI: Simple, engaging, and motivating images to encourage progress

5. How It Works?

Little Rewards is designed to be an intuitive and seamless task-and-reward system, helping parents guide their children through positive habit-building in a structured yet engaging way. The journey begins on the Home page, where users can review key information and navigate easily. On the Task page, parents select tasks suited to their child’s abilities and developmental stage, ensuring personalised learning experiences. The Reward page provides examples of incentives based on completed tasks, allowing parents to tailor rewards according to effort and difficulty. A simple click on the Thank You button marks the completion of the process, fostering motivation, celebration, and continued positive reinforcement for families. For more additional information, please see the FAQ section on the Contact page.

6. Technologies Used

Little Rewards is built using:
- Frontend: HTML, CSS, and a little JavaScript (for dynamic interactions)

7. Tools Used

Development and design tools:
- Visual Studio Code (coding environment)
- Lighthouse (performance analysis)
- GitHub (version control)

8. Testing

Testing ensures a smooth experience:
Little Rewards undergoes testing to ensure a smooth experience for both children and parents, making navigation simple and intuitive. Additionally, performance analysis through Lighthouse reports helps optimize speed and responsiveness, while cross-browser and mobile testing guarantees seamless compatibility across different devices

One of the main problem faced when building Little Rewards was that the hero-section image on the home page was not showing in my workspace. Interestingly, it was always showing up in the web browser. I was however determined to fix the issue. After a good number of attempts in debugging, a solution was finally found after validating my CSS code using W3C CSS Validation Service. The issue was that the background: linear-gradient had one colour instead of two. Once both colours were present, the image in the hero-section showed up in my workspace. Problem solved! 
 
Lighthouse Report Screenshots
![home-page-lighthouse](https://github.com/user-attachments/assets/244d4037-e952-47d5-be9f-28968417cd57)
![about-page-lighthouse](https://github.com/user-attachments/assets/c04639c4-5889-4354-99ef-4abb1a50d017)
![task-page-lighthouse](https://github.com/user-attachments/assets/5c9ddd6e-a4a4-4bda-9962-67de79d2a10b)
![reward-page-lighthouse](https://github.com/user-attachments/assets/37b4d8a4-0aeb-4b3c-8f30-9f429157a9b6)
![contact-page-lighthouse](https://github.com/user-attachments/assets/b8c53686-f452-4df3-9fd6-11074928814d)

W3C HTML Validator Screenshots
![html-validator_home](https://github.com/user-attachments/assets/2372c6ce-01d8-49bb-8084-b0c283855b21)
![html-validator_about](https://github.com/user-attachments/assets/fc8ba905-c5eb-4e18-a882-2f9a1ebe83a2)
![html-validator_tasks](https://github.com/user-attachments/assets/53096ead-7140-4af7-8f4b-ffd4a746b9fb)
![html-validator_rewards](https://github.com/user-attachments/assets/4bfd0155-3c1f-428c-8e61-b95a55d0366f)
![html-validator_contact](https://github.com/user-attachments/assets/3507c338-71e7-4646-b85a-7936d3a84c48)


Jigsaw W3C CSS Validator Screenshot
![jigsaw-css-validator_style css](https://github.com/user-attachments/assets/2e90b6e3-9661-4c53-b299-6cec25e7e702)

9. Deployment

The deployed website can be viewed at: https://mariama-ny21.github.io/little-rewards/

10. AI Assistance

AI assisted with:
- AI streamlined idea development and communication strategies 
- AI helped refining written content for clarity and accessibility
- AI-powered image generation contributed to appealing reward graphics, reinforcing positive reinforcement
- While parental intuition remains at the heart of Little Rewards, AI played a key role as a collaborative tool, bringing precision, adaptability, and innovation to the development process
- AI also helped with debugging technical issues, ensuring smooth development process

11. Challenges and Learnings

Throughout the development, key challenges included:
- Finding solutions to technical issues
- Refining the reward logic—ensuring incentives align with appropriate Reward Tiers
- Improving accessibility for younger audiences

12 Credits

- All images on the website are AI-generated, contributing to the vibrant and engaging visual experience of the program. 
- The JavaScript code used to collaps the menu when internal links are clicked was obtained from tuition materials.

13 Key Updates

Home Page:
- CSS style for the active nav links were updated to ensure links are visible when clicked 
- Css style for the navbar toggler icon was added to ensure that the navbar toggler icon is visible on smaller screens
- Hero image updated to a high resolution image with better quality and semi-transparent overlay added to ensure improved text visibility
- Text colour on hero image changed, font-family changed and font-size increased for enhanced redability 
- Buttons text font-size also increased to ensure readability
- FAQ Contact Us button added to the hero image
- Two Cards titles under the Key Highlight section were also updated
- The previous Parents and Guardians paragraph has been summarised using checkmark (✅) icon to highlight key points
- JavaScript addition to the home page - event listeners added to the home page buttons

About Page:
- A medium blue background colour added to the About page which gives it a fresher look and the text are clearly visible

Rewards Page:
- The Rewards page was redesigned, and the major changes includes the addition of the previous cards into a Bootstrap carousel
- The Example section was also restyled using a check list
- The Thank You modal message was also updated

Contact Page:
- The Contact page was redesigned by using Accordion for the FAQ and changing the Feedback form to Contact Us form
- CSS style was also updated for the Contact page
- Footer adjusted on Contact page and other pages so that it occupies very little space

Screenshots:
- Lighthouse report generated for all pages; HTML and CSS validation done after all the changes were made
