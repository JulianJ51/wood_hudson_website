# wood_hudson_website
paypal code information: https://developer.paypal.com/home/?_ga=2.165074684.293061184.1757168308-1780809195.1757168308&_gac=1.14304581.1757168308.CjwKCAjwt-_FBhBzEiwA7QEqyHQxPOdU5e7_rhJVP53avt93iFaSzJjNzWcUicIX1bz7zxVRn19F2RoC4D8QAvD_BwE


Steps for Julian:
    1. Add this package: Microsoft.AspNetCore.Authentication.JwtBearer (Version 8)
Add these secrets by right clicking on solution and clicking "Manage User Secrets" :
 
    2. {
  "Auth0": {
    "Authority": "https://dev-vrnk33waxoeez2jy.us.auth0.com",
    "Audience": "https://reciplease-api"
  }
}