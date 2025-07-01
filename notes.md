## The challenge

Your challenge is to build out this contact form and get it looking as close to the design as possible. Pay particular attention to making this form accessible. Building accessible forms is a key skill for front-end developers. So this is a perfect challenge to practice.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Your users should be able to:

- Complete the form and see a success toast message upon successful submission
- Receive form validation messages if:
  - A required field has been missed
  - The email address is not formatted correctly
- Complete the form only using their keyboard
- Have inputs, error messages, and the success message announced on their screen reader
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

## Mobile

- Single card with verticle felxbox layout with 3 seperate sections 24 px margin fully around and 16px border radius(add faint box shadow for enhanced visuals here)
  - Form Content
  - Consent Checkbox
  - Submit button

### Form Content

- contains the title and fields with a 32px gap between title and fields
- fields for first name, last name, email address, query type and message. Additionally each field should have its proper input type.
- Each field should also contain error text that will be dynamically displayed by js when a required field is not filled out, or filled out properly. (all fields for this form are required)
- each field should hold a 24px gap. e.g, there should be a 24px gap between the field and the label of the next input( firstname input gap last name label)
- query type is a differnt field set(own container possibly?)
  - 16 px gap between the title block (query type title) and the radio selection container
  - radio section container also holds a 16px gap between the 2 options

### Consent Checkbox

- Check box input and consent message with a horizontal flexbox layout.
- Consent message and checkbox input should have a 16px gap.
- Consent message padding right of 16px.
- Consent checkbox message to also hold an error message if not checked.

### Submit Button

- Not much to it 100% width with 8px border radius