# 📘 Data Dictionary – schedule_survey_cleaned.xlsx

This file describes the meaning and format of each column in the dataset used for the "Schedule Impact Statistical Analysis" project.

| Column Name               | Description                                                                                  | Example Values                                      |
|---------------------------|----------------------------------------------------------------------------------------------|-----------------------------------------------------|
| `index`                  | Row index or ID of the respondent                                                            | 84, 112, 160                                        |
| `age`                    | Age group of the respondent                                                                  | "18-23"                                             |
| `gender`                 | Gender of the respondent                                                                     | "Male", "Female"                                    |
| `occupation`             | Primary role of the respondent                                                               | "Student"                                           |
| `schedule_type`          | How the respondent describes their current scheduling style                                  | "I schedule both goal-oriented tasks and routine daily activities", "I don’t schedule my tasks" |
| `scheduling_satisfaction`| Satisfaction level with current schedule (1 = Very Unsatisfied, 5 = Very Satisfied)          | 1, 2, 4, 5                                          |
| `schedule_control`       | Level of flexibility or control respondent has over their schedule                           | "Always (I can adjust my schedule anytime)", "Rarely" |
| `preferred_schedule`     | Respondent's preferred type of schedule                                                      | "Flexible", "Fixed", "Hybrid (Combination of Fixed and Flexible)" |
| `planning_method`        | How the respondent plans their schedule                                                      | "No formal planning", "Using a digital calendar"    |
| `schedule_effectiveness` | Respondent's perceived effectiveness of their current schedule (scale 1–5)                   | 1 to 5                                              |
| `productivity`           | Self-rated productivity (scale 1–5)                                                          | 1 to 5                                              |
| `overwhelmed`            | Frequency of feeling overwhelmed by schedule                                                 | "Rarely", "Always", "Sometimes"                     |
| `performance_satisfaction`| Satisfaction with academic or personal performance                                          | "Satisfied", "Very Satisfied", "Unsatisfied"        |
| `work_life_balance`      | Satisfaction with work-life balance                                                          | "Satisfied", "Unsatisfied", "Very Satisfied"        |
| `diet_healthy`           | Frequency of maintaining a healthy diet                                                      | "Always", "Often", "Sometimes", "Rarely", "Never"   |
| `exercise_regular`       | Frequency of regular exercise                                                                | "Always", "Often", "Sometimes", "Rarely", "Never"   |
| `suitable_schedule_type` | Schedule type the respondent believes is most suitable for them                             | "Flexible Schedule", "Fixed Schedule", "Hybrid"     |
| `ai_tool_use`            | Whether the respondent uses AI tools to assist in scheduling                                | "Yes", "No", "Haven't tried yet", "Somewhat, but I still prefer manual scheduling methods." |
| `flexibility_importance` | How important schedule flexibility is to the respondent                                      | "Extremely important", "Somewhat important", "Not important at all" |
| `satisfied`              | 1 = Generally satisfied with schedule; 0 = Not satisfied                                     | 0, 1                                                |
| `healthy`                | 1 = Maintains healthy routines (diet + exercise); 0 = Does not                              | 0, 1                                                |
