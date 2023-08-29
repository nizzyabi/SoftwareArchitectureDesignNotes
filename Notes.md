# Notes #

Break down of course application.

Writing out what you must track provides you with a clear and good outline of what is needed, saving you time and unnecessary time spend thinking of things needed.


# For an online school areas we will likely need track:

- Students
- Professors 
- Courses   
- Enrol 

- Person
- Address

# Then,for each item you need to track (Students, Profs, Courses, and Enrollment of Students and Professors, break each down into subsections of things that we will need to write in code and track):

1. Students
- international(): boolean (is the student international or not?)
- isPartTime(): boolean (is the student part time or full time?)
- isOnProbation():boolean (is the student on probation or not?)

2. Professors
- salary: float (how much profs are being paid)

3. Courses

- name: string (name of the course)
- code: string (name of course code)
- minStudent: int (what is the min amount of students needed for this class to be allowed to start?)
- maxStudent: int (what is the max amount of students allowed to enroll in this class?)
- start: date (when is the start date of the course?)
- end: date (when is the end date of the course?)
- isCancelled(): boolean (checks if the class cancelled based off min amount of student threshold?)

4. Enrol
- date: date (when did they enrol?)
- grade: float (tracks student grades)

5. Person (shared classes and attributes between the listed items to track)
- firstName: string
- lastName: string
- dateOfBirth: date
- phoneNumber: string

6. Address
- country: string
- state: string
- city: string
- streetAddress: string
- postalCode: string