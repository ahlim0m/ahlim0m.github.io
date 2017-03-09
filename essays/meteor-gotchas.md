---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---

## Problem Solved!

In prior practice WODs, we were told many times the importance of import statement. However, I tend to forget writing import statement every once in a while and get confused. The problem was as same as the walkthrough video posted on the course website. The function or layout did not show up at all, although my application itself was up and running. There were a few times where I could get away with it by going back to index.js and adding import statements for right files, but there was one time when my application crashed because of this problem. I could not figure it out myself and ended up asking for help. Turns out, I used the template inside a file that was not imported, thus the application crashed. A great lesson to get into a habit of checking import files!

## Wait, What?

For the digits practice WOD part 1, I encountered a serious problem which worried me, because it was related to time. When setting up our application for the first time using a meteor application template, there were several different steps to follow through. Downloading and installing npm went smoothly, but the problem was the next step. Invoking meteor --settings ../config/settings.development.json took more than 40 minutes! I had about 8,000 changes to commit, while the walkthrough video only had about 300 files, and I have tried one of the possible solution to help solving the problem which was running: meteor npm install —save bcrypt , but it did not solve the problem. It still remains as a mystery.
