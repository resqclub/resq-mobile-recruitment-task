# ResQ Mobile Development Recruitment Task

The aim of this task is to provide proof of your technical abilities and material for discussion in the technical interview. You have 2 choices,

1. Provide a sample of your work for us to review
2. Write and submit some new code matching specifications described below

In either case, you can submit your code by sharing access to a git repo. We will evaluate the code as if it is going to a production app, so bear that in mind with your submission.

# 1. Providing a sample

You can send us any mobile code you have available, written by yourself. This could be for an iOS or Android app, or cross-platform code. This should be a significant sample of code and e.g. not just the implementation for a tutorial. As a guideline, if it's less than 1000 lines of code then it's probably not suitable.

Along with your code, please provide some extra context for the sample. We'd like to know things like,

- What is the code for?
- Why did you write this code?
- How long ago did you write the code?

# 2. Submitting new code

If you don't have any recent code that you'd like to share with us, you may instead implement new code for the following assignment. You should not spend more than 2 - 3 hours on this assignment, it is okay not to complete everything and to leave some requirements unfulfilled. You may indicate in your submission if there are things you didn't have time for, or would change if you had more time.

## The assignment

ResQ Club employees love animals, and require easy access to cute cat pictures at all times. To fulfil this critical business need, please implement an MVP for the "ResQ Cat Club" app. The requirements for the app are as follows,

### Must have

- Can be used by iPhone and Android users
- Provides access to images from https://placekitten.com/ (API for [fetching particular images is described here](https://placekitten.com/attribution.html))
- Images can be viewed one at a time, with simple UI to get another image
- Users can mark particular cat images as "not cute enough", so they do not show up again

### Nice to have

- Users can easily undo marking cat images as "not cute enough" for up to 5 seconds after making the action
- Users can reset their preferences for cats - removing any "not cute enough" reviews they have previously made
- Users can submit their own cat images to their private gallery
