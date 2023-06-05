# API Automation Testing with Postman

<h3><ins> Requirement </h3>

- Postman (Obviously)
- Postman CLI (to run it with Pipeline / Command Line)

<h3><ins> To run the test with Pipeline / Command Line </h3>

- Make sure to generate Postman API KEY
- Login on Postman CLI using this command `postman login --with-api-key <YOUR_API_KEY>`
- Run the test with `postman collection run --environment <path/to/environment>.json <path/to/collection>.json`