# CoderGirl_WebDev
### Lesson 2 — Git + GitHub Practice (README.md)



## Assignment

- [ ] **Fork** this repository. (https://github.com/kenmhaggerty/CoderGirl_WebDev)
- [ ] **Clone** your fork of this repository to your local machine (i.e., your computer).
- [ ] **Follow the instructions** below.
- [ ] **Push** all of your branches to your remote repository (i.e., GitHub).
- [ ] **Submit** your repository's **GitHub URL** on **Canvas**.



## Instructions

1. Switch to the `development` branch. You should have one file (`us_states.json`) inside of a folder named `Lesson 2`.
2. Open `us_states.json` in the code/text editor of your choice (e.g., Visual Studio Code; Sublime Text; Atom). It should be **empty** (i.e., have no contents).
3. Switch to the branch `ada_lovelace`. Verify that the file `us_states.json` now has the name and capital of every US state.
   - [ ] One US state is missing — can you figure out which one? **Add the missing information** for that state so that it follows the same format as the rest of the file.
   - [ ] **Commit your changes** with a good commit message. ("How to Write a Git Commit Message": https://chris.beams.io/posts/git-commit/)
4. Switch back to your `development` branch.
   - [ ] **Merge** your `ada_lovelace` branch into your `development` branch.
5. Switch to the branch `grace_hopper`.
   - [ ] **Merge** your `development` branch into your `grace_hopper` branch.
   - [ ] **Add missing information** for the state you added in *Step 3*.
   - [ ] **Commit** your changes with a good commit message.
6. Switch back to your `development` branch.
   - [ ] **Merge** your `grace_hopper` branch into your `development` branch.
   - [ ] **Merge** the branch `margaret_hamilton` into your `development` branch.
     - **Merge conflict!** 😫 Let's resolve this:
       - [ ] Make sure `us_states.json` **matches the formatting** of the branch `margaret_hamilton` by **deleting duplicate lines**.
       - [ ] **Don't lose your work!** Ensure none of the data you added are lost in resolving this merge conflict.
       - [ ] There's an error in the branch `margaret_hamilton` with one state capital — **find and correct the error** in `us_states.json`.
       - [ ] Finally, **commit your changes** to resolve the merge conflict.
       - [ ] *Food For Thought — what made resolving this merge conflict unnecessarily difficult?*
7. Merge branch `master` into `development` to see how close your final answer is to what you should have gotten!
   - **Don't worry** if your values for `lat` and `long` are slightly different. That's perfectly normal!
   - If you encountered any merge conflicts in this step, **resolve your conflicts + commit your fixes**.
8. Push **all of your branches** to **GitHub**.
9. On **Canvas**, submit the **URL** for your **GitHub repository** for this lesson.
10. You're done! Congratulations! 🎉🎉