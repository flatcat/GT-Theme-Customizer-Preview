GT-Theme-Customizer-Preview
===================

The idea is for Guests to be able to "Try Out" customizing your wordpress theme's options without registering an account.

** This is ALMOST ready for production use. **

Usage:
A test user is automatically created the first time you visit the customizer username="Test"

A short code is available to automatically let guests login.

[GTCustomizer]Click here to Preview this theme's Customizer[/GTCustomizer]

After the guests click that link, they are logged in as the "test" user with access to a read-only copy of the wordpress live customizer.

A Menu Item is added to the admin bar so they can use the customizer.

TO DO:
1. There's two places where a static path to wordpress files is set
2. Add a theme selector to the customizer.
3. Make some options for changing the default test account's username, and a list of available themes to choose from.
4. Stop the Test user from modifying their own account. OR just allow anon access if that's possible.


Double and Triple, check the security.


Note:
I'm sure it won't work for you if you don't adjust the static links to the wp includes
