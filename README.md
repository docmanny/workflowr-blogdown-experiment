# Workflowr-Blogdown Experiment:

## Goal

Figure out most optimal method of incorporating `workflowr` functionality into `blogdown`  

## Results

By adding an option to provide a `pre_knit` function into `blogdown::html_page`, we can supply `workflowr`'s own `pre_knit` function and add in the reproducibility report and `session_info`.
