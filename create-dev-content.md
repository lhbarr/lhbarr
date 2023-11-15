# How to start writing developer docs 

As technical writers, we write documentation for all kinds of users -- installers, end-users, administrators, and maybe even developers.  For some of us, writing for developers is a challenge. How can we know what a developer needs if we don't know how to code ourselves? I grappled with how to give developers what they need in this last year, while creating developer documentation for Via. This guide shares my process. I hope it helps you start this journey. 

## 1. Investigate why your organization needs developer docs

Ask your product team and your dev team what they want to gain by adding developer content. What problems are they trying to solve? Here are some questions you can ask:

- How are external developers using the product today?
- Is there a need to reduce work for the implementation teams that are installing the product? What are the main problems?
- Are there existings docs, but there are still a lot of support calls? If yes, what are the issues?
- What is the purpose of the developer product, and what kinds of documentation do you need to do this? Let's say that the purpose is to let developers add your product to their app. You'll probably need to deliver: API reference docs, tutorials to use the endpoints together, SDK docs, and testing guidelines. 

Find out the issues your docs need to solve and what you need to write.

## 2. Prioritize the doc issues with the product and dev teams

Now that you have a good understanding of what problems your docs need to help solve, map out your documentation tasks. [This article by Pronovix on the minimum you need is helpful.](https://pronovix.com/blog/what-mvp-developer-portal)

- Are there internal drafts of developer documentation? Can you use the internal docs as your base?
- What areas are not ready for documentation? Sometimes, you see a need for documentation, but it's not in the dev plan. 
- Can a developer complete main flows end-to-end? 

Figure out what you need and the order you need to write the docs. After you understand what needs to be done, ask your dev and product teams for feedback. Make sure you are aligned, and ask them to prioritize what must come first.

## 3. Identify your own knowledge gaps

Writing for developers can be challenging for those of us that aren't engineers. What do you need to learn? You don't need to be able to code. But you do need to be familiar with the developer's environment. Your dev team will help you. To learn enough to have good questions for them, I recommend:

- [Tom Johnson's excellent API documentation course](https://idratherbewriting.com/learnapidoc/)
- [An interactive way to learn about Git branching](https://learngitbranching.js.org/)
- [Learning some code](https://www.freecodecamp.org/learn/)
- [Finding beautiful docs you love](https://pronovix.com/blog/best-developer-portals-2022)

## 4. Choose a style guide 

If you have a corporate style guide, use it for basic style issues like case and voice. Then, choose a developer style guide to use for all other questions. At Via, I used the [Google developer documentation style guide](https://developers.google.com/style). 

## 5. Set up a process for documentation development and release

Be proactive and suggest a process that embeds documentation into the definition of done (DoD) for the release. 
- Make sure documentation tasks are linked to the feature epic.
- Set up guidelines to make sure endpoints conform to the industry standard. For example, if you're documenting a REST API, review the endpoint names and parameters, and make sure they are RESTful. Make this review part of the DoD.
- If you have a release gate, make sure to include documentation review. If there isn't a formal gate, have your own internal meeting with the dev and product teams to review what will be released for a feature.

## Would love to hear from you

What helped you in your journey to write dev docs? Let's hear from you. 

