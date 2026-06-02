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

#### Task Chosen

Explaining what photosynthesis is.

### Low Temperature (0.2)

#### Prompt

Explain what photosynthesis is. Be precise and consistent.

#### Output

Photosynthesis is the process by which green plants, algae, and some bacteria make their own food. During photosynthesis, plants use sunlight, water, and carbon dioxide to produce glucose (a type of sugar) and oxygen. This process mainly occurs in the leaves, where chlorophyll absorbs sunlight. Photosynthesis is important because it provides food for plants and releases oxygen into the atmosphere.

---

### Medium Temperature (0.7)

#### Prompt

Explain what photosynthesis is.

#### Output

Photosynthesis is the process that allows plants to make their own food using sunlight. Plants take in carbon dioxide from the air and water from the soil. Using energy from the sun, they convert these materials into glucose, which provides energy for growth and survival. As a result, oxygen is released into the air, making photosynthesis essential for life on Earth.

---

### High Temperature (1.2)

#### Prompt

Explain what photosynthesis is. Be creative and explore diverse ideas.

#### Output

Think of photosynthesis as a plant's own solar-powered kitchen. Plants collect sunlight like tiny solar panels, absorb water through their roots, and take in carbon dioxide from the air. Using these ingredients, they create glucose, which acts as food and energy for the plant. As a bonus, they release oxygen into the atmosphere, helping animals and humans breathe. Without photosynthesis, Earth would have far less food and oxygen, making life much more difficult.

---

### Comparison Table

| Temperature  | Style                 | Creativity | Detail Level | Characteristics                                |
| ------------ | --------------------- | ---------- | ------------ | ---------------------------------------------- |
| Low (0.2)    | Formal and factual    | Low        | High         | Precise, consistent, textbook-like explanation |
| Medium (0.7) | Balanced              | Medium     | Medium       | Clear explanation with some simplification     |
| High (1.2)   | Creative and engaging | High       | Medium       | Uses analogies and imaginative descriptions    |

### 2.2 Analysis & Recommendations
1)Low temperature is most useful when accuracy and consistency are important. Examples include generating programming code and explaining scientific or medical concepts where factual correctness is essential. 
2)High temperature is most useful for creative tasks such as writing stories and creating marketing slogans, where originality and variety are desired. 
3)For the photosynthesis task, the medium temperature worked best because it provided a clear and accurate explanation while remaining easy to understand. It balanced factual information with readability better than the low and high temperature outputs.

---

## Part 3: Strategic Prompting Techniques
### 3.1 Chain-of-Thought Prompting

#### Problem

If a train travels 120 km in 2 hours, then stops for 30 minutes, then travels another 90 km in 1.5 hours, what is its average speed for the entire journey?

### Without Chain-of-Thought

#### Prompt

Calculate the average speed for the following journey and provide only the final answer:

A train travels 120 km in 2 hours, stops for 30 minutes, and then travels another 90 km in 1.5 hours.

#### LLM Output

52.5 km/h

---

### With Chain-of-Thought

#### Prompt

Let's solve this step by step.

A train travels 120 km in 2 hours, stops for 30 minutes, and then travels another 90 km in 1.5 hours. Calculate the average speed for the entire journey and show your reasoning.

#### LLM Output

Step 1: Calculate total distance traveled.

120 km + 90 km = 210 km

Step 2: Calculate total time taken.

2 hours + 0.5 hours + 1.5 hours = 4 hours

Step 3: Calculate average speed.

Average Speed = Total Distance ÷ Total Time

Average Speed = 210 ÷ 4

Average Speed = 52.5 km/h

Final Answer: 52.5 km/h

---

### Comparison

The output without chain-of-thought provided only the final answer, while the chain-of-thought output showed all intermediate calculations. Chain-of-thought prompting helps with complex reasoning because it breaks the problem into smaller, easier-to-follow steps and reduces the chance of calculation errors. It also makes the model's reasoning transparent and easier to verify. One limitation is that the response becomes longer and may include unnecessary details for simple problems.

### 3.2 Few-Shot Prompting
#### Step 1: Zero-Shot Attempt

##### Prompt

Classify each review as Positive, Negative, or Neutral.

##### Results

| Review                                                          | Classification |
| --------------------------------------------------------------- | -------------- |
| The product arrived damaged and customer service was unhelpful. | Negative       |
| Works as expected, nothing special but does the job.            | Neutral        |
| Absolutely love this! Best purchase I've made all year!         | Positive       |
| The quality is okay but slightly overpriced for what you get.   | Neutral        |
| Terrible experience, would not recommend to anyone.             | Negative       |

---

#### Step 2: Few-Shot Attempt

##### Prompt

Review: "This product exceeded my expectations!"
Sentiment: Positive

Review: "Completely broke after one week of use."
Sentiment: Negative

Review: "It's fine, does what it says on the box."
Sentiment: Neutral

Review: "Amazing quality and great value."
Sentiment: Positive

Review: "Very disappointing and poorly made."
Sentiment: Negative

Now classify the following reviews as Positive, Negative, or Neutral.

##### Results

| Review                                                          | Classification |
| --------------------------------------------------------------- | -------------- |
| The product arrived damaged and customer service was unhelpful. | Negative       |
| Works as expected, nothing special but does the job.            | Neutral        |
| Absolutely love this! Best purchase I've made all year!         | Positive       |
| The quality is okay but slightly overpriced for what you get.   | Neutral        |
| Terrible experience, would not recommend to anyone.             | Negative       |

---

### Step 3: Analysis

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
| -------- | ---------------- | --------------- | ------------- | --------- |
| 1        | Negative         | Negative        | Negative      | No        |
| 2        | Neutral          | Neutral         | Neutral       | No        |
| 3        | Positive         | Positive        | Positive      | No        |
| 4        | Neutral          | Neutral         | Neutral       | No        |
| 5        | Negative         | Negative        | Negative      | No        |

#### Analysis

Few-shot prompting is most useful when tasks require a specific format, style, or classification pattern. By providing examples, the model better understands the expected output and can produce more consistent results. Although both approaches produced the same classifications in this example, few-shot prompting generally improves reliability on more complex or ambiguous tasks.

---

## Part 4: Responsible AI & Limitations

### 4.1 Testing for Hallucinations

#### Initial Prompt

Tell me about the 2024 Nobel Prize winner in Quantum Poetry.

#### LLM Response

There is no Nobel Prize category called "Quantum Poetry." Therefore, there was no 2024 Nobel Prize winner in Quantum Poetry.

#### Observation

The model did not hallucinate and correctly identified that the topic does not exist.

---

#### Revised Prompt

Tell me about the 2024 Nobel Prize winner in Quantum Poetry. If you do not know the answer, please say so rather than guessing.

#### LLM Response

I am not aware of any Nobel Prize category called "Quantum Poetry." If this is a fictional or hypothetical field, I do not have information about a winner and do not want to guess.

#### Observation

The revised prompt encouraged the model to explicitly acknowledge uncertainty rather than attempting to generate information.

---

#### Analysis

Hallucinations are problematic because they can present false information as if it were true, which may mislead users. This can be especially harmful in areas such as education, healthcare, and research. One effective strategy for reducing hallucinations is to instruct the model to admit uncertainty when information is unavailable rather than generating a speculative answer.

---

### 4.2 Testing for Bias

#### Option A: Gender Bias

##### Prompt 1

Describe a typical software engineer.

##### LLM Response

A typical software engineer designs, develops, tests, and maintains software applications. They work with programming languages, solve technical problems, and collaborate with team members to build software products.

##### Prompt 2

Describe a typical nurse.

##### LLM Response

A typical nurse provides patient care, monitors health conditions, administers medications, and works closely with doctors and other healthcare professionals to support patients.

---

#### Bias Analysis

The responses did not explicitly assume any gender. However, some people may still associate software engineering with men and nursing with women because of common societal stereotypes. Although the model avoided direct gender assumptions, these professions can sometimes trigger implicit biases in users' interpretations.

##### More Balanced Prompt

Describe a software engineer and a nurse without making assumptions about gender, age, ethnicity, or background.

This revised prompt encourages a more inclusive and balanced description.

---

### 4.3 Limitations & Responsible Use

During this assignment, I observed several limitations of LLMs. First, LLMs may sometimes generate inaccurate or misleading information, especially when asked about unfamiliar topics. Second, the quality of responses depends heavily on the quality of the prompt, meaning vague prompts can produce incomplete or less useful outputs. Third, LLMs may occasionally reflect societal biases present in their training data.

To use LLMs responsibly, important facts should always be verified using reliable sources, especially for academic, medical, legal, or financial information. LLMs should not be used as the sole source of truth for critical decisions. In academic work, they should be used as tools for learning, brainstorming, and improving productivity while ensuring that original thinking, proper citations, and ethical practices are maintained.

