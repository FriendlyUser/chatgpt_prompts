# chatgpt_prompts
List of chatgpt prompts I have used. In the era of AI generated code, I wish to list all the prompts I have created for blog posting, commit message generation and 


## Software Development
### Commit messages

Write an insightful but concise Git commit message in a complete sentence in imperative present tense for the following diff without prefacing it with anything:

`
git diff goes here
`

Rewrite the code below following the Google style guidelines for javascript.

Generate a regex to match [the pattern you want to match]

Generate documentation for the code below. You should include detailed instructions to allow a
developer to run it on a local machine, explain what the code does, and list vulnerabilities that
exist in this code.

Write test cases for the main edge cases that could happen to the below code snippet. First
outline the test cases you'll write. Second, write the test cases in [language] using the [framework]
framework.

Regenerate the code snippet below, but please include comments to each line of code:

Explain this code to me:

I'm building a new frontend app, and want to compare React.js with Vue.js. Please propose the
scope for a simple frontend app, and generate two code bases that fulfill that scope, one using
React.js and another using Vue.js. Please redact clear instructions for me to run both apps on
my local machine.

Generate boilerplate code for an app that integrates to an external API. Please use javascript
code on the express.js framework.


Given the following git commit messages create dev testing notes, do not reference the commits themselves, 
explain what should be tested when [feature name goes here]

### Test case Generation in Jest

Write a test case in jest for the following code:

### Code generation

Implement a job that clears out deactivated phone numbers from twilio in nodejs using bullmq

For fetching the url to download the txt file.

const accountSid = process.env.TWILIO_ACCOUNT_SID;
const authToken = process.env.TWILIO_AUTH_TOKEN;
const client = require('twilio')(accountSid, authToken);

client.messaging.v1.deactivations()
                .fetch({date: new Date(Date.UTC(2020, 8, 5))})
                .then(deactivations => console.log(deactivations.redirectTo));
Where a sample response is

{
  "redirect_to": "https://com-twilio-dev-messaging-deactivations.s3.amazonaws.com"
}
the class should look like

export class JobExecutor {
}

### Bugs
Please find the bug in the code below. This is what it should be doing:
[outline of the desired functionality]
Code:

### Leetcode

Generate code in [desired language] to solve the following challenge:
[outline of the challenge to be solved]


##  Blog Generation

Topic: ChatGpt Script in Python to describe code and get keywords

For the above topic, use future prompts to write for a technical audience for a blog post and give consise explainations for code. Optimize the post for medium and google seo. Ensure this content is original. Respond with 'confirm' to acknowledge that you understand the prompt.


Create a solution to the following problem, make sure to include the problem in the solution and any question numbering given. For example

For the following problem
5. Write a function-like macro that generates a series of getter and setter methods for a struct with the specified fields. The generated methods should follow the Rust convention of `get_<field>` and `set_<field>`.

The output would start with

5. Write a function-like macro that generates a series of getter and setter methods for a struct with the specified fields. The generated methods should follow the Rust convention of `get_<field>` and `set_<field>`.




