# Project-Vision
Postman collections for DellEMC's storage products' REST APIs
## Details
This Avengers' project leverages Postman's import collection capabilities to provide sample API calls for the following products:
 - PowerMax
 - PowerStore
 - PowerFlex (formerly ScaleIO and VxFlex)
 - VPLEX - this collection has been kindly contributed by [Ankur Patel](https://www.youtube.com/channel/UC_Y46gxyBVWH2Xr7qSJ32Kw)
 - ECS management and ECS S3 API - these two collections are courtesy of [Christopher Jenkins](https://github.com/chrisjen83?tab=repositories)
 - Unity
 - XtremIO
 - PowerOne (tested only with the PowerOne simulator)

The goal of the project is to help customers of these products to automate day 1 and day 2 operations by looking at handy examples. API reference guides can sometimes be many hundreds of pages, so by looking at some of the most common operational examples one can kickstart coding efforts. Each collection aims to provide sample calls in these areas:
 - Gather system and hardware information
 - Basic provisioning
 - Performance and event collection

Where possible, API calls in these collections have been provided with a sample response so that developers can more easily see what fields are relevant for their purpose and help fast tracking the coding effort, even if they don't have access to a real array

For more details about the Project Vision and its deliverables visit the following blog posts
http://anzpiper.blogspot.com/2019/12/postman-collections-for-dellemc-block.html
http://anzpiper.blogspot.com/2020/01/project-vision-in-action.html

The following table shows the different environment parameters that are required for each collection
Array | Variable | Variable | Variable
------|----------|----------|----------
XtremIO | ip | pwd | 
Unity | ip | pwd | csrfToken
PowerMax/VMAX | ip | pwd | serial
PowerFlex | ip | pwd | token
PowerStore | ip | pwd | token
PowerOne |  |  | token

For details on the environment requirement for the two ECS collections please visit [Chris Jenkins's repo](https://github.com/chrisjen83/ECS-Postman-Examples)
