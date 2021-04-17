###### [Home](https://gleebleneeble.github.io/Being-Me-With-IT/)

# Building for name changes

A key part of building for this is to ensure that users understand what's trivial to alter and what requires coordination from IT.

You should have documentation that outlines:
- What users can change by themselves without breaking anything (e.g. preferred names and display names)
- The difference between email aliases and primary emails in terms of change impact (this is especially true if emails are used as logins)
- Other identifiers such as initials-based or otherwise linked user ids that users interact with

This is not intended to scare users away from asking for their name to be changed internally but rather to set expectations around how long it will take and how fiddly it might be. Essentially - set the expectation that working with IT for a little time may be necessary otherwise access may break for them.

## Using your Identity Access Management System

### OneLogin

It's fairly trivial to change the primary email and name of a user in their OneLogin profile. That said - pay attention to your underlying directory setup, for example, name and email changes made in a synced Google directory will be reflected in OneLogin. 

As OneLogin uses OpenIDs as the main identifier for users it's way easier to make changes around that without breaking access.


###### [Home](https://gleebleneeble.github.io/Being-Me-With-IT/)
