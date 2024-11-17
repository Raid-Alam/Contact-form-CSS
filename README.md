# Contact-form-CSS
For Contact form stylimg

/* Contact Form Styles */

/* Form container */
.wpcf7 {
    max-width: 700px;
    margin: 0 auto;
}

/* Form input fields */
input[type="text"],
input[type="email"],
input[type="tel"],
textarea {
    font-size: 14px !important;
    width: 100%;
	height: 45px;
    padding: 10px; 
    margin-bottom: -5px;
    border: 1px solid #06052f; /* Base color for field border */
    border-radius: 4px;
    font-family: 'Poppins', sans-serif; /* Use Poppins font */
}

textarea { height: 150px;
!important
}

/* Style for labels */
label {
  display: block;
  margin-bottom: -20px;
  font-weight: bold;
  font-size: 14px !important;
  font-family: 'Poppins', sans-serif; /* Use Poppins font */
}

/* Placeholder font size */
::placeholder {
    font-size: 12px !important;
    font-family: 'Poppins', sans-serif; /* Use Poppins font */
}

/* Active field border color */
input[type="text"]:focus,
input[type="email"]:focus,
input[type="tel"]:focus,
textarea:focus {
    border: 2px solid #06052f !important;
}

/* Form submit button */
input[type="submit"] {
    background-color: #06052f; /* Base color for button background */
    color: #fff;
    padding: 15px 40px;
    border: none;
    border-radius: 3px;
    cursor: pointer;
	display: block;
    margin: 0 auto;
    font-size: 16px;
    font-family: 'Poppins', sans-serif; /* Use Poppins font */
}

input[type="submit"]:hover {
    background-color: #f8b526; !important /* Hover color for button */
}
