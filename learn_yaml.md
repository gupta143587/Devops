# YAML SYNTAXES
- YAML :- Yaml Ain't Markup Language
- File Extension Should be .yml or .yaml
- EX:
   ```
     config-1
     ---
     config-2
   ```
------------------------------------------------------------
# YAML Data Types
## 1. Scalar Data Types
- Numbers: It Can be **Integer** and **Floating** values
    - Ex: 23, 23.5
- Boolean: The Value Can **True** or **False**
    - Ex: is_student: true/false
- Strings: Texts Enclosed in **Single** or **Double** Qutoes
    - Ex:
        - email: "gupta@gmail.com"
- Null: no value represented as **null** or **~**

## 2. Sequence/Array Data Type
- Ex:
    ---
      fruits:
        - apple
        - cherry
        - berry
      fruit: [apple, mango, grapes]
    ...

## 3. Mapping/Dictionary Data Type
- Ex: name: Gupta

--------------
# Types of Strings
## 1. Normal String
- Ex:
    ---
      jobDescription: "I am B Gupta Completed my Btech in **NSRIT** College. I am B Gupta Completed my Inter in **Narayana** College. I am B Gupta Completed my School in **Ravindra Bharathi** School."
      output: 
        I am B Gupta Completed my Btech in **NSRIT** College. I am B Gupta Completed my Inter in **Narayana** College. I am B Gupta Completed my School in **Ravindra Bharathi** School.
    ...

-------------
# YAML Example
  ---
    #Learners Data
    learners:
      learner1:
        name: Gupta
        age: 22
        email: gupta@gmail.com
        isCourseCompleted: False
        stipend: 30.0
        isEmployed: null
        course_enrolled:
          - aws
          - devops
          - azure

      learner2:
        name: Yogesh
        age: 22
        email: yogesh@gmail.com
        isCourseCompleted: True
        stipend: 80.0
        isEmployed: null
        course_enrolled:
        devops:
          - docker
          - k8s
          - Github
          - linux
        cloud: [aws, azure, google]
  ...

  ---
    #Trainer's Data
    learners:
      learner1:
        name: Yogesh Gupta
        age: 22
        email: gupta@gmail.com
  ...