# Project Wiki

## Requirements

- Amazon Developer Account
- Amazon Web Services Account
- AWS Lambda

## Resources

- [Alexa Skill Kit Glossary](https://developer.amazon.com/en-US/docs/alexa/ask-overviews/alexa-skills-kit-glossary.html)
- [Index of Skill Types](https://developer.amazon.com/en-US/docs/alexa/ask-overviews/list-of-skills.html)
- [Skill Certification Requirements](https://developer.amazon.com/en-US/docs/alexa/custom-skills/certification-requirements-for-custom-skills.html)

## Notes

### What is Alexa Skill Kit?

- Alexa Skills Kit (ASK) enables the creation of 'skills'
- Skills are like apps, they enable developers to add additional functionality (e.g., voice commands)

### How does a user access a Skill?

- Users access skills by using the wake word, 'Alexa, < insert skill >'.

### How does a skill work?

1. Alexa receives the request to invoke a skill and handles the speech recognition
2. Alexa communicates with the skill (residing on a cloud platform) using a HTTPS request-response mechanism
3. The invoked skill receives a POST request containing a JSON body
4. The POST request body contains parameters for your skill to understand the request, perform its logic, and generate a response

- note: project will utilize _pre-built voice interaction model_
