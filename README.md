# Admission_Enquiry_Form
## Date:07-07-2025
## Sachin B
## 212222060207

## Objective:
To design a simple Admission Enquiry Form using basic HTML that collects student details such as name, contact, program of interest, and a message for further communication.

## Tasks:
#### 1. Set Up the HTML Structure:
Use <!DOCTYPE html>, <html>, <head>, and <body> tags to define the document structure.
Set the <title> as "Admission Enquiry Form".

#### 2. Add a Page Heading:
Use `<h1>` to title the page as “Admission Enquiry”.

#### 3. Create the Form Layout:
Use the <form> tag to wrap all input elements. Set method="post" for structure.

#### 4. Add Input Fields:
Include the following fields using appropriate HTML elements:

Full Name

Email Address

Phone Number 

Program of Interest 

Message

#### 5. Add Submit and Reset Buttons:
Use submit and reset at the bottom of the form.

#### 6. Use HTML-only:
No CSS or JavaScript is to be included. Focus on structure and accessibility.

## HTML Code:
```
<!DOCTYPE html>
<html>
<head>
    <title>Saveetha Engineering College - Admission Enquiry</title>
</head>
<body>
    <h1>Admission Enquiry Form</h1>
    <form>
        <label>Full Name:</label><br>
        <input type="text" name="fullname"><br><br>

        <label>Email Address:</label><br>
        <input type="text" name="email"><br><br>

        <label>Mobile Number:</label><br>
        <input type="text" name="mobile"><br><br>

        <label>Gender:</label><br>
        <input type="radio" name="gender" value="Male"> Male
        <input type="radio" name="gender" value="Female"> Female
        <input type="radio" name="gender" value="Other"> Other<br><br>

        <label>Date of Birth:</label><br>
        <input type="text" name="dob" placeholder="DD/MM/YYYY"><br><br>

        <label>Department Interested:</label><br>
        <select name="department">
            <option>CSE</option>
            <option>ECE</option>
            <option>MECH</option>
            <option>EEE</option>
            <option>CIVIL</option>
            <option>IT</option>
        </select><br><br>

        <label>Academic Qualification:</label><br>
        <textarea name="qualification"></textarea><br><br>

        <label>Address:</label><br>
        <textarea name="address"></textarea><br><br>

        <label>Preferred Mode of Contact:</label><br>
        <input type="checkbox" name="contact" value="Email"> Email
        <input type="checkbox" name="contact" value="Phone"> Phone<br><br>

        <input type="submit" value="Submit">
    </form>
</body>
</html>
```


## Output:

![Screenshot 2025-07-07 130419](https://github.com/user-attachments/assets/44d2dbf4-b914-435a-93f8-b96f8268a13a)



## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
