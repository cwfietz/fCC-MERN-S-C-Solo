My solo attempt at the [MERN Stack Course - ALSO: Convert Backend to Serverless with MongoDB Realm](https://www.youtube.com/watch?v=mrHNSanmqQ4) by Beau Carnes of freeCodeCamp.org


=>
restaurantsDAO.js

import RestaurantsDAO from "../dao/restaurantsDAO.js"
=>
restaurants.controller.js


import express from "express"
import RestaurantsCtrl from "./restaurants.controller.js"
=>
restaurants.route.js


import express from "express"
import cors from "cors"
import restaurants from "./api/restaurants.route.js"
=>
server.js


import app from "./server.js"
import mongodb from "mongodb"
import dotenv from "dotenv"
import RestaurantsDAO from "./dao/restaurantsDAO.js"
=>
index.js