# Project Wiki

## Requirements

[x] Amazon Developer Account
[x] Amazon Web Services Account
[] AWS Lambda

## Resources

- [Alexa Skill Kit (ASK) Index](https://developer.amazon.com/en-US/docs/alexa/ask-overviews/what-is-the-alexa-skills-kit.html#:~:text=Skills%20are%20like%20apps%20for,to%20control%20cloud%2Dconnected%20devices.)
- [What is the ASK](https://developer.amazon.com/en-US/docs/alexa/ask-overviews/what-is-the-alexa-skills-kit.html)
- [ASK Glossary](https://developer.amazon.com/en-US/docs/alexa/ask-overviews/alexa-skills-kit-glossary.html)
- [Index of Skill Types](https://developer.amazon.com/en-US/docs/alexa/ask-overviews/list-of-skills.html)
- [Skill Certification Requirements](https://developer.amazon.com/en-US/docs/alexa/custom-skills/certification-requirements-for-custom-skills.html)
- [Beginner's guide to building Alexa skills](https://developer.amazon.com/en-US/alexa/trainings_and_workshops)
- [Alexa Skills Toolkit for Visual Studio Code](https://developer.amazon.com/en-US/docs/alexa/ask-toolkit/get-started-with-the-ask-toolkit-for-visual-studio-code.html)
- [ASK CLI - getting started](https://developer.amazon.com/de-DE/docs/alexa/smapi/quick-start-alexa-skills-kit-command-line-interface.html)
- [ASK CLI - mini tutorial](https://www.youtube.com/watch?v=Z1pVgsAKmYI)
- [Alexa Skills Store](https://www.amazon.com/alexa-skills/b?ie=UTF8&node=13727921011)
- [Tips for writing Utterance](https://alexa.sana.ai/s/30MdMhV0h_ea/file:W65x6NwKWWQU)

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

### Selecting and Formating the Invocation Name/Phrase

- The skill invocation name is OFTEN the same as the skill name, although not required
- Enter the invocation name in all lower-case, space and apostrophes as needed
- DO NOT USE: names of people, places, and brands -- PCExpress (is not suitable)

### Intent and Utterance

- An utterance is a user request
- An user 'utterance' maps to an 'intent'
- For example, user: 'alexa, < insert utterance/skill >' -- this request will map to a single intent 'LaunchIntentRequest' that will result in a response
