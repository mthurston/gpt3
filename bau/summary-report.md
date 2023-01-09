1. Summary Format: 
* The first row should contain a single cell that spans 4 columns, with the text "Weekly Activity Summary" 
* The second row should contain 4 cells, with the following column headings: "Day", "Date", "Hours", "Activity" 
* The next 6 rows should contain 4 cells each, with the following content: 
  * Day: The day of the week, abbreviated (e.g. "Mon.", "Tue.", "Wed.", "Thur", "Fri.", "Sat.", "Sun.") 
  * Date: The date of the corresponding day, in the format MM/DD 
  * Hours: The number of hours worked on the corresponding day. If no hours are specified, the default is 0. If hours are specified, the default is 8 unless otherwise specified. 
  * Activity: Any activity that was performed on the corresponding day. If no activity is specified, the cell should be left blank. 
 * The final row should contain 3 cells, with the following content: 
  * The first cell should be blank 
  * The second cell should contain the word "Total" in bold 
  * The third cell should contain the total number of hours worked for the week 
 * The table should be generated using the provided input, which consists of tasks and hours for each day of the week. 
2. Task List Format: 
* The tasks should be grouped by day of the week 
* Each day of the week should have a heading with the day of the week in bold (e.g. "Monday") 
* Under each day of the week heading, the tasks should be listed as bullet points in the following order: 
 * Any meetings that took place on that day 
 * Tasks, listed in numerical order based on the task number 
 * Non-task items (e.g. notes, observations) 
* Each task should be formatted as follows: 
 * The task number should be enclosed in square brackets (e.g. [T123]) 
 * The task description should be a brief paraphrase of the task 
3. Accomplishments Format 
* The accomplishments should be listed as bullet points 
* Each bullet point should describe a completed task 
* The task number should be included in square brackets at the beginning of the bullet point (e.g. [T123]) 
* The task description should be a brief paraphrase of the task 
* The bullet points should be organized by task number, in numerical order 
* Any bullet points without a task number should be removed from the list 
* Any references to other people or teams should be removed from the descriptions 
* If multiple tasks have the same description, they should be combined into a single bullet point with multiple task numbers listed in square brackets (e.g. [T123, T456, T789]) 