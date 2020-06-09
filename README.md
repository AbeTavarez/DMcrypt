# DMcript README <!-- omit in toc -->

> Project Planning section:
>
>

- [Overview](#overview)
- [MVP](#mvp)
  - [Goals](#goals)
  - [Libraries](#libraries)
  - [Client (Front End)](#client-front-end)
    - [Wireframes](#wireframes)
    - [Component Tree](#component-tree)
    - [Component Hierarchy](#component-hierarchy)
    - [Component Breakdown](#component-breakdown)
    - [Component Estimates](#component-estimates)
  - [Server (Back End)](#server-back-end)
    - [ERD Model](#erd-model)
- [Post-MVP](#post-mvp)
- [Code Showcase](#code-showcase)
- [Code Issues & Resolutions](#code-issues--resolutions)

<br>

## Overview

_**DMcrypt** is a Chat App web application build with privacy and security in mind. Sign-up with your e-mail and start sharing messages with your friends. Create group chats with your friends in a secure and private enviroment. This can be very useful when dealing with confidential information._
  

<br>

## MVP

_**DMcrypt** Application would allow the user to sign-up using their personal email and password.
Email needs to be confirm by the user before signing-in. After the user has been authenticated he or she can start sending messages to other users and will also be able to create private groups and invite friends to join the group chat._

<br>

### Goals

- _Create back-end using Ruby On Rails._
- _Create front-end using React JS._
- _Create models for the database._
- _Create Auth for the users._
- _etc._

<br>

### Libraries

> Supporting libraries and dependencies, and their role in the project.

|     Library      | Description                                |
| :--------------: | :----------------------------------------- |
|      React       | _Front-end Library._ |
|   React Router   | _Routing for React._ |
| React SemanticUI | _Front-end UI Framework._ |
|      Axios       | _Lorem ipsum dolor sit amet, consectetur._ |
|      Rails       | _Lorem ipsum dolor sit amet, consectetur._ |
|    PostgreSQL    | _Lorem ipsum dolor sit amet, consectetur._ |
|  JSOn Web Token  | _Lorem ipsum dolor sit amet, consectetur._ |
|     bcrypt       | _Lorem ipsum dolor sit amet, consectetur._ |
|      CORS        | _Lorem ipsum dolor sit amet, consectetur._ |

<br>

### Client (Front End)

#### Wireframes

> Wireframes section to display desktop, tablet and mobile views.

- Wireframe
![Dummy Link](https://res.cloudinary.com/abetavarez/image/upload/v1591708968/Screen_Shot_2020-06-09_at_9.20.35_AM_cwfsgv.png)

- Desktop Landing
![Dummy Link](https://res.cloudinary.com/abetavarez/image/upload/v1591709619/Screen_Shot_2020-06-09_at_9.33.19_AM_odi00j.png)


- App Flowchart
![Dummy Link](https://res.cloudinary.com/abetavarez/image/upload/v1591709132/Screen_Shot_2020-06-07_at_10.43.20_PM_wqisxj.png)

- Resource Show
![Dummy Link](url)


- Tablet Resource Index
![Dummy Link](url)


![Dummy Link](url)

- Mobile Resource Index

#### Component Tree

> Structure of how your React components are being rendered. This should show the parent to child relation between you components. In other words, show which components are rendering the other components. 

#### Component Hierarchy

> React components and the data architecture of app. Expected your directory/file tree. 

``` structure

src
|__ assets/
      |__ fonts
      |__ graphics
      |__ images
      |__ mockups
|__ components/
      |__ Header.jsx
|__ services/

```

#### Component Breakdown

> Use this section to go into further depth regarding your components, including breaking down the components as stateless or stateful, and considering the passing of data between those components.

|  Component   |    Type    | state | props | Description                                                      |
| :----------: | :--------: | :---: | :---: | :--------------------------------------------------------------- |
|    Header    | functional |   n   |   n   | _The header will contain the navigation and logo._               |
|  Navigation  | functional |   n   |   n   | _The navigation will provide a link to each of the pages._       |
|   Gallery    |   class    |   y   |   n   | _The gallery will render the posts using cards in flexbox._      |
| Gallery Card | functional |   n   |   y   | _The cards will render the post info via props._                 |
|    Footer    | functional |   n   |   n   | _The footer will show info about me and a link to my portfolio._ |

#### Component Estimates

> Use this section to estimate the time necessary to build out each of the components you've described above.

| Task                | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------- | :------: | :------------: | :-----------: | :---------: |
| Add Contact Form    |    L     |     3 hrs      |     2 hrs     |    3 hrs    |
| Create CRUD Actions |    H     |     3 hrs      |     1 hrs     |     TBD     |
| TOTAL               |          |     6 hrs      |     3 hrs     |     TBD     |

> _Why is this necessary? Time frames are key to the development cycle. You have limited time to code your app, and your estimates can then be used to evaluate possibilities of your MVP and post-MVP based on time needed. It's best you assume an additional hour for each component, as well as a few hours added to the total time, to play it safe._

<br>

### Server (Back End)

#### ERD Model
![Dummy Link](https://res.cloudinary.com/abetavarez/image/upload/v1591709353/Screen_Shot_2020-06-09_at_9.29.04_AM_seq46h.png)

> ERD

<br>

***

## Post-MVP

> Use this section to document ideas you've had that would be fun (or necessary) for your Post-MVP. This will be helpful when you return to your project after graduation!

***

## Code Showcase

> Use this section to include a brief code snippet of functionality that you are proud of and a brief description.

## Code Issues & Resolutions

> Use this section to list of all major issues encountered and their resolution, if you'd like.
