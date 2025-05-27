# Little Rewards

## Description
**Little Rewards** is an intuitive **task and reward** program designed to help parents nurture positive habits and responsible behavior in children aged 4 to 10. This engaging platform fosters motivation and achievement—both academically and in everyday tasks—by offering small but meaningful rewards. Whether encouraging kindness, perseverance, or household responsibility, **Little Rewards** transforms goal-setting into a fun and structured experience.

At its core, the program streamlines task assignment and reward selection, allowing parents to tailor challenges to suit their child’s development stage. By reinforcing good behavior through **thoughtful incentives and guided strategies**, the platform empowers parents to instill essential life skills while making learning and personal growth engaging.

## Features 
1. Home - Introduction to the platform
2. About - Purpose and structure
3. Tasks - Details on tasks selection
4. Rewards - Reward Tier and Incentives
5. Contact - How users can reach out

## AI Role
Artificial intelligence played a crucial role in shaping and refining the development of Little Rewards. From assisting in conceptualizing the program’s framework to enhancing written content, AI provided valuable insights and creative support throughout the process. By leveraging AI-driven tools, the project benefited from streamlined content creation, ensuring clarity, coherence, and accessibility for parents seeking guidance on reward-based learning. AI also contributed to refining task structures, improving descriptions, and optimizing the overall user experience—helping to make Little Rewards an engaging and effective platform for families.

Beyond content generation, AI enabled efficiency in idea development and iterative improvements, making it easier to fine-tune key aspects of the program. Whether it was crafting user-friendly instructions, enhancing communication strategies, or ensuring inclusivity in language and tone, AI-assisted refinement helped align the project with its core mission. AI was particularly instrumental in shaping both the Task and Rewards pages, helping to structure tasks in a way that encourages motivation while ensuring the rewards system is exciting and meaningful. AI-powered image generation also played a key role in creating visually appealing reward images, reinforcing the idea that positive reinforcement can be both engaging and rewarding. While human creativity and parental intuition remain at the heart of Little Rewards, AI served as an invaluable collaborator—bringing precision, adaptability, and innovation to the process. This partnership between human-driven insight and AI-powered support has helped shape a thoughtful and practical resource for families seeking to encourage positive habits in their children.

## How It Works?
Little Rewards is designed to be simple, user-friendly, and easy to navigate, ensuring parents can seamlessly guide their children through the task-and-reward process. The journey begins on the **Home** page, where users can review the available information and use the navigation buttons to explore further.

When reaching the **Task** page, parents can browse and select tasks suited to their child’s abilities and developmental stage, making a note of their choices for easy reference. The **Reward** page provides examples of tasks corresponding to specific Reward Tiers, helping parents match completed tasks with appropriate incentives. Parents are encouraged to use their discretion in assigning rewards that reflect the effort and difficulty of the tasks completed. Once the process is complete, a simple click on the **Thank You** button wraps up the experience, allowing families to celebrate achievements and encourage continued motivation.

## Website Address
The deployed website can be viewed at: https://mariama-ny21.github.io/little-rewards/

## Testing
One of the main problem faced when building Little Rewards was that the hero-section image on the home page was not showing in my workspace. Interestingly, it was always showing up in the web browser. I was however determined to fix the issue. After a good number of attempts in debugging, a solution was finally found after validating my CSS code. The issue was that the background: linear-gradient had one colour instead of two. Once both colours were present, the image in the hero-section showed up in my workspace. Problem solved! 
 
## Lighthouse Report Screenshots
![Local Image](assets\images\Screenshots\home-page-lighthouse.png) 
![Local Image](assets\images\Screenshots\about-page-lighthouse.png)
![Local Image](assets\images\Screenshots\reward-page-lighthouse.png)
![Local Image](assets\images\Screenshots\task-page-lighthouse.png)
![Local Image](assets\images\Screenshots\contact-page-lighthouse.png)

## W3C HTML Validator Screenshots
![Local Image](assets\images\Screenshots\html-validator_home.png)
![Local Image](assets\images\Screenshots\html-validator_about.png)
![Local Image](assets\images\Screenshots\html-validator_rewards.png)
![Local Image](assets\images\Screenshots\html-validator_tasks.png)
![Local Image](assets\images\Screenshots\html-validator_contact.png)

## Jigsaw W3C CSS Validator Screenshot
![Local Image](assets\images\Screenshots\jigsaw-css-validator_style.css.png)

## Key Updates
Home Page
- CSS style for the active nav links were updated to ensure links are visible when clicked 
- Css style for the navbar toggler icon was added to ensure that the navbar toggler icon is visible on smaller screens
- Hero image updated to a high resolution image with better quality and semi-transparent overlay added to ensure improved text visibility
- Text colour on hero image changed and font-size increased for enhanced redability 
- Buttons text font-size also increased to ensure readability
- Two Cards titles under the Key Highlight section were also updated
- The previous Parents and Guardians paragraph has been summarised using checkmark (✅) icon to highlight key points

JavaScript Addition
- Add event listener to the home page buttons

About Page
- A medium blue background colour added to the About page which gives it a fresher look and the text are clearly visible

Rewards Page
The Rewards page was redesigned and the major changes includes the removal of the cards and the addition of a Bootstrap carousel. The Example section was also restyled using a check list. The Thank You modal message was also updated.

Contact Page
The Contact Page redesigned by using Accordion for the FAQ and changing the Feedback form to Contact Us form. CSS style was also updated for the Contact page.

## Credits
- All images on the website are AI-generated, contributing to the vibrant and engaging visual experience of the program. 
- The JavaScript code used to collaps the menu when internal links are clicked was obtained from tuition materials.