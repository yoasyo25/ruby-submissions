### Project Option 1: CryptoBox
Let’s create an app to record your ideas. Host your app live on Heroku.

#### Cryptocurrency

• [ ] A Cryptocurrency can be created by a user. (with attributes name, amount, symbol, image)
• [ ] A Cryptocurrency can be edited/updated only by the user that created it.
• [ ] A Cryptocurrency can be destroyed only by the user that created it.
• [ ] When a user types a Cryptocurrency into the form, there is a selection dropdown for choosing the correct category (Proof of Stake vs. Proof of Work). See Categories below for more information.

#### Categories

• [ ] Cryptocurrency belong to a category.
• [ ] Categories can be created and destroyed by a logged-in admin user (regular logged in users cannot create categories).
• [ ] Categories can be destroyed by a logged-in admin user (regular logged in users cannot destroy categories).

#### Images
• [ ] Users can add an image to their own Cryptocurrency.
• [ ] An image can have many Crypto currencies and a Cryptocurrency can have many images.
• [ ] Images can only be created by an admin user.
    - The most simplistic way to implement images is to store a url to an online image. If you’re feeling fancy and want to upload your own images, check out Carrierwave

#### Authentication and Authorization
• [ ] Users need to log in to see their Crypto currencies.
• [ ] Users can only see their own Crypto currencies – they should not be able to visit another user’s page.
• [ ] Users cannot create Crypto currencies for other users.
• [ ] Users cannot create new categories – only the admin can do that.
• [ ] Users cannot create images – only the admin can do that; however, a user can assign an image to their Cryptocurrency.
• [ ] Visitors can create user accounts.

#### Optional Extensions
•    Implement Twitter, Github, or Facebook OAuth login
•    Use HAML for your views
•    TDD using RSpec instead of Test::Unit
