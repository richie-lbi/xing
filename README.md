XING Frontend Playground Introduction  
You've been given the design of a sign-up form by our UX Team. 
We would like you to demonstrate your frontend skills by implementing it using standards-compliant HTML, CSS and JavaScript. 
It should take approximately 2 hours.   

Instructions  
1. Create a project in Github (you will need a Github account) 
2. As you work, please make frequent and meaningful commits. 
3. Add the following validation: o Name is mandatory and must have at least 3 characters. 
	Email must be valid-ish (must contain @ sign and match a top-level domain). 
	Email barcelona-hiring@xing.com with a link to you repository when you're done.  

Restrictions  
• Put all code in one file, including CSS and JavaScript. • Use native JavaScript with no external dependencies (like jQuery). • Your page must be compatible with most modern browsers (use HTML5/CSS3 when possible and at your discretion).   
Things to take into account  
• Assume this is a standalone page. • SEO and speed optimization are a plus (but not at the expense of maintainability). 


		// MY ASSUMPTIONS ON THE BREIF
		
		// A successfully submitted form results in an alert box
		
		// I didn't make any attempt to decide an 'action' or 'method' for the form
		
		// I interpreted 'modern browsers' in the brief as IE8 and above.
		// Although some CSS and HTML5 elements I used aren't supported on IE8,
		// they degrade in a way which doesn't affect the functionality of the form.
		// I opted out of dedicated html5 inputs like number and email for robustness
		
		// E.G. I used html5 placeholder attribute, could use Modernizr to feature detect 
		// on older browsers to provide alternative
		
		// Even though the brief didn't specify TC's were mandatory, I assumed the 
		// checkbox would need to be ticked for successful submission
		
		// With the name validation field I've assumed that white space shouldn't 
		// count as part of the 3 characters and so ignored any spaces included
		// in the input field
		
		// Since there wasn't a PSD to match the font-family/size I've assumed the 
		// font was Arial (the font sizes are also approximate)
		
		// I used asterisks and a red coloured label to denote invalid entries
		// As an extra, I included [commented out] some capability for for error 
		// message text next to inputs and some basic styling
		
		// Validated against http://validator.w3.org/check
