# Auto Scaling Lab

An interactive, browser-only cloud-computing lab that demonstrates server capacity, load balancing, Auto Scaling rules, and predictive scaling.

## Run locally

Open [index.html](./index.html) in a modern browser. No build step, server, cloud account, or external service is required for the simulator.

The optional GSAP CDN script provides the page-transition animation. The lab remains functional if the CDN is unavailable.

## What learners can do

- Compare vertical and horizontal scaling.
- Test Round Robin and Least Connections load balancing.
- Configure and run Auto Scaling scenarios.
- Edit a simple JavaScript traffic-prediction function.
- Review local learning progress.
- Complete student-specific quizzes, then verify answers with simulator charts and explanations.
- Download verified quiz results as JSON.

## Student quizzes

Enter a student ID or name to begin. The ID deterministically selects each mission's questions, option order, and parameter values. Refreshing the page keeps the same quiz; retaking a mission advances its saved attempt and selects a different question set. Answers remain ungraded until the whole mission quiz is verified.

## Language

Use the button in the header to switch the interface between Traditional Chinese and English. The selected language is saved in browser local storage.

## Storage and privacy

The student ID, simulation settings, quiz selections, verification attempts, and progress are stored only in the browser under `cc10-autoscaling-lab-v2`; the language preference is stored under `cc10-language`. The page does not submit learner information or connect to a cloud account. Verified results can be downloaded by the learner as a JSON file.
