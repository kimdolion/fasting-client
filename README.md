# Intermittent Fasting
An app to track and see statistics about intermittent fasting efforts.

This prompt came from [Medium Article: 10 Coding Prompts for Your Portfolio](https://medium.com/@PurpleGreenLemon/10-coding-prompts-for-your-portfolio-4a5266d86ede).

![Fasting Langing Page](public/BobaLanding.png)

![Fasting Stats]()

[Front-end Client](https://kimdolion.github.io/fasting-client/#/)

[Front-end Repo](https://github.com/kimdolion/fasting-client)

[Back-end Client](https://limitless-everglades-63033.herokuapp.com/)

[Back-end Repo](https://github.com/kimdolion/boba-tracker-backend)

## Technologies Used
React, React Boostrap, Axios, MongoDB, Express, HTML, CSS, JS

## Setup and Installation
##### Setup and intialize to local/remote and Git Pages
Install dependencies and work with locally with Grunt
- Use `npm` to install dependencies
  - Installed additional dependency React-color to test color pickers
- Use `npm run deploy` to deploy to Git Pages

**User** has many **Timers**

  <table style="display:inline">
  <th colspan="2" style="text-align:center">Timers</th>
  <th colspan="2" style="text-align:center">User</th>
  <tr>
  <td>_id</td>
  <td>MongoDB generated</td>
  <td>_id</td>
  <td>MongoDB generated</td>
  </tr>
  <tr>
  <td>flavor</td>
  <td>string</td>
  <td>email</td>
  <td>string</td>
  </tr>
  <tr>
  <td>datePurchased</td>
  <td>date</td>
  <td>hashedPassword</td>
  <td>string</td>
  </tr>
  <tr>
  <td>location</td>
  <td>string</td>
  <td>token</td>
  <td>string</td>
  </tr>
  <tr>
  <td>cost</td>
  <td>number</td>
  <td>timestamps</td>
  <td>datetime</td>
  </tr>
  <tr>
  <td>color</td>
  <td>string</td>
  <td></td>
  <td></td>
  </tr>
  <tr>
  <td>owner</td>
  <td>ref to user</td>
  <td></td>
  <td></td>
  </tr>
  </table>


  #### Timer actions currently supported:
  - Create timers
  - (Read) See
    - All timers
    - All timers by owner
    - Show timer by id
  - Edit your timers
  - Delete your timers

##### End Point Testing

<ul style="list-style-type:none;">
  <li>get -> #index, #show</li>
  <li>post -> #create</li>
  <li>patch -> #update</li>
  <li>delete -> #destroy</li>
</ul>

## Resource Routes
`user routes`:
  - `/sign-up` - POST for sign up credentials
  - `/sign-in` - POST for sign in credentials
  - `/users` - GET for list of users
  - `/change-password` - PATCH for updating credentials
  - `/sign-out` - DELETE for sign out

`timers routes`:
  - `/timers` - GET for index of timers
  - `/timers/:id` - GET for individual timers
  - `/timers` - POST for timers creation (applies ownership)
  - `/timers/:id` - PATCH for editting timers (requires ownership)
  - `/timers/:id` - DELETE for deleting timers (requires ownership)

## Development Process
Post General Assembly's Software Engineering Immersive, I felt I had many ideas that had lofty goals that I didn't necessarily feel prepared to tackle just yet. I also wanted to try to follow someone else's requirements to create this app.


## Problem Solving
###
TBD

## Unsolved Problems
TBD

## Wireframes and User Stories

[User Stories](https://docs.google.com/document/d/1rU0EMt1qlRVzYi5IN6PDTBv9FH-f241SB1buLiKU5VY/edit?usp=sharing)

[Wireframes](https://docs.google.com/document/d/1Bmr5gQ1BCXurel8O9UvznKwcHkwt-F_cnnR5uouSSXA/edit?usp=sharing)

[ERD](https://docs.google.com/document/d/1KAxKF9fMoZRf_MedIocuvrfn7yVN1JOpxzY0Z7Bnkl0/edit?usp=sharing)

## Stretch Goals



## Additional Resources
[Medium Article: 10 Coding Prompts for Your Portfolio](https://medium.com/@PurpleGreenLemon/10-coding-prompts-for-your-portfolio-4a5266d86ede)
