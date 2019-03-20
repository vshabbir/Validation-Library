# Validation-Library
Validator js is a javascript + jquery library developed for form validation.It is a super easy library to use with number of different validation rules.
Please feel free to report any bugs or issues

Why use validator js?
1 - It is a super easy library to implement,which can be embeded directly into your html tags code just like the default html 5 validation.
You heard it right,no javascript code required for basic validation.

2 - Ever wanted a validation which cannot be altered?
If yes,then this is the perfect library for your need.Rules and validation once applied using validator js cannot be manipulated using the dom.

3 - Number of different validation rules which will help you accomplish your client side validation with just one line.

Requirements - 
- JQuery

Installation
- Download or clone the repositry.
- Include the validator.js file in your project.Include it after you include all the other librarys.
All set now you are ready to go...

Basic implementation
Once you have included the js and the requirements you can start using the library with your form.

Adding required and email validation for a form

<html>
<head>
  <title>Validator JS</title>
</head>
<body>
  <form>
    <div>
      <label>Email Id</label>
      input type="text" name="email" rules="required email"       ==> when using in html file please add the tags
    </div>
  </form>
  <script src="jquery-file.js"></script>
  <script src="validator.min.js"></script>
</body>
</html>
