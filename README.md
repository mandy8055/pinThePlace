# PinPlace full stack application

![image](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)![image](https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white)![image](https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=material-ui&logoColor=white)![image](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)![image](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)

## App overview
This repo contains the frontend/client side of the full-stack **MERN** application. This application lets the user to pin the places which they visited across the globe and write the comments about the things they liked most about that place and also provide with the suitable ratings. The application also comes with the login and registration functionality. Anybody can view the pins which are already marked by the other users. A user can create the pins if and only if he/she is logged in to the application. The application is tested on **Google Chrome** browser. The application makes use of the [**Mapbox**](https://www.mapbox.com/) API for providing the Map interface.

This application is built by keeping in mind the best practices which can be used to develop a full-stack application. Although, perfection and learning is an life-long process so I will continue to make use of best practices going along. Please visit [**here**](https://github.com/mandy8055/pinThePlace_server#readme) for detailed overview of the backend architecture.

## Features
1. Login and register functionality is properly handled.
2. XSS vulnerability is addressed properly.
3. The pins of the current logged in user is different(**color of pins is tomato**) than that of other users(**color of pins is slateblue**).
4. On double clicking the place on the map, the edit card opens up where you can add the description of the place, provide the rating, etc.
5. Whenever any pin gets clicked, the focussed pin moves to the center of the view-area and then the information is visible.

**CHECKLIST [TODO]:**

- [ ] Implement delete pins functionality for the current logged in user.
- [ ] Add confirm password button to the Register card.
- [ ] Implement different user registration options like Google and facebook login.

## Known bugs
1. [**Mapbox Bug1**](https://github.com/visgl/react-map-gl/issues/1266)
2. [**Mapbox Bug2**](https://github.com/mapbox/mapbox-gl-js/issues/10173)
3. There is one app specific bug which needs improvement. The pins are overlaying the information filling card i.e. the pins are appearing at the top of the information card. It(pins) need to be overridden by the card component.

## Deployment Link

The backend api is deployed **[here.](https://pin-the-place.herokuapp.com/)**

The application is deployed **[here.](https://pin-the-place.netlify.app/)**