# photo-critic

A simple MEAN-stack-based photo-critiquing website. An idea posed by my fiance, and an excellent way to test out my WebDev skills.

## Requirements

### 30,000 foot view

* Provide an outlet for photographers to share their pieces with other users of the site in order to get (anonymous or not) critiques about their work.
* Critique can come in the form of thumbs-up/thumbs-down simple mechanic, text area with general feedback, or structured questions provided by the artist. (Any combination)
* Critique can be anonymous or non-anonymous, and can be specified by the owning artist, if they want.
* To prevent abuse or spam, the owner of the art can choose to flag/report critiques, which will soft-ban the user from providing feedback to that user until an administrator of the website can analyze the reported content and act appropriately. Legitimate reports will lead to warnings/permanent bans of accounts, as appropriate.
* Users can upload their photographic art, creating pages for the critique.
* Critique pages can be tagged to provide search terms for users that want to critique photos.
* Users can choose to search for certain things to critique via keyword, artist name or just a random stream of photos.

### Users

* Users should be able to login or register a new account.
* Only an email address and password should be required to sign up (add other ways to login, via passport.js, later)
* User will need to validate their account through that email address (maybe? or maybe go the reddit route, where you can sign up without an email address but that means you can't reset your password.)
* 
