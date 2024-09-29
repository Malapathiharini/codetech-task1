# codetech-task1

**Name** Malapathi Harini

**Company** codtech it solution

**Id** CT08DS7291

**Domain** CYBER ECURITY AND ETHICAL HACKING

**Duration**  AUGUST 30th, 2024 to SEPTEMBER  30th, 2024. 

**Mentor** Neela Santhosh Kumar  

#Objective
The objective of this password strength checker script is to evaluate the quality of a user's password based on several criteria to determine if it's weak, moderate, or strong. 


#About the program


**Password Strength Criteria:**

1. Length: At least 12 characters
2. Lowercase letters: Contains at least one lowercase letter (a-z)
3. Uppercase letters: Contains at least one uppercase letter (A-Z)
4. Digits: Contains at least one digit (0-9)
5. Special characters: Contains at least one special character (!@#$%^&*(),.?":{}|<>)
6. Not common: Password is not in the list of common passwords


**Program Flow:**

1. Import the re module for regular expression matching.
2. Define a list of common passwords (common_passwords).
3. Define the password_strength function, which takes a password as input.
4. Evaluate the password against the strength criteria using regular expressions.
5. Calculate a score based on the number of criteria met (max score: 7).
6. Provide feedback based on the score:
    - Weak (score ≤ 2): Password is too short or lacks complexity.
    - Moderate (score ≤ 4): Password could be stronger.
    - Strong (score > 4): Password is secure.
7. Get user input for a password.
8. Call the password_strength function with the user's password.
9. Print the password score and feedback.


**Regular Expressions Used:**

- r'[a-z]': Matches any lowercase letter.
- r'[A-Z]': Matches any uppercase letter.
- r'[0-9]': Matches any digit.
- r'[!@#$%^&*(),.?":{}|<>]': Matches any special character.


**Scoring System:**

- Length criterion: 2 points
- Each character type criterion (lowercase, uppercase, digit, special character): 1 point
- Not common criterion: 1 point



