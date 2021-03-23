# NOTES/Problems
- Figure out schema for followers & following
- Figure out schema for wordpress type blog creator (drag and restructure)
    - Looking at the editing tool wireframe... On the left it seems that the user can select if they are editing the Problem/Research/Solutions/Outcome/Takeaway part of the case study. Is this edited individually by section, or is an overall edit. (i.e., maybe the contributor doesn't want a problem section, or wants to rename 'problem' section to 'issue' section)
- Figure out how to uploade/fetch/save images to rails
- Validations! ex. Unique email, unique username, update password when, password must contain, etc
- Should Admin table be created for non developers to alter information?

- contributor_about_details

# Tables

## contributor
### Notes/Problems

#### Crud Functions
- Full Crud (general)
- C: Create account
- R: View account details
- U: Update account details
- D: Delete account

## contributor_job_detail
### Notes/Problems

#### Crud Functions
- Full Crud (general)

## contributor_about_prompt

## contributor_about_detail
### Notes/Problems
- "Do you work for a company? Which one? (if you don't know, that's ok)?"
    - It's set as a single input. Much easier to develop if there's a checkbox for yes/no. (If yes, input appears/can be typed in. If no, input doesn't appear/cannot be typed into)
- "Skills"
    - Figure out how to add a skill if they select 'other'. Is a new skill created into the backend or just for this one contributor?
- "Industries"
    - Figure out how to add a industry if they select 'other'. Is a new skill created into the backend or just for this one contributor?

#### Crud Functions
- Full Crud (general)

## contributor_about_detail_industry
### Notes/Problems
- Should update be included or update be done through delete and create functions seperately?

#### Crud Functions
- C: Created when contributor_about_detail connects to industry tables
- R: View join table
- D: Delete join table (no updates, update is done through delete and create??)

## contributor_about_detail_skill
### Notes/Problems
- Should update be included or update be done through delete and create functions seperately?

#### Crud Functions
- C: Created when contributor_about_detail connects to skill tables
- R: View join table
- D: Delete join table (no updates, update is done through delete and create??)

<hr />
<hr />

## industry
### Notes/Problems
- Should there be some sort of admin to alter this or changed purely on the dev side?

#### Crud Functions
- Full Crud (general)

## skill
### Notes/Problems

#### Crud Functions

## prompt
### Notes/Problems

#### Crud Functions

<hr />
<hr />

## case_study
### Notes/Problems

#### Crud Functions

## case_study_industry
### Notes/Problems

#### Crud Functions

## case_study_comments
### Notes/Problems

#### Crud Functions

## bookmarked_case_study
### Notes/Problems

#### Crud Functions
