---
title: Week 10 Reflection
author:
  name: Taylor Pike
  url: "https://taylor-pike.github.io/2020-10-22-week10-reflection.html"
categories:
- reflections
---

This week, we learned about “aleatory poetry” which is basically writing that is created at random. This can look very different depending on how you choose to write it. On one hand, you can choose to make random words and phrases to make sentences that are diverse if not completely unrelated. You can also create diverse storylines or endings of the same story.

For my hands-on activity this week, I chose to do the latter. After coming up with an opening for a story, I made two possible middle sections of the story. Then, for each of those middle sections, I came up with two endings. Therefore, my writing had four possible storylines.

Then, I used the Tracery library to code my story to show up as a blog post on my website with randomly generated content. I included a new “tracery” layout then made a new page for the post. My “origin” was the beginning of my story that would always be the same no matter what middle and ending was randomly chosen. Then, I included a grammar (in this case #middle#) once the beginning of the story was over.

Within this #middle# grammar, there were two options: middle1 and middle2. In the code for middle1, after this section of the story, was another grammar (#endingA#), and the code for middle2 ended with a grammar for #endingB#.

Finally, I specified the #endingA# grammar with two possible endings: ending1 and ending2. I did the same for #endingB#, containing ending3 and ending4. By writing out my code this way, I ensured that ending1 and ending2 were only possible if middle1 was chosen, and ending3 and ending4 could only be generated if middle2 was randomly selected.

I chose to write it this way because my first two endings to my story are based on the events that occur in middle1 and my second two endings to my story are based on the events that occur in middle2.

I like knowing how to create stories that are randomized by the computer, but I hope to soon get more experience with providing those same differing plot lines but at the choice of the reader. Maybe instead of simply calling them “middle1” and “middle2” or “ending1” through “ending4,” I can give some information about what those parts of the story will lead to.

With the example of my own story, I could prompt the user to choose what the father should do: agree to meet with the stranger in the park or tell the police. In this way, the story will become more of an interactive experience, with the reader and user feeling like they are the ones in the story since they are the ones making the decisions.

Now that I think about it, it could be interesting to combine both randomization and user choices. Since my endings aren’t really specific choices from my characters, the user can choose a middle (whether or not the main character meets with the stranger) and the ending can be randomized to show different possibilities that could occur with the same decision.
