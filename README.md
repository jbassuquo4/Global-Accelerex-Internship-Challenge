# Global-Accelerex-Interns-Challenge
Front End Challenge

## Table of contents

* [Introduction](#introduction)
* [Motivation](#motivation)
* [Style Guide](#style-guide)
* [Screen Shot](#screen-shot)
* [Installing](#installing)
* [Prerequisites](#prerequisites)
 * [Folder Structure](#folder-structure)
 * [Working Routes](#working-routes)
 * [License](#license)
 * [Author](#author)
 * [Acknowledgments](#acknowledgments)
 * [Live Demo](#live-demo)

## Introduction

REST API<br>This is documentation for an endpoint to allow you pull a list for a people and update  the description for a person. 

## Motivation

This is a REST API challenge that will contritube to a great career as `Global Accelerex` expert.

### Style guide

[Airbnb ](https://github.com/airbnb/javascript)(Javascript style guide)


### Screen Shot

![alt](/screenshot.JPG)


## Installing

#### Prerequisites

Ensure you have **NodeJS** installed by entering `node -v` on your terminal
If you don't have **NodeJS** installed go to the [NodeJS Website](http://nodejs.org), and follow the download instructions

To install this app

```
git clone https://github.com/jbassuquo4/Global-Accelerex-Internship-Challenge.git
```

## Folder Structure

```
Global-Accelerex-Internship-Challenge/
Asuquo_Jeremiah/
crown.png
index.html
main.js
style.css
README.md
screenshot.JPG
```


### Working Routes

<table>
<thead>
<tr>
<th>Endpoint</th>
<th>Functionality</th>
</tr>
</thead>
<tbody>
<tr>
<td>GET request to “{BASE_URL}/persons”</td>
<td>Returns a list of people.<br /> N.B: This endpoint is paginated and returns a maximum of 10 items per request. It accepts a query parameter named page which should be an integer greater than 0.
</td>
</tr>
<tr>
<td>POST request to “{BASE_URL}/persons/{personId}”</td>
<td>This endpoint updates the description for a person identified by the parameter personId. This endpoint also accepts a single parameter description in the body of the request.<br />Example request body is:
{
     			"description": "Nice"
}
</td>

<tr>
<td></td>
<td></td>
</tr>
</tbody></table>

## License

This projects is under the MIT LICENSE

## Author

[Jeremiah Asuquo B.](https://github.com/jbassuquo4)

## Acknowledgments

* [Stackoverflow](https://stackoverflow.com)
* [Google Search](https://google.com)
