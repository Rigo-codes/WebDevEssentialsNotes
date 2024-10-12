
# Interactive Forms
![The screenshot shows an unstyled HTML form titled "Apply Now" with input fields for name, email, age, resume, and bio, along with validation rules. It ends with a "Submit Application" button.](./assets/images/example.png)

##

## Description 📄
In this assignment, you will create a basic form that includes various media types and validations. This form allows users to submit their personal details such as name, email, age, resume, and a short bio. The form uses basic HTML5 features like input validation and file upload to ensure the data is entered correctly.

## Project Structure

```
Interactive-Forms/
└── index.html
```

## Instructions ✅

## 1. **Create the Project Folder and Files**
   - [ x] Create a folder named `InteractiveForms` to store all your project files.
   
   - [ x] Inside the `InteractiveForms` folder, create a file named `index.html`. 
   
You are now ready to begin coding your basic form with media types and validations!

## 2. **Start with a HTML boilerplate**
Now that you have your files set up, let's add the basic HTML5 boilerplate code.

  - [ x] Open your empty `index.html` file and add the following code to it.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Basic Form with Media Types and Validations</title>
</head>
<body>

</body>
</html>
```

Next, you will build out the form `html` code which will include a header and various input fields, each with specific validations.

## 3. Let's add a Header to our form
Let's add a form header which typically includes a title that informs users of the form's purpose.

 - [x ] Inside the `<body></body>` tags of your `index.html` file add the following code.

 ```html
<h1>Apply Now</h1>

```

**Explanation:**
- The `<h1>` tag defines the main heading of the webpage or in this case a form.
- This is the largest and most important heading tag, indicating the primary purpose of the page, which in this case is "Apply Now."

## 4. Add our Form section tags
Now, we need to use form section tags to wrap the form code, effectively grouping all the related form elements together

 - [ x] Inside the `<body></body>` tags after the `h1` tag add the following code.

   ```html
   <form>
   <!-- Form content goes here -->
   </form>
   ```

**Explanation:**
- The <form> tag in HTML is used to create a form for collecting user input.

## 3. Full Name Input Field:
We will now prompt the user to enter their full name using an input field.

 - [ x] Inside the `<form></form>` tags add the following code.
 
   ```html
   <label for="name">Full Name:</label>
   <input type="text" id="name" name="name" required minlength="2" placeholder="Your Full Name">
   <br><br>
   ```
   **Explanation:**
   - The `<label>` element provides a label for the input field, improving accessibility. 
   - The `for="name"` attribute connects the label to the input field with the id `name`.
   - `<input type="text">` creates a single-line text input.
   - The `required` attribute ensures the field must be filled out before submission.
   - The `minlength="2"` attribute specifies that the input must have at least 2 characters.
   - `placeholder="Your Full Name"` provides a hint to the user of what to enter.
   - `<br>` This is a line break tag used to insert a single line break.

## 4. Email Address Input Field
We will now prompt the user to enter their email address and validate that a valid email address has been provided.

 - [ x] Add the following code after the `<br>` tags from the user's name section.

   ```html
   <label for="email">Email Address:</label>
   <input type="email" id="email" name="email" required placeholder="example@mail.com">
   <br><br>
   ```

**Explanation:**
- `<input type="email">` creates an input field for email addresses, which validates the email format automatically.
- `required` ensures this field is mandatory.

## 5. Age Input Field
Let's collect the user's age using an input field and set a minimum and maximum required number entry.

 - [ x] Add the following code after the `<br>` tags from the user's email section.

   ```html
   <label for="age">Age (18-60):</label>
   <input type="number" id="age" name="age" required min="18" max="60">
   <br><br>
   ```

**Explanation:**
- `<input type="number">` creates a number input field.
- The `min="18"` and `max="60"` attributes restrict the input to between 18 and 60.

## 6. Resume Upload Option:
Let's enable users to submit their resumes through our form and validate that it is a PDF file.

 - [x ] Add the following code after the `<br>` tags from the age section.

   ```html
   <label for="resume">Upload Resume (PDF):</label>
   <input type="file" id="resume" name="resume" accept=".pdf" required>
   <br><br>
   ```

   **Explanation:**
   - `<input type="file">` allows the user to upload files.
   - The `accept=".pdf"` attribute restricts the file type to PDFs.
   - `required` ensures that a file must be uploaded before submission.

## 7. Short Bio Entry
Let's give users the option to include a brief bio in our form.

 - [ x] Add the following code after the `<br>` tags from the resume section.

   ```html
   <label for="bio">Short Bio:</label>
   <textarea id="bio" name="bio" rows="4" maxlength="200" placeholder="Tell us about yourself..."></textarea>
   <br><br>
   ```

    **Explanation:**
   - `<textarea>` creates a multi-line text input.
   - `rows="4"` sets the height of the textarea.
   - `maxlength="200"` restricts the input to a maximum of 200 characters.

## 8. Submit Button
Here, we'll add a submit button to send the form's data.

 - [ x] Add the following code after the `<br>` tags from the user's bio section.

   ```html
   <button type="submit">Submit Application</button>
   ```

   **Explanation:**
   - `<button type="submit">` creates a button that submits the form when clicked.

##

## Testing Suggestions

After completing the form, open the `index.html` file in a web browser to test the form's functionality.

1. Try submitting the form without filling in some of the required fields, such as the name, email, or resume. Observe how the browser prevents the form from being submitted and highlights the missing fields.
2. Try entering an incorrectly formatted email address or an age outside of the specified range (18-60). Observe what happens and how the browser enforces these validations.
3. Ensure all validations work as expected, such as the correct format for email and the age constraints.

# Conclusion 📄

By completing this assignment, you should have gained an understanding of how to create a simple HTML form with various input types and built-in validation. This knowledge is fundamental for collecting user data in web applications.

##

### Solution codebase 👀
🛑 **Only use this as a reference** 🛑

💾 **Not something to copy and paste** 💾

**Note:**  This lab references a solution file located [here](https://github.com/HackerUSA-CE/sdai-wde-02-interactive-forms/blob/solution/index.html) (link not shown).

---

© All rights reserved to ThriveDX
