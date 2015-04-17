# smis
#information system
#School Information Management Application
Definitions:
School
    Name of school
    Registration number
    Telephone
    Mobile
    Level (Nursery, Primary, Secondary, Other)
    Type (Private, Government, UPE, USE, etc)
    Postal address
    Physical address
    Email address*
Student
    Id
    First name
    Middle name
    Last name
    Profile photo
    Date of birth
    Gender
    Student Id
    Next of kin
    Year of admission
    Identification (add attachement)
    Sponsor*
    Status*

Staff
    Id
    First name
    Middle name
    Last name
    Staff role Id

Staff role
    Id
    Title
    Description

Class/Stream*
    Id (S1 , S2 , S3 , S4 , S5 , S6)*
    Stream (North , East , West , South , Blue)*    
		
Subject
    Id
    Title
    Exam code

Academic term
    Id
    Title

Score type
    Id
    Title
    Description

Grade
    Id
    Title
    Description

Score comments
    Score Id
    Date
    Comment text
    Comment by Id

Score
    Id
    Date
    Student Id
    Subject Id
    Term Id
    Mark type Id
    Score(BOT) value*
    Score(MID-TERM) value*
    Score(EOT) value*
    Score(FINAL) value*
    Grade Id
    Scored by Id
    Revision Id

Time table*
    Day of the week*
    Class*
    Stream*
    Subject*
    Time/period*
    Subject teacher*
    Class room/venue*

Parents/Sponsor*
    First Name*
    Middle Name*
    Last Name*
    Contact Address*
    Student's First Name | Last Name*

Pages:
Main
    About us
    Partners
    Support
    Services*
    Sign up
    Sign in*
    FAQ
    Getting started guide
    Forum
    Documentation
    Contact

Sign up (for school)
