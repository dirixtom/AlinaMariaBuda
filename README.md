# Test Project

### Before you start:

All documentation you will need for this test can be found in following links, this test will focus on your ability to adapt to a new environment, in this case Marketo.
The general documentation of Gulp & SASS are included as well, just in case.

1. https://docs.marketo.com/display/public/DOCS/Create+a+Guided+Landing+Page+Template
   - To update H1, H2 titles and make button editable
2. https://developers.marketo.com/rest-api/assets/forms/examples/
   - You can copy-paste the example at `Set Form Field Values` into the form below.
3. https://gulpjs.com/docs/en/getting-started/quick-start/
   - You won't need this, everything is set up for you in the gulpfile.js already
4. https://sass-lang.com/documentation  

Note that we use a version of Gulp-SASS for this project and Gulp runs all tasks and dependencies.

**Approximate values are fine! Do not lose time by nitpicking colors, font sizes, paddings, border radius, ... in reality these are received through brand guideline files or existing assets**. 

### Requirements:

- The project requires dependencies, those are missing. Install Gulp, install the dependencies and compile the project using the 'gulp' command. The gulpfile is already configured.
  - run `npm install` and ignore the vulnerabilities, this test doesn't focus on fixing them and can run without fixes then run `gulp`
- Embed Marketo form to the landing page using the snippet below:
```
<script src="//engage.leadfabric.com/js/forms2/js/forms2.min.js"></script> <form id="mktoForm_1139"></form> <script>MktoForms2.loadForm("//engage.leadfabric.com", "128-VAK-565", 1139);</script>
```
- Add SASS style & Marketo form to recreate the [design](/app/img/brief.png) provided in the [img folder](/app/img), all other assets can be found in [this folder](/app/img) as well.
- Make H1 & H2 titles editable in according to the Marketo syntax.
- Make banner "button" editable. Both text and href, according to the Marketo syntax.
- Make a small javascript that prefills your first name, last name and email address in the Marketo form in the script file. Not inline in the HTML. Use the MarketoForms2 JS Library.
- Remove the 'dist' folder from the .gitignore file, stage & commit your changes and let your contact within LeadFabric know you're done, including a link to your fork/branch or create a pull request.


Good luck!
