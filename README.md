# HTML-HW


* This task will comprise of multiple parts - to keep a handle on changes, you will need to create a new repository.
Either create a  public repository in github and clone to your PC, or init a new repo on your PC and then push it to a new repo in github.

* Each part of the task will consist of one branch with multiple commits, instructions below will tell you when to commit your changes.
* After each task is done - merge your changes to the main(or master) branch - the next task will be based on it.

Instructions

1. In your repo - create a new branch from main, name it 'feature/form-base'
2. Create your base files - index.html, style.css
(If you want to experiment with events - Feel free to add a script.js file and import it to your html)
-- commit your changes here.
3.In index.html - create your base html template and add a 'form' tag to body.
4. Create your form - try to get as close to the attached picture as possible with css and wrappers.
-- commit your changes here.
5. set up the form submit - it shoud send a post request (and not a get). 
(currently - the form action should be empty)
6. test your form body - using developer tools, open the network tab and watch the request. is the form sending the correct data?
fix form names if needed.
-- make a last commit and push your changes - this branch will be used for code review and comparisons later.
7. merge the branch to main branch.


** feel free to experiment with styling, events and other field types.
Guidelines:

1. Each form field (input, select etc.) must have a label attached - use div/p/span wrappers to apply correct styling if needed.
2. Form areas ('User Details' etc.) should be wrapped in 'fieldset' and use legend to match. explore fieldset/legend
3. it is recommended to create a basic css reset for the elements in the form.
4. Form validation:
required fields: first name, last name, email
email should have an email validator, phone should either be a number field, or a tel field with the correct pattern
5. each field should have a name attribute and an id.
6. form width is 400px with 20px padding, notice the fields are alined properly. 
specifically - select fields and input fields are harder to align. do not try to set width manually - instead investigate the elements and find a setting that allows select and input elements to match (to experiment - first try  to align the textarea and select as they both should be 100% width.
7. use placeholders where needed
8. check that moving around the form with the tab button works properly, if it doesn't - check the element order in the html.
9. for buttons - use button tag and set the types to allow for submit and reset. add a hover style to your buttons.

10. notice - when you move with tab key, a black outline is formed around your fields. read about outline and why it's there
