Build HTML form with inputs	
Style with CSS	
JavaScript validation	
Show error messages	
Prevent submission on errors	
Show success message	
Test edge cases	
Regex for email validation

🔍 Edge Case Testing Checklist
Test the form using:
Empty Name / Email / Message
Invalid Email like: user@domain, @domain.com, user@.com
Email with special characters: user.name+test@domain.co.uk ✅
Normal valid inputs

🔍 Validation Summary:
Field	Validation Rule
Name	Required (not empty)
Email	Required and must be valid email format
Message	Required (not empty)

✅ Optional Enhancements:
Use HTML5 input types like type="email" for better mobile support.
Use Bootstrap or other CSS frameworks for styling.
Add a loader or spinner during submission.
