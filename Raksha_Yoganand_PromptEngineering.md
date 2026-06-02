# Prompt Engineering Portfolio

Name: Raksha Yoganand

Date: June 2026

LLM Used: ChatGPT (GPT-5.5)

---

## Part 1: Prompt Design & Iteration

### 1.1 Scenario A: Technical Explanation
Goal: Explain a complex technical concept (e.g., "blockchain", "neural networks", "recursion") to a 10-year-old

Initial Prompt: Explain blockchain to a child.

Refined Prompt: 1)You are an elementary school teacher. Explain blockchain to a 10-year-old using a story and simple examples. Avoid technical jargon.
2)You are an award-winning elementary school teacher. Explain blockchain to a 10-year-old using a classroom notebook analogy. Use simple language, one example, and end with a 3-point summary.

Final Output: Blockchain: The Classroom Notebook Story 📒

Imagine your class has a special notebook that records important things, like who earned classroom points.

Every student has a copy of the same notebook.

One day, your teacher gives Emma 5 points for helping clean the classroom.

Everyone writes in their notebook:

"Emma earned 5 points."

Now all the notebooks match.

Later, Emma gives 2 points to Noah as a reward for helping with a project. Everyone checks that Emma really has enough points, and then they all write:

"Emma gave 2 points to Noah."

Because everyone has the same record, nobody can secretly change the notebook and claim extra points. If someone writes something different, the rest of the class can see that it doesn't match their copies.

A blockchain works in a similar way. It's a shared record where many people keep copies of the same information. When something new happens, everyone updates their records so they stay in agreement.

3-Point Summary
Blockchain is a shared notebook that many people keep copies of.
New actions are recorded for everyone to see and check.
It is difficult to cheat because many copies of the record must agree.

### 1.1 Scenario B: Professional Email
Goal: Draft an email declining a job offer politely while expressing continued interest in the company

Initial Prompt: Write an email declining a job offer politely.

Refined Prompt:1)Write a professional email declining a job offer from a company.
Thank them for the opportunity and explain that I have decided to accept another position.
Keep the tone respectful and appreciative.
2)You are a professional career advisor.
Write a polite and professional email declining a job offer from a company because I have accepted another opportunity.
Thank the hiring team for their time and confidence in me.
Express genuine appreciation for the interview process.
Mention that I remain interested in the company and would welcome opportunities to work together in the future.
Use a warm, respectful, and professional tone.

Final Output: 
Dear Hiring Team,

I hope you are doing well.

Thank you very much for offering me the opportunity to join your organization. I sincerely appreciate the time, effort, and consideration that you and the team invested throughout the recruitment process.

It was a pleasure getting to learn more about the company, the role, and the talented individuals I had the opportunity to meet during the interview process. I was truly impressed by the professionalism, culture, and vision of the organization.

After careful consideration, I have decided to decline the offer, as I have accepted another opportunity that aligns with my current career goals. This was not an easy decision, given the positive experience I had throughout the hiring process and the confidence your team placed in me.

I am genuinely grateful for the opportunity and for the trust you showed in my abilities. I hold your organization in high regard and remain very interested in the company. I would welcome the possibility of working together in the future should our paths cross again.

Thank you once again for your time, understanding, and consideration. I wish you and the team continued success, and I hope to stay connected.

Warm regards,

[Your Name]

### 1.1 Scenario C: Creative Content
Goal: Generate a creative marketing tagline for a new eco-friendly water bottle brand
Initial Prompt: Create a tagline for an eco-friendly water bottle brand.
Refined Prompt: 1)Create 10 marketing taglines for a reusable eco-friendly water bottle.
The brand promotes sustainability and reducing plastic waste.
The taglines should be catchy and memorable.
2)You are an award-winning marketing copywriter.
Create 10 short and memorable taglines for a premium eco-friendly water bottle brand aimed at environmentally conscious young professionals.
The taglines should:
- Be fewer than 6 words
- Sound modern and inspiring
- Emphasize sustainability and everyday use
- Be easy to remember
Final Output:
1)Sip Smarter. Live Greener.
2)Refill Today. Renew Tomorrow.
3)Carry Change Every Day.
4)Sustainability in Every Sip.
5)Drink Well. Tread Lightly.
6)Made for Daily Impact.
7)Your Bottle. Better Future.
8)Refill. Reuse. Rise.
9)Hydrate with Purpose.
10)Every Sip Counts. 🌿💧
### 1.2 Iteration Documentation
A)
| Version | Prompt                                                                                                                                                                                        | What Changed                                                           | Why This Improved the Output                                                                                                     |
| ------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| V1      | Explain blockchain to a child.                                                                                                                                                                | Initial prompt.                                                        | Produced a simple explanation but was somewhat generic and less engaging.                                                        |
| V2      | You are an elementary school teacher. Explain blockchain to a 10-year-old using a story and simple examples. Avoid technical jargon.                                                          | Added role assignment and storytelling instructions.                   | The explanation became more engaging, age-appropriate, and easier to understand through the sticker-trading story.               |
| V3      | You are an award-winning elementary school teacher. Explain blockchain to a 10-year-old using a classroom notebook analogy. Use simple language, one example, and end with a 3-point summary. | Added a specific analogy, example requirement, and structured summary. | The response became more focused, memorable, and well-organized, making it easier for a child to learn and remember the concept. |

B)
| Version | Prompt                                                         | What Changed                | Why This Improved the Output                                      |
| ------- | -------------------------------------------------------------- | --------------------------- | ----------------------------------------------------------------- |
| V1      | Write an email declining a job offer politely.                 | Initial prompt.             | Produced a basic email but lacked detail and personalization.     |
| V2      | Added appreciation and reason for declining.                   | More context.               | Made the email more professional and realistic.                   |
| V3      | Added role assignment, future interest, and tone requirements. | More specific instructions. | Generated a polished email with a professional and positive tone. |


C)

| Version | Prompt                                                              | What Changed                  | Why This Improved the Output                                                   |
| ------- | ------------------------------------------------------------------- | ----------------------------- | ------------------------------------------------------------------------------ |
| V1      | Create a tagline for an eco-friendly water bottle brand.            | Initial prompt.               | Produced a generic tagline.                                                    |
| V2      | Added sustainability focus and requested multiple taglines.         | More context.                 | Generated more relevant and creative ideas.                                    |
| V3      | Added role assignment, target audience, word limit, and brand tone. | Highly specific instructions. | Produced concise, memorable, and marketable taglines tailored to the audience. |


### 1.3 Role and Context Analysis
Role assignment and context setting significantly improved the quality of the generated responses. In Scenario A, assigning the role of an elementary school teacher helped the model explain blockchain using simple language, relatable examples, and age-appropriate analogies. In Scenario B, assigning the role of a professional career advisor resulted in a more polished and professional email that maintained a respectful tone while expressing future interest in the company. In Scenario C, providing the role of an award-winning marketing copywriter and specifying the target audience helped generate concise, memorable taglines that aligned with the brand's sustainability goals and appealed to environmentally conscious young professionals.


## Part 2: Temperature & Parameter Control

### 2.1 Temperature Experimentation

### 2.2 Analysis & Recommendations

---

## Part 3: Strategic Prompting Techniques

### 3.1 Chain-of-Thought Prompting

### 3.2 Few-Shot Prompting

---

## Part 4: Responsible AI & Limitations

### 4.1 Testing for Hallucinations

### 4.2 Testing for Bias

### 4.3 Limitations & Responsible Use
