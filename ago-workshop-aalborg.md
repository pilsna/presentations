---
layout: plain
progress: true
author_name: Nils Rydh
style: |

    #Cover h2 {
        margin:30px 0 0;
        color:#FFF;
        text-align:center;
        font-size:70px;
        }
    #Cover p {
        margin:10px 0 0;
        text-align:center;
        color:#FFF;
        font-style:italic;
        font-size:20px;
        }
        #Cover p a {
            color:#FFF;
            }
    #Picture h2 {
        color:#FFF;
        }
    #SeeMore h2 {
        font-size:100px
        }
    #SeeMore img {
        width:0.72em;
        height:0.72em;
        }
---



# developing with arcgis online 
[Nils Rydh](http://twitter.com/pilsna) 

## ![](pictures/arcgis-devices-large.png) 
{:.cover .w}
<!-- photo from developers.arcgis.com -->

## goal
1. arcgis online knowledge exchange: I teach you, you teach me
2. hands-on result on github that can be shown to the other offices
3. solve some real problem

## real problems 
- data analysis
- visualization
- routing - to be qualified

## github
- version control system (git)
//TODO: install github for windows or git 

## ![](pictures/esri-leaflet.png)
{:.cover .w}

## not just the code
- issue tracking
- wiki
- publishing: maps & web content

## [geojson](https://github.com/Neogeografen/beachnumbers/blob/master/beachnumber.geojson) 

## gists
Gist - a simple way of sharing snippets
//TODO: create a gist and add some geojson or other content

## publish html
Bl.ocks.org 

## [http://github.com/esri](http://github.com/esri) 
![](pictures/esri-github.png)

//TODO: clone a project on github and have a look at it 

## **mobile first**

## The old approach 
- ... Check the user agent  
- ... Redirect to a mobile view 
- ... Example: [matas](http://matas.dk), AGO template

## The new approach 
- Fluid/responsive layout that is based on size relative to the viewport. 
- (definition of viewport) 
- [developers.arcgis.com](http://developers.arcgis.com)

## html5
    <!DOCTYPE html>
        <html>
        <head>
            <meta charset="utf-8">
            <meta name="viewport" content="initial-scale=1, 
                  maximum-scale=1,user-scalable=no">
        </head>
        <body></body>
    </html>


## div vs table
- [learnlayout.com](http://learnlayout.com/)
- Quick demo with live reload
//TODO create a simple layout

## responsive design
Pixel based vs relative layout
//TODO: Extend the previous layout with some viewport specific elements
//TODO: extend the layout, make it responsive

## responsive frameworks

## twitter bootstrap

## zurb foundation

## media queries
breakpoints
//TODO: extend the layout with a few media queries

## webmaps and web apps
Webmaps are hosted on ago
Web apps are hosted on ago or elsewhere 

## **feature services**

## Ways to create a service
1. From ArcGIS desktop 
2. Uploading csv/shp
3. Web interface to create an empty service
4. Rest api
5. Use existing feature service

## how to create a template
- Boilerplate on github
- simple template I've created
- swipe template
- story map template
//TODO: download a template from AGO or github, make som changes, run
//TODO: create a template from scratch
// Titanic storymap http://storymaps.esri.com/stories/titanic/

## template configuration

## [**authentication**](https://developers.arcgis.com/en/authentication/index.html) 
//TODO: setup a template with appid authentication for anonymous access

## analysis services
Find nearest bar
//DEMO: nearestbar

## esri-leaflet
github project
hat project visualization
//DEMO: hat-cluster

## routing

## **coming up** 

## **geoevent processor**

## **geotrigger**
- in beta now
- [docs](https://developers.arcgis.com/en/geotrigger-service/)
- [code](https://github.com/search?q=%40Esri+geotriggers)
