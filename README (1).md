# Class-Result-Analysis
So, I wanted to work on something that I could personally connect with and at the same time apply my Python data analysis skills. That’s when I decided — why not analyze the academic performance of my own class? This way, the data would be real, and I could make meaningful interpretations.

The first step was collecting the data. I didn’t want to work with random, pre-existing datasets from the internet — I wanted this to be original. So, I went around collecting SPI, CPI, gender, accommodation type (whether they were hostelers or outsiders), and attendance percentage for each of my classmates across five semesters.
I put all this data neatly into an Excel sheet, with each row representing a student. I made sure to anonymize sensitive fields when presenting results and got permission to use the data for analysis.

Once I had my dataset ready, I moved into Jupyter Notebook — my favorite place for experimenting with data. Using Python’s Pandas library, I read the Excel file and started cleaning it:
-Made sure the SPIs and CPI values are numeric datatypes
-Made sure attendance percentages were numbers
-Checked for any missing values or irregular entries

Before jumping to visualizations, I took some time to understand the dataset:
-How many male vs. female students we had
-What the average SPI looked like across semesters
-The spread of CPI values
-How attendance varied across the class

Here’s where the project really came to life. I used Matplotlib and Seaborn to create visual stories:
-CPI Distribution by Gender — I created a box plot comparing male and female CPI distributions to see if there were any noticeable patterns.
-Attendance Analysis — A histogram revealed how attendance was distributed. Some people were extremely regular, and some… well, not so much.
-CPI vs Attendance — This scatter plot was interesting because it showed whether higher attendance actually correlated with better CPI.
-Statewise average CPI is sought w.r.t gender as well.
-Grade distribution plots of CPI and Semester wise SPI

**I grouped students into four CGPA bands (Excellent, Very Good, Good, Needs Improvement) and visualized the share of each group. That helped show where most students fall and how many might need intervention.**

From the visuals, I could tell a few stories:
-Some students showed clear upward SPI growth, proving they adapted well over time.
-One semester stood out as particularly challenging for the whole class.
-There was a noticeable difference in CPI distribution between genders.
-Attendance did have a mild positive correlation with CPI — the more regular students generally did better.
-Most students were in the ‘Good’ and ‘Very Good’ groups; only a small fraction fell into ‘Needs Improvement’, which helped prioritize targeted academic help

**There was a modest positive correlation between attendance and CPI: students with over ~85% attendance tended to cluster at higher CPI values. It wasn’t a perfect rule, but it was clear enough to warrant emphasizing attendance.**

I turned observations into recommendations:
-Academic mentoring for the students with declining SPIs (targeted tutoring).
-Attendance promotion programs — since attendance correlated with CPI, nudging students toward better attendance could improve outcomes.

What makes this project special to me is that the dataset is my own class — people I know, real academic journeys I’ve seen. This made the analysis not just technical, but personal. And I believe that’s what makes data science powerful — it turns numbers into stories

# Ultimately this project was a simple question turned into evidence: I turned classmates’ marks into a small dashboard and story that highlights who’s improving, what levers (like attendance) matter, and where we can intervene. It’s practical, respectful of privacy, and immediately useful for small-scale academic planning
