# Module Inquiry 1

## Questions
Abbreviations:
- NLP == Natural Language Processing
- ML == Machine Learning
- API == Application Programming Interface

1. What questions did you ask your stakeholder that helped in breaking down your tasks?
- Who would be able to sign up to the website and what are the best security measures? (e.g. some unwanted person signing up and posting inappropriate content)
- What if the user (child) has unreadable handwriting? Should we manually transcribe it if the ML outputs gibberish?
- Would there be human moderators?

2. What user stories did you draw from to create your product roadmap? List them below.
Note: This would be more DS related so it applies to the functionality of automated moderation (using ML) and the complexity score (using NLP).
- The user (child) and customer (parent) need safety from unwanted, inappropriate posts.
- The user needs a complexity score for further rankings.
- The user should not write stories with foul language on them.

- STRETCH: The user should not draw anything inappropriate in their submitted stories (I found a way to build a ML model that can identify the doodles/drawings, then train the model to flag what it finds inappropriate and send it to the human moderator for review).

3. Select your favorite user story. What are the tasks that need to be accomplished in order to ship that particular user story?
    - What did you do well in this task breakdown process? What were some challenges?
    
     - > My favorite one is the complexity score user story. I would love to dive in and see how it works under the hood. One part that I love about DS is researching
    how these models work and how they came about these predictions.
    - > First, build an API where we can add these functions and also send the endpoints to backend. Then, load the data and analyze it for further implementations
    to create the ML and NLP model. As stated above, the NLP model will take care of the complexity score; and the ML model will take care of transcribing the
    user's stories into text, and also it would be used for the automated moderation.
    - > The biggest challenge was finding an approach for the moderation of unwanted drawings/doodles since there were limited ways to implement it.
    
4. After what you've learned in this process, given a new product roadmap, how would you approach it differently? What would you change about the way you go about breaking down individual tasks?
- I would take less time focusing on some "minor" details and focus instead on the more crucial aspects that need to be handled. It's great to think ahead and
think of ways to improve the app/website, but right after the crucial points are out of the way.
