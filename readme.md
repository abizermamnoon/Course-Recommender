# Overview
The Claremont Colleges has web apps such as hyperschedule and 5C scheduler to build their course schedules for each semester. I wanted to build a web app powered by generative AI that would reduce the effort that students need to put in to build these schedules. Students just have to provide the chatbot with the courses they have taken and the major they are interested in pursuing. The chatbot can provided the user with courses that they can take.

# Features
**Feature 1: Personalized Course Recommendations**

Students can input the courses they've taken, specify their major, and indicate the subjects they wish to study next semester. The chatbot suggests courses that satisfy their major requirements and explore additional interests.
Example 1: 

User Query: 
```
I am a government major. I have taken GOVT020, GOVT060 and GOVT070. Next semester, I want to take two government courses, 1 philosophy GE course and 1 psychology GE course. Can you recommend courses I can take given my pre-reqs?
```

Response: 

```
Based on your prerequisites and the courses you've already taken as a government major, here are some recommendations for the next semester:

Government Courses:

GOVT055 - Empirical Methods: Instructor: Shanna Rose. Scheduled for Tuesdays and Thursdays from 1:15 PM to 2:30 PM at CM Campus, The Kravis Center, 165. This course covers the philosophy and practice of political science research. Prerequisite: Introduction American Politics.
GOVT080 - Intro to Political Philosophy: Instructor: Mark Blitz or Ioannis Evrigenis. Available on Tuesdays and Thursdays from either 11:00 AM to 12:15 PM or 1:15 PM to 2:30 PM at CM Campus. This course introduces various philosophical understandings of political life.
Philosophy GE Course:

PHIL030 - Intro: Philosophical Questions: Instructors include Suzanne Obdrzalek, Alex Rajczi, or Briana Toole. Offered at various times, including Tuesdays and Thursdays from 11:00 AM to 12:15 PM, 1:15 PM to 2:30 PM, or 2:45 PM to 4:00 PM; and Monday and Wednesday from 3:00 PM to 5:00 PM at CM Campus. The course focuses on teaching philosophy through historical texts or contemporary readings, depending on the instructor.
Psychology GE Course:

PSYC030 - Introduction to Psychology: Instructors Alison M. Harris or Daniel A. Krauss. Scheduled on Tuesdays and Thursdays from 1:15 PM to 2:30 PM or 2:45 PM to 4:00 PM, and Monday and Wednesday from 8:10 AM to 9:25 AM or 9:35 AM to 10:50 AM at CM Campus. This course surveys major areas of scientific psychology.
These courses were selected based on their relevance to your major and the requirement to fulfill your GE needs. Generally, they are offered every semester or year, fitting well into your schedule at CMC.
```

**Feature 2: Career-Aligned Course Recommendations**

Student can input the raw job description they want to apply to and ask the chatbot courses they can take to situate themselves better among other candidates

User Query:
```
I am interested in this policy role. Here is the job description:

For five decades, the Environmental Law Institute (ELI) has played a pivotal role in shaping the fields of environmental law, policy, and management, both domestically and internationally.  ELI is hiring interns to support the research and publications departments of the Institute. Interns work directly with staff attorneys, editors, scientists, and policy analysts on a variety of projects. Substantive areas of focus in local, regional, federal, and international policy and law include: climate change, green technology, land use, biodiversity, air quality, public health, hazardous waste and brownfields, wetlands and watersheds, armed conflict and the environment, environmental management systems, public participation, environmental justice, Indigenous issues, and environmental enforcement. ABOUT THE INTERNSHIP Interns conduct in-depth secondary and primary research, attend and report on outside events, analyze, edit, and synthesize scholarly material, assist with preparation for environmental training courses, and provide limited administrative support. ELI integrates interns into the day-to-day operations of the Institute, and interns are encouraged to attend ELI-sponsored workshops, seminars, roundtable, and other events. In addition, interns will develop and complete an independent research project under the guidance of ELI staff. QUALIFICATIONS Eligibility is limited to students enrolled in an undergraduate program who have at least completed their first year of college. Applicants are ineligible if they graduate from college/university before or during this summer 2025 internship. Candidates should possess superior research, writing, and interpersonal communication skills, as well as a deep desire to gain knowledge of the environmental field. A strong academic background is required, but specific environmental experience is not. Candidates should demonstrate self-awareness, cultural competency and inclusivity, the ability to work with colleagues and stakeholders across diverse cultures and backgrounds, and the willingness to learn new digital tools. ABOUT ELI The Environmental Law Institute (ELI) is an environmental law, science, and policy center that makes law work for people, places, and the planet. We envision a healthy environment, prosperous economies, and vibrant communities founded on the rule of law. Our mission is to foster innovative, just, and practical law and policy solutions to enable leaders across borders and sectors to make environmental, economic, and social progress. ELI’s Research and Policy experts develop innovative legal and governance solutions to challenges in areas such as climate change; environmental justice; natural resource management; land conservation and smart growth; biodiversity loss and habitat destruction; and air, water, and soil pollution. Together, ELI’s staff aims to: Build the skills and capacity of tomorrow’s leaders and institutions Research and analyze complex and pressing environmental challenges Promote and disseminate the best thinking through print and electronic media Work with partners to develop and implement laws, policies, and other means to protect the environment and society Convene people with diverse perspectives to build understanding through robust dialogue For more information on ELI’s programs, visit https://www.eli.org/programs. COMPENSATION & PROGRAM REQUIREMENTS ELI will provide interns an hourly wage of $18.00. If an intern desires to receive course credit for the internship and the intern’s school prohibits earning income for the same work as the course credit is being received, accommodations can be made. Candidates for the summer internship must be available to work approximately 37.5 hours/week for at least 10 consecutive weeks from June to August 2025. This is a hybrid internship experience. Therefore, you must be physically present in the DC metro area (where ELI’s office is located).
What courses should I take to make myself a better candidate?
```

Response:

```
Based on the internship description from the Environmental Law Institute (ELI), here are some courses that could be beneficial to make you a stronger candidate for the role:

Policy Lab (ECON100 CM-01)

Instructor: Eric Helland
Schedule: Monday and Wednesday from 1:15 PM to 2:30 PM
Location: CM Campus, Center Court, TNT1Courser, Zachary C.
Description: This course focuses on the politics and process of domestic policymaking in the United States using an experiential approach to policy research and formation. Prerequisites include Introduction to American Politics and Principles of Economic Analysis.
Policy Lab (GOVT100 CM-01)

Instructor: Eric Helland
Schedule: Monday and Wednesday from 1:15 PM to 2:30 PM
Location: CM Campus, Center Court, TNT1Courser, Zachary C.
Description: Similar to ECON100, this course explores domestic policymaking with a focus on analytical tools and case studies. Prerequisites are Introduction to American Politics and Principles of Economic Analysis.
Intl Political Feature Writing (GOVT142 CM-01)

Instructor: William Ascher
Schedule: Monday and Wednesday from 2:45 PM to 4:00 PM
Location: CM Campus, The Kravis Center, LC63
Description: A course on journalistic writing about international politics, covering topics like migration and pollution. Prerequisite is Introduction to American Politics.
U.S. Politics and Social Policy (GOVT152C CM-01)

Instructor: Dionne Bensonsmith
Schedule: Tuesday and Thursday from 2:45 PM to 4:00 PM
Location: CM Campus, Bauer Center, 2
Description: Examines U.S. social policy with a focus on education, healthcare, and welfare policy.
Cold War America (HIST099 CM-01)

Instructor: Lily Geismer
Schedule: Tuesday and Thursday from 1:15 PM to 2:30 PM
Location: CM Campus, The Kravis Center, 103
Description: Provides an overview of U.S. history during the Cold War era, focusing on historical analysis, research, and writing.
Monetary and Fiscal Policy (ECON140 CM-01)

Instructor: Madison Florian Pascal
Schedule: Tuesday and Thursday from 9:35 AM to 10:50 AM
Location: CM Campus, Bauer Center, 25
Description: Investigates monetary and fiscal policy in market economies, understanding welfare effects of policy interventions. Prerequisite is Intermediate Macroeconomics.
Seminar in Research Methods (ECON180 CM-01)

Instructor: Richard Burdekin
Schedule: Tuesday from 11:00 AM to 12:15 PM
Location: CM Campus, Bauer Center, 36
Description: This seminar aids in the preparation of a senior thesis in economics and is recommended for all economics majors.
These courses focus on policy, research, and writing, aligning well with the core skills required for the internship. They also provide a comprehensive understanding of policy-making processes and research methods, which are crucial for a role at ELI.
```

# Project Setup

**STEP 1: Install Required Packages**

```
$ pip install -r requirements.txt
```

**STEP 2: Set Up API Key**

Create a .env file in src folder. Generate an API key and add the API key within the file
```
OPENAI_API_KEY=your_api_key_here
```

**STEP 3: Run the Application**

```
$ streamlit run src/app.py

```

# SQLite Database Schema

SQlite Database has the following variables:

```
'Course Code': 'The course code and section identifier.',
'Instructor_location': 'The professor, time, and location of the class.',
'Course Name': 'The name of the course.',
'course': 'The category the course falls into',
'instructor': 'The name of the professor teaching the course.',
'date_time': 'The days and times the course is offered.',
'location': 'The campus, building, and room where the course is taught.',
'campus': ('The campus or college where the course is taught.'),
'Course Code Short': 'The shortened course code. The first four letters represent the subject category, and the last three numbers are unique to each course.',
'Course Description': 'A description of the course.',
'prerequisites': 'Courses that must be completed before enrolling in this course.',
'Frequency': 'How often the course is generally offered.',
'day_code': 'The days the course is offered.',
'time': 'The time of day the course is taught.'
```

# Prompts

**Parameters provided:**

Schema describes the variables in the database and rules for the chatbot for recommending courses to the user

```
schema = {}
schema['get_table_info'] = db.get_table_info()

schema['labels_descriptions'] = {
'Course Code': 'The course code and section identifier.',
'Instructor_location': 'The professor, time, and location of the class.',
'Course Name': 'The name of the course.',
'course': 'The category the course falls into. Use `distinct_courses` to find available categories.',
'instructor': 'The name of the professor teaching the course.',
'date_time': 'The days and times the course is offered. Use `day_code` and `time` columns instead.',
'location': 'The campus, building, and room where the course is taught.',
'campus': (
    'The campus or college where the course is taught. '
    'Refer to `campuses` for campus names. Unless specified, assume the student is from CMC and '
    'rank courses based on `campus_ranking`.'
),
'Course Code Short': (
    'The shortened course code. The first four letters represent the subject category, '
    'and the last three numbers are unique to each course. Higher numbers indicate harder courses '
    'within the same subject category.'
),
'Course Description': 'A description of the course.',
'prerequisites': 'Courses that must be completed before enrolling in this course.',
'Frequency': 'How often the course is generally offered.',
'day_code': 'The days the course is offered. See `day_codes` for more information.',
'time': 'The time of day the course is taught. Refer to `distinct_times` for available times.'
}
# Add additional metadata to the schema
schema['distinct_courses'] = {
'economics', 'computer science', 'mathematics', 
'religious studies', 'government', 'history', 
'philosophy', 'psychology'
}
schema['campuses'] = {
'PZ Campus': 'Pitzer campus',
'CM Campus': 'CMC/Claremont McKenna College campus',
'SC Campus': 'Scripps campus',
'PO Campus': 'Pomona campus',
'HM Campus': 'Harvey Mudd campus'
}
schema['day_codes'] = {
'M': 'Monday',
'T': 'Tuesday',
'W': 'Wednesday',
'R': 'Thursday',
'F': 'Friday',
'TR': 'Tuesday and Thursday',
'MW': 'Monday and Wednesday',
'WF': 'Wednesday and Friday',
'MWF': 'Monday, Wednesday, and Friday',
'To Be Arranged': 'Schedule not determined yet'
}
schema['distinct_times'] = {
'01:15-02:30PM', '11:00AM-12:15PM', '09:35-10:50AM', 
'08:10-09:25AM', '02:45-04:00PM', '04:15-05:30PM', 
'02:45-05:30PM', '01:15-04:00PM', '07:00-09:50PM', 
'07:00-09:45PM', '09:00-09:50AM', '06:00-09:00PM', 
'00:00-00:00AM', '11:00AM-12:00PM', '11:00-11:50AM', 
'10:00-10:50AM', '08:00-08:50AM', '06:30-08:00PM', 
'03:00-05:00PM', '01:15-04:15PM', '03:00-04:00PM'
}
# Add ranking logic for campuses based on user preference
schema['campus_ranking'] = {'CM Campus', 'PZ Campus', 'SC Campus', 'PO Campus', 'HM Campus'}

schema['rules'] = {
'give higher preference to the courses from the school/campus that user says they stay at',
'easy/fun courses have fewer prerequisites compared to harder or more technical courses',
'make sure course names recommended are different. A course should not be recommended more than once in the same response. Always use distinct in final return statement for recommended courses',
'Math or CS GE can be satisified by any computer science or math course in any of the campuses',
'literature GE can be satified by any literature courses offered at CMC',
'philosophy GE can be satisifed by any philosophy course with course code less than 59',
'religious studies GE can be satisifed by any course with course code below 180',
'economics GE can be satisfied by Principles of Economic Analysis',
'government GE can be staisifed by Introduction American Politics',
'history GE can be satisfied by any CMC history course',
'psychology GE can be satisifed by pscychology course numbered under 100',
'in SQL query ensure "Course Name", "course", "instructor", "date_time", "location", "campus", "Course Code Short", "Course Description", "day_code", "time" "prerequisites" are returned',
'provde user with aternative timetables not just one strict response. For example if user asks for two econ courses and 2 psychology courses, provide 4 timetables each with 2 different economics and 2 different psychology courses',
'filter out course names that are seminar or research methods or special topics',
'always return 5 more results than user requested in SQL query',
'Economics major requirements: ECON050, ECON101, ECON102, ECON125, course codes in economics greater than 125. If student has taken ECON101, they cannot take ECON050. If student has taken ECON125, they cannot take ECON120.',
'Government major requirements: GOVT020, GOVT080, GOVT060 or GOVT070, 2 of (GOVT050 or GOVT055, GOVT112A or GOVT112B), course codes in government greater than 100',
'History major requirements: course name focus on United States, course name focus on Europe, course name focus on Asia, Latin America, Africa, Middle East',
'Psychology major requirements: PSYC030, PSYC037 or PSYC092, PSYC065 or PSYC070 or PSYC081, PSYC040 or PSYC096 or PSYC097, PSYC109, PSYC110 and PSYC111, course codes greater than 100 in psychology. If student has taken one of the courses in the or statement, they cannot take any other courses in the or statement',
'Philosophy major requirements: 1 course code less than 059, PHIL095, some history of philosophy course, some ethics course, PHIL198',
'Data Science major requirements: CSCI004 or CSCI005 or CSCI040, MATH031, CSCI055 or MATH055, CSCI046, MATH060, CSCI036 or ECON122 or ECON160 or PSYC166, MATH151, MATH152, CSCI145, CSCI143, some ethics course. If student has taken one of the courses in the or statement, they cannot take any other courses in the or statement',
'Data Science sequence requirements: CSCI004 or CSCI005 or CSCI040, CSCI036 or ECON122 or ECON160 or PSYC166, ECON120 or GOVT055 or MATH052 or MATH152 or PSYC109, CSCI046 or ECON125 or MATH151 or PSYC111, CSCI143 or CSCI145 or ECON126 or MATH152 or MATH156 or MATH160 or MATH166 or MATH186 or MATH187 or PSYC167, DS180. If student has taken one of the courses in the or statement, they cannot take any other courses in the or statement',
'Math major requirements: MATH030, MATH031, MATH032, MATH060, MATH131, MATH151. If user has taken MATH031, they cannot take MATH030 and if user has taken MATH032, user cannot take MATH031 and MATH030', 
'Computer Science major requirements: CSCI060, MATH055, CSCI070, CSCI081, CSCI105, CSCI123, CSCI140, CSCI183, CSCI184, CSCI195',
'if user mentions courses they have already taken, do not recommend those same courses in final result',
'if user includes their major and indicates that they want to take courses to satisy their major, provide course names that meet their major requirements first before suggesting additional courses',
}
```

**Prompt 1: Chain of Thought**

Generate a strategy to build a SQL Query

```
You are a thinker. You are responsible for coming up with a carefully thought out strategy to answer the user's query using the schema given below.
The label_descriptions in schema documents what the variables in the database consist of
Based on the user query, schema and chat history below, write a carefully thought out strategy on answering the user's question. Take the conversation 
history into account. For column names, strictly adhere to schema. Make sure that the response is a string with no formatting

<SCHEMA>{schema}</SCHEMA>
User query: {user_query}

write out the strategy and nothing else. 
For example: 
Question: I am a CMC student. I want to take two technical courses and two fun classes next semester

Response: Need to identify what courses can be categorized as technical courses and what courses can be categorized
as fun courses. Using the schema above, it is clear that 'computer science' and 'mathematics' are technical courses. 
Out of the courses in my database, I can say that 'religious studies' and 'history' are "fun" courses. "fun" courses 
should also not be hard so that student does not have to spend too much time on the course. Hence need to choose religious 
studies and history courses that have little prerequisities. Need to sort the religious studies and history courses based
on the number of prerequisites they have. Student is studying at CMC so it is easier for them to get into a class in CMC compared to
other campuses. Rank the computer science/math classes and give higher preferences to CMC courses. Also rank the religious studies/history courses and rank CMC courses higher. Student just wants two technical courses and two fun classes so select two
computer science/math classes and two history/religious studies courses. Also have a look at schema to make sure all bases are covered

Question: I am applying to the Lowe Institute. Here is the job description:
Data Journalists (DJs) will work in a team with Professor Cameron Shelton, Lowe Institute Director, and Dr. Minjae Yun, Lowe Assistant Director, to develop content for the Institute’s Lowe Down blog and social media accounts. 
Content will be defined based on the DJs research interests as well as the Lowe Institute’s focus on economics, politics, healthcare, education, transportation, and environmental studies pertinent to the Inland Empire and California.
DJs will need to be entrepreneurial in helping to generate ideas, pursue and analyze data, and write content. A weekly meeting with the entire group is required. Meeting deadlines is critical to success. DJs are expected to produce at least one publishable article a semester, and they are encouraged to work individually and in teams. This role is a good fit for those interested in public intellectualism, journalism, and the intersection of academia and the public. This is a young and expanding program and DJs will be expected to provide energy and ideas in helping expand the program. Successful participants will show initiative while taking editorial direction in pursuit of data analysis and writing.
Qualifications:
Basic data visualization and data analysis skills (e.g., graph creation and design, pivot tables, functions, basic transformations, regression)
Strong at reading, interpreting, and analyzing graphs/data tables; able to make economic inferences based on data
Completion of Econ 50 is required; completion of Econ 120 is extremely useful
Strong writing skills
Ability to adhere to established article posting deadlines
We expect to hire 8 to 12 Data Journalists, which may include returning "EJs" from the previous year.
Apply on Handshake, job posting job 9208561
What courses can I take to make me a good applicant for this job?

Response: This looks like a job that combines investigative journalism and data analysis. First step would looking for hints in the job description. The job description says that the user should take ECON050 and ECON120. These are course codes so these courses should be recommended. Second step would be collecting all the keywords that can be useful to filter within both course description and course name
This is a comprehensive list of keywords for this job description: "economics", "politics", "healthcare", "education", "transportation", "environment", "enterpreneurial", "data analysis", "writing", "journalism", "data visualization", "regression".  Then do a full text search within course descriptions to identify courses with all the keywords and sort the courses based on how many keywords they have from the list we created. Based on the rules in the schema, I assume student is from CMC so when recommending courses I would give first preference to CMC courses. To not overload students with too much info, recommend upto 10 courses maximum. Also have a look at schema to make sure all bases are covered

Question: I have taken the following courses: Principles of Economic Analysis, Intermediate Microeconomics, Economics Statistics, Computing for the Web, Literature GE, History GE and Psychology GE. I am an Economics major so I want to take two Economics courses next semester, one philosophy GE and one government GE. Can you recommend me a course scheule? I also prefer afternoon classes

Response: First identify that the courses are course names not course code. User wants to take two Economics courses next semester. 
Give first preference to courses that satisfy Economics major requirements from schema. Economics requirements are ECON050, ECON101, ECON102, ECON125, course codes in economics greater than 125.SQL query should give preference to these course codes. To identify courses that are taken, take keywords from courses that user has mentioned and make sure that final list of course names do not have these keywords. In this scenario keywords would be "Principles of Economic", "Microeconomics", "Statistics". Sort the courses in some random order not strictly increasing or decreasing. Make sure that courses suggested are not courses that user has already taken.
To make sure that recommended courses are not ones that user has already taken filter out course names that are similar to the ones that user has described. In this scenario identify keywords in the courses user has indicated i.e. "Principles of Economic", "Microeconomics", "Statistics". And filter course names from final results that have these keywords in them. The schema provides the criteria in order to qualify the philosophy course for philosophy GE or government course for government GE. According to schema, any philosophy course with course code below 59 satisifies philosophy GE. Also Introduction American Politics course satisfies government GE. User might want multiple timetables that they can choose from so provide at least 4 different sets of 2 economics courses, 1 philosophy GE and 1 government GE. Student also prefers afternoon classes so give higher preference to time in the afternoon. Also have a look at schema to make sure all bases are covered

Your turn: 
Question: {user_query}
Response:
```

**Prompt 2: Generate SQL Query based on Chain of Thought Reasoning**

```
You are a data analyst at a company. You are interacting with a user who is asking you questions about the company's database.
Based on the table schema, strategy below, write a SQL query that would answer the user's question. Take the conversation history into account.

<SCHEMA>{schema}</SCHEMA>
strategy: {strategy}

Write only the SQL query and nothing else. Do not wrap the SQL query in any other text, not even backticks. For column names, strictly adhere to schema.

For example:

Question: I am a CMC student. I want to take two technical courses and two fun classes next semester

Strategy: Need to identify what courses can be categorized as technical courses and what courses can be categorized
as fun courses. Using the schema above, it is clear that 'computer science' and 'mathematics' are technical courses. 
Out of the courses in my database, I can say that 'religious studies' and 'history' are "fun" courses. "fun" courses 
should also not be hard so that student does not have to spend too much time on the course. Hence need to choose religious 
studies and history courses that have little prerequisities. Need to sort the religious studies and history courses based
on the number of prerequisites they have. Student is studying at CMC so it is easier for them to get into a class in CMC compared to
other campuses. Rank the computer science/math classes and give higher preferences to CMC courses. Also rank the religious studies/history courses and rank CMC courses higher. Student just wants two technical courses and two fun classes so select two
computer science/math classes and two history/religious studies courses. Also have a look at schema to make sure all bases are covered

SQL Query: Write only the SQL query and nothing else. Do not wrap the SQL query in any other text, not even backticks.
SQL Query:
WITH RankedCourses AS (
SELECT 
    `Course Name`, 
    `Course Code Short`, 
    campus,
    course,
    prerequisites,
    ROW_NUMBER() OVER (
        PARTITION BY course 
        ORDER BY 
            CASE campus
                WHEN 'CM Campus' THEN 1  
                WHEN 'PZ Campus' THEN 2
                WHEN 'SC Campus' THEN 3
                WHEN 'PO Campus' THEN 4
                WHEN 'HM Campus' THEN 5
            END, 
            `Course Code Short`  
    ) AS rank_in_category
FROM merged_courses
WHERE course IN ('computer science', 'mathematics')
UNION ALL
SELECT 
    `Course Name`, 
    `Course Code Short`, 
    campus,
    course,
    prerequisites,
    ROW_NUMBER() OVER (
        PARTITION BY course 
        ORDER BY 
            CASE campus
                WHEN 'CM Campus' THEN 1  
                WHEN 'PZ Campus' THEN 2
                WHEN 'SC Campus' THEN 3
                WHEN 'PO Campus' THEN 4
                WHEN 'HM Campus' THEN 5
            END,
            LENGTH(prerequisites)  
    ) AS rank_in_category
FROM merged_courses
WHERE course IN ('religious studies', 'history')
AND prerequisites IS NULL  
)
SELECT 
DISTINCT `Course Name`,
`Course Code Short`,
campus,
course
FROM RankedCourses
WHERE (course IN ('computer science', 'mathematics') AND rank_in_category <= 2) 
OR (course IN ('religious studies', 'history') AND rank_in_category <= 2)  
ORDER BY 
course,  
CASE campus
    WHEN 'CM Campus' THEN 1  
    WHEN 'PZ Campus' THEN 2
    WHEN 'SC Campus' THEN 3
    WHEN 'PO Campus' THEN 4
    WHEN 'HM Campus' THEN 5
END
LIMIT 4;

Question: I have taken the following courses: Principles of Economic Analysis, Intermediate Microeconomics, Economics Statistics, Computing for the Web, Literature GE, History GE and Psychology GE. I am an Economics major so I want to take two Economics courses next semester, one philosophy GE and one government GE. Can you recommend me a course scheule? I also prefer afternoon classes

Strategy: First identify that the courses are course names not course code. User wants to take two Economics courses next semester. 
Give first preference to courses that satisfy Economics major requirements from schema. Economics requirements in schema are ECON050, ECON101, ECON102, ECON125, course codes in economics greater than 125. SQL query should give preference to these course codes.
To identify courses that are taken, take keywords from courses that user has mentioned and make sure that final list of course names do not have these keywords. In this scenario keywords would be "Principles of Economic", "Microeconomics", "Statistics". Sort the courses in some random order not strictly increasing or decreasing. Make sure that courses suggested are not courses that user has already taken.
To make sure that recommended courses are not ones that user has already taken filter out course names that are similar to the ones that user has described. In this scenario identify keywords in the courses user has indicated i.e. "Principles of Economic", "Microeconomics", "Statistics". And filter course names from final results that have these keywords in them. The schema provides the criteria in order to qualify the philosophy course for philosophy GE or government course for government GE. According to schema, any philosophy course with course code below 59 satisifies philosophy GE. Also Introduction American Politics course satisfies government GE. User might want multiple timetables that they can choose from so provide at least 4 different sets of 2 economics courses, 1 philosophy GE and 1 government GE. Student also prefers afternoon classes so give higher preference to time in the afternoon. Also have a look at schema to make sure all bases are covered

SQL Query:
WITH taken_courses AS (
SELECT DISTINCT "Course Name"
FROM merged_courses
WHERE "Course Name" LIKE '%Principles of Economic%'
    OR "Course Name" LIKE '%Microeconomics%'
    OR "Course Name" LIKE '%Statistics%'
    OR "Course Name" LIKE '%Computing for the Web%'
    OR "Course Name" LIKE '%seminar%'
    OR "Course Name" LIKE '%research%'
    OR "Course Name" LIKE '%Special Topics%'
),
economics_major_courses AS (
SELECT *
FROM merged_courses
WHERE course = 'economics'
    AND (
        "Course Code Short" IN ('ECON050', 'ECON101', 'ECON102', 'ECON125')
        OR CAST(SUBSTR("Course Code Short", 5, 3) AS INTEGER) > 125
    )
    AND "Course Name" NOT IN (SELECT "Course Name" FROM taken_courses) -- Exclude taken courses
    AND time LIKE '%PM%' -- Afternoon preference
ORDER BY
    
    CASE campus
        WHEN 'CM Campus' THEN 1
        WHEN 'PZ Campus' THEN 2
        WHEN 'SC Campus' THEN 3
        WHEN 'PO Campus' THEN 4
        WHEN 'HM Campus' THEN 5
        ELSE 6
    END,
    "Course Code Short"
LIMIT 8 -- Get a maximum of 8 economics courses
),
philosophy_ge AS (
SELECT *
FROM merged_courses
WHERE course = 'philosophy'
    AND CAST(SUBSTR("Course Code Short", 5, 3) AS INTEGER) < 59 -- Philosophy GE requirement
    AND time LIKE '%PM%' -- Afternoon preference
LIMIT 4
),
government_ge AS (
SELECT *
FROM merged_courses
WHERE "Course Name" = 'Introduction American Politics' -- Government GE requirement
    AND time LIKE '%PM%' -- Afternoon preference
LIMIT 4
)
SELECT *
FROM economics_major_courses -- Selected economics courses
UNION ALL
SELECT *
FROM philosophy_ge -- Selected philosophy GE course
UNION ALL
SELECT *
FROM government_ge;

Question: I am applying to the Lowe Institute. Here is the job description:
Data Journalists (DJs) will work in a team with Professor Cameron Shelton, Lowe Institute Director, and Dr. Minjae Yun, Lowe Assistant Director, to develop content for the Institute’s Lowe Down blog and social media accounts. 
Content will be defined based on the DJs research interests as well as the Lowe Institute’s focus on economics, politics, healthcare, education, transportation, and environmental studies pertinent to the Inland Empire and California.
DJs will need to be entrepreneurial in helping to generate ideas, pursue and analyze data, and write content. A weekly meeting with the entire group is required. Meeting deadlines is critical to success. DJs are expected to produce at least one publishable article a semester, 
and they are encouraged to work individually and in teams.
This role is a good fit for those interested in public intellectualism, journalism, and the intersection of academia and the public. This is a young and expanding program and DJs will be expected to provide energy and ideas in helping expand the program. Successful participants will show 
initiative while taking editorial direction in pursuit of data analysis and writing.
Qualifications:
Basic data visualization and data analysis skills (e.g., graph creation and design, pivot tables, functions, basic transformations, regression)
Strong at reading, interpreting, and analyzing graphs/data tables; able to make economic inferences based on data
Completion of Econ 50 is required; completion of Econ 120 is extremely useful
Strong writing skills
Ability to adhere to established article posting deadlines
We expect to hire 8 to 12 Data Journalists, which may include returning "EJs" from the previous year.
Apply on Handshake, job posting job 9208561
What courses can I take to make me a good applicant for this job?

Strategy: This looks like a job that combines investigative journalism and data analysis. First step would looking for hints in the job description. The job description says that the user should take ECON050 and ECON120. These are course codes so these courses should be recommended. Second step would be collecting all the keywords that can be useful to filter within both course description and course name. This is a comprehensive list of keywords for this job description: "economics", "politics", "healthcare", "education", "transportation", "environment", "enterpreneurial", "data analysis", "writing", "journalism", "data visualization", "regression".  Then do a full text search within course descriptions to identify courses with all the keywords and sort the courses based on how many keywords they have from the list we created. Based on the rules in the schema, I assume student is from CMC so when recommending courses I would give first preference to CMC courses. To not overload students with too much info, recommend upto 10 courses maximum. Also have a look at schema to make sure all bases are covered

SQL Query:
    WITH keyword_matches AS (
SELECT 
    *,
    -- Count how many keywords are present in the course description or name
    ( 
        (LOWER("Course Description") LIKE '%economics%') + 
        (LOWER("Course Description") LIKE '%politics%') +
        (LOWER("Course Description") LIKE '%healthcare%') +
        (LOWER("Course Description") LIKE '%education%') +
        (LOWER("Course Description") LIKE '%transportation%') +
        (LOWER("Course Description") LIKE '%environment%') +
        (LOWER("Course Description") LIKE '%entrepreneurial%') +
        (LOWER("Course Description") LIKE '%data analysis%') +
        (LOWER("Course Description") LIKE '%writing%') +
        (LOWER("Course Description") LIKE '%journalism%') +
        (LOWER("Course Description") LIKE '%data visualization%') +
        (LOWER("Course Description") LIKE '%regression%') +
        (LOWER("Course Name") LIKE '%economics%') +
        (LOWER("Course Name") LIKE '%politics%') +
        (LOWER("Course Name") LIKE '%healthcare%') +
        (LOWER("Course Name") LIKE '%education%') +
        (LOWER("Course Name") LIKE '%transportation%') +
        (LOWER("Course Name") LIKE '%environment%') +
        (LOWER("Course Name") LIKE '%entrepreneurial%') +
        (LOWER("Course Name") LIKE '%data analysis%') +
        (LOWER("Course Name") LIKE '%writing%') +
        (LOWER("Course Name") LIKE '%journalism%') +
        (LOWER("Course Name") LIKE '%data visualization%') +
        (LOWER("Course Name") LIKE '%regression%')
    ) AS keyword_score
FROM 
    merged_courses
WHERE 
    "Course Code Short" IN ('ECON050', 'ECON120') -- Include these as high-priority courses
    OR (
        LOWER("Course Description") LIKE '%economics%'
        OR LOWER("Course Description") LIKE '%politics%'
        OR LOWER("Course Description") LIKE '%healthcare%'
        OR LOWER("Course Description") LIKE '%education%'
        OR LOWER("Course Description") LIKE '%transportation%'
        OR LOWER("Course Description") LIKE '%environment%'
        OR LOWER("Course Description") LIKE '%entrepreneurial%'
        OR LOWER("Course Description") LIKE '%data analysis%'
        OR LOWER("Course Description") LIKE '%writing%'
        OR LOWER("Course Description") LIKE '%journalism%'
        OR LOWER("Course Description") LIKE '%data visualization%'
        OR LOWER("Course Description") LIKE '%regression%'
        OR LOWER("Course Name") LIKE '%economics%'
        OR LOWER("Course Name") LIKE '%politics%'
        OR LOWER("Course Name") LIKE '%healthcare%'
        OR LOWER("Course Name") LIKE '%education%'
        OR LOWER("Course Name") LIKE '%transportation%'
        OR LOWER("Course Name") LIKE '%environment%'
        OR LOWER("Course Name") LIKE '%entrepreneurial%'
        OR LOWER("Course Name") LIKE '%data analysis%'
        OR LOWER("Course Name") LIKE '%writing%'
        OR LOWER("Course Name") LIKE '%journalism%'
        OR LOWER("Course Name") LIKE '%data visualization%'
        OR LOWER("Course Name") LIKE '%regression%'
    )
),
ranked_courses AS (
SELECT 
    *,
    -- Give priority to CMC courses and sort by keyword_score
    CASE
        WHEN LOWER(campus) = 'cm campus' THEN 1
        ELSE 2
    END AS campus_rank
FROM 
    keyword_matches
)
SELECT 
"Course Code", 
"Course Name", 
"instructor", 
"date_time", 
"location", 
"campus", 
"Course Code Short", 
"Course Description", 
"prerequisites"
FROM 
ranked_courses
ORDER BY 
campus_rank, 
keyword_score DESC
LIMIT 10;

Your turn:

Question: {user_query}
Strategy: {strategy}
```

**Prompt 3: Generate Response to user query based on results from SQL Query**

```
You are a data analyst at a company. You are interacting with a user who is asking you questions about the company's database.
Based on the table schema below, question, sql query, and sql response, write a natural language response. Make sure that response 
follows the schema
<SCHEMA>{schema}</SCHEMA>

Conversation History: {chat_history}
SQL Query: <SQL>{query}</SQL>
User question: {question}
SQL Response: {response}
```