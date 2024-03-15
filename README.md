# [JSL02] Submission: Debug the DOM


# Debugging Duplicate Goals

**Debugging Brief:**
In the current code, users can add the same fitness goal multiple times, leading to duplicate entries in the goal list. To enhance the user experience and prevent duplicates, you need to implement a check to ensure that the same goal cannot be added more than once. If a duplicate goal is detected, it should NOT be added to the list.

![alt text](JSL02_Solution.png)

**Issue:** Users can add duplicate fitness goals.
**Debugging Task:** Prevent users from adding the same goal more than once.

- The goal is to prevent users from adding duplicate fitness goals to the list.
- You need to check if the goal being added already exists in the list before appending it.
- Display an alert to inform the user if they are trying to add a duplicate goal.
- Focus on the code structure within the function and how to handle duplicates.

**Explanation:**
1. We first retrieve all the existing goals in the `goalList` using `querySelectorAll`.
2. Then, we iterate through each existing goal and compare its text content with the new goal input.
3. If a duplicate is found, we display an alert message and exit the function using `return` to prevent the duplicate goal from being added.
4. If no duplicate is found, we proceed to create and add the new goal as before.

Check out the practice challenges on Scrimba here: https://scrimba.com/playlist/pwVxGLDUW


# Project Overview
- I was given a debugging task to prevent users from adding the same goal more than once. I had to enhance the user experience and prevent duplicates, so I implemented a check to ensure that the same goal cannot be added more than once. If a duplicate goal is detected, it should not be added to the list.

# Project Brief
- The goal was to prevent users from adding duplicate fitness goals to the list.
- I had to check if the goal being added already exists in the list before appending it.
- I had to  display an alert to inform the user if they try to add a duplicate goal.
- I focused on the code structure within the function and how to handle duplicates.

# Elements included 
- Code that includes modifications to prevent duplicate fitness goals from being added to the list.
- GitHub repository containing the updated code files.

# Reflections 

### Areas of mastery 
- There aren't any areas that I have mastered.

### Challenges faced 
gakitsi

### Areas of Improvement 
An area of improvement that I would like to focus on, especially on future projects (which will require more), is finding better ways to write more elegant lines of code that reduce clutter and unnecessary lines of code.

## Overall learning experience
My overall experience was quite overwhelming as I was only beginning to understand the little intricacies of writing JavaScript code and all the vast ways to do it. The experience was not on the posistive side, even though I was able to figure out how to complete the brief. 