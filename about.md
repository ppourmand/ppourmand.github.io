---
layout: page
title: About
permalink: /about/
---

Hi there! My name is Pasha and I'm a software engineer with experience in both DevOps and iOS development. I'm currently searching for opportunities as an iOS developer so if it feels like a good fit, please reach out! You can browse my ios-specific resume [here](/static/pasha-pourmand-ios-resume.pdf) or I've listed out my _full_ experience below.

Check out my apps [SkyDroplet](https://apps.apple.com/us/app/skydroplet-weather-forecast/id6479719868) or [EasyCongress](https://apps.apple.com/us/app/easy-congress/id1522413054) on the Apple Appstore.


## Work Experience
### NortonLifelock (2017 - 2023)
#### iOS Team (2021 - 2023)
- Isolated features from the Norton Security iOS application into distinct frameworks, allowing for
customizable user interfaces and facilitating the implementation of white-labeling capabilities for
third-party partners. Reduced the turnaround time for launching partner applications
- Collaborated with the UX team to implement new onboarding flows and overall redesign of the Norton
Security iOS application to enable higher customer retention and improve App Store rating
- Spearheaded transition from Carthage to SwiftPM; created a Swift tool that parsed dependencies from
Xcode project files and generated binary distribution Package.swift files during the build process,
allowing developers to easily release and consume versioned binary frameworks in Artifactory

#### Mobile DevOps Team (2019 - 2021)
- Led team building new CI/CD infrastructure and pipelines for all Norton mobile applications. Decreased
build and test time from an hour to 15 minutes, which resulted in faster feature development, fewer bugs,
and made it possible to release to TestFlight or Playstore Beta on every commit
- Enhanced developer productivity by creating a web app that used the Bitbucket Server API to kick off automated builds, report build statuses from Azure DevOps, and enable developers to run new builds
when needed via Bitbucket comments
- Created dockerfiles and scripts to enable spinning up new on-prem mac OS and Linux VMs easily with all
mobile dependencies required, making it trivial for any developer to expand the build machine pool
- Drove adoption of standardized git branching strategy across iOS and Android teams, which led to more
consistency across teams and less issues during conflict

#### Tools Team (2017 - 2019)
- Increased overall release velocity of Norton VPN. Implemented automation libraries in Python that
decreased the time it took to verify release candidates by several weeks
- Established performance measurement and improved test engineer experience for Norton Security. Led
development and maintained a Python package that allowed test engineers to provision virtual machines
for installing Norton Security and build test scripts
- Mentored test engineers to improve their development skills, including version control (git), Python, code
reviews, and automation

## Personal Projects
### [SkyDroplet](https://apps.apple.com/us/app/skydroplet-weather-forecast/id6479719868)
- A comprehensive iOS weather and calendar application, providing users with real-time weather conditions, hourly
forecasts, and 10-day forecasts, developed in Swift
- Integrated WeatherKit API to fetch accurate weather data, CoreLocation and MapKit frameworks for
seamless location lookup, and EventKit to integrate weather data into the users’ calendar
- Created custom lockscreen and homescreen widgets using SwiftUI, enhancing user accessibility and
providing at-a-glance weather information

### [EasyCongress](https://apps.apple.com/us/app/easy-congress/id1522413054)
- A tool for users to easily consume information on bills being worked on in the U.S. Congress
- Built using Swift and SwiftUI
- Bill data provided by the United States Government Publishing Office via XML API and cached with
CoreData