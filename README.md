# food-corner-client

Website live-link: https://food-corner-41608.web.app

Server-side-code-link: https://github.com/shishir1809019/food-corner-server

- In this website I have used - **MongoDB || Node || Express || React || React router || React Bootstrap || React-stars-component || Material UI || Firebase || Firebase idToken || ContextApi || CSS & HTML**
- In this website I had showed some watch with those name , price , description.
- In this website user can purchase product and user has a dashboard where they see and cancel their own purchase.
- Here admin can see , modify, delete all users purchase.
- An admin can also add another admin and add new product.

**Security**

*BASIC*
- do not show the link to them who should not see it only show to the person/types of user who should see it
- Do not allow to visit the link by typing on the url. use AdminRoute that will check whether the user is admin or not if not admin then redirect to any other page. you could logout user  and send them to the login page as well.

*TO SEND DATA*
- verify jwt token (send authorization token in the header to the server). If possible use axios to send jwt token by intercepting the request
- if it is an admin activity. Make sure only admin user is posting data by using verifyAdmin

