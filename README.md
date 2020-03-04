# stock-portfolio-webapp
Parent Repo for the two submodule repos

# Link to deployment: https://stock-port.herokuapp.com/
# Link to demo: https://youtu.be/j6Wr_pDs3Nk
# Link to blog: https://medium.com/@bennylouie/stock-portfolio-app-1b0e9e261fae

This is my web-based stock portfolio app I built using Ruby on Rails for my backend and React for my frontend. 
The app pulls data from the IEX Cloud API. 
BCrypt and JWT tokens are used for security and authorizations. 
Redux is used to manage state in the front end and React-Router helps with navigation.

## Instructions

1) `cd stock-portfolio-backend`
2) `bundle`
3) `rails db:seed`
4) `rails s`

5) `cd stock-portfolio-frontend`
6) `npm i`
7) `npm start`
