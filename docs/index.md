# Ethos Project

## Overview

This site hosts the documentation for the heat early warning system developed by the [Ethos Project](https://www.griffith.edu.au/research/climate-action/climate-transitions/health/ethos-project) at [Griffith University](https://www.griffith.edu.au/) with funding provided by the [Wellcome Trust](https://wellcome.org/) (grant 224709/Z/21/Z: 'Individualised heat-health early warning systems: A novel digital solution', held by S. Rutherford, A. J. E. Bach, S. Binnewies).

The Ethos Project aims to provide a heat Early Warning System (EWS) for vulnerable populations, such as older adults. It achieves this through real-time monitoring of ambient conditions (ambient temperature and relative humidity) using sensors placed around a user's place of residence. These sensors then transmit that information to a base station which then processes and displays that data as well as forwards it to the server. There is also an optional smartphone app developed by the Griffith App Factory which can act as an alternative User Interface (UI) to the base station by connecting to the server.

![System](assets/system.JPG)
*Photo of the Ethos system. From left to right: indoor sensor, outdoor sensor, base station, indoor sensor x2.*

## Architecture

The project is largely comprised of three main components:

1. Ethos Base Station - This is the heart of the system and is responsible for: receiving transmitted sensor information, processing that information to calculate risk based on user information and forwarding the sensor/risk information to the server.
2. Ethos Temperature Sensor(s) - These are the individual sensors which read the ambient temperature and relative humidity and transmit that information to the base station using radio communication.
3. Ethos Server - This receives and stores the user's temperature/humidity data in a database. It is also responsible for sending surveys during heatwaves, as well as storing the survey answers. All stored data is de-identified.

TODO - diagram

## Hardware

TODO
