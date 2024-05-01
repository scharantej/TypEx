**Flask Application Design**

**HTML Files**

- `index.html`: The main page of the experiment, containing the necessary form for collecting participant information and initiating the experiment.
- `results.html`: The page displaying the experiment results, including typing speed and accuracy measurements before and after using the pretyping application.

**Routes**

- `home`: The route for the `index.html` page, serving as the starting point of the experiment.
- `start`: The route handling the initiation of the experiment. It records the participant's typing speed and accuracy before using the application.
- `submit`: The route handling the submission of the experiment results. It records the participant's typing speed and accuracy after using the application and performs statistical analysis to determine if there is a significant improvement.
- `results`: The route for the `results.html` page, displaying the experiment results to the participants.