# Workshop: Mock Interview

## What?
- Learn how to conduct a mock interview with a fellow learner.

## Why?
- Interviewing skills are adjacent to technical skills.
- It is really important to have practiced giving interviews in a SAFE space.
- Stepping into the shoes of the interviewer can give you real insights into the process, and what the interviewers are looking for.
- Opportunity to ignore Imposter Syndrome and Dunning Kruger Effect
- To have the tools to self organize and participate in a mock interview with another learner.

## How?
- Create groups of 2 learners each. One learner is an interviewer, the other is an interviewee.
- The interviewer is given a problem definition and the solution.
- The interviewee is then expected to whiteboard the solution in 45 mins.
- The interviewer makes notes of things that went well, and things that did not.

## Interviewee tips
- Ensure you UNDERSTAND the problem by explaining it to the interviewer. Writing the problem down(without the help of the interviewer) on the board helps.
- Rely on a process, to free up your mind.
- Break a complex problem down into smaller parts.
- Start with the smallest and simplest input(base case), and then grow the input.
- Be communicative about your thought process. THINK OUT LOUD.
- Manage the whiteboard space well
- Write pseudocode first, and test your assumptions.
- Good variable names
- Know the time and space complexity of your code
- Ask how much time you have remaining

## Interviewer tips
- Answer all clarifying questions.
- Ask them about space and time complexity.
- IF you're feeling generous, you can validate their pseudocode (if it is correct)
- Keep track of time.
- Write down the things that the you think the interviewee did well, and things that they did not do so well.

## Examples: 

### Design a schema for an online flowershop.
- As a user, I can see a list of flowers on sale
- As a user, I can buy a flower
- As a user, I should be able to leave a message on the flower when I purchase

#### Step 1: identify all NOUNS in the specs
Solution: flowers, users, orders

#### Step 2: think of all ADJECTIVES(properties) of the nouns
Solution:
 a. Flower
 - color
 - name
 - regular_cost
 - sales_cost
 - id
 - is_on_sale


 b. User
 - id
 - first name
 - last name
 - email

 c. Order
 - id
 - flower_id
 - user_id
 - quantity
 - total_cost
 - message
 - created_at

#### Step 3: Think of the VERBS (actions)
- `findAllFlowersOnSale` function which returns all the flowers
- `purchase` function which creates an entry into the orders table, and takes a message as a parameter for the order


