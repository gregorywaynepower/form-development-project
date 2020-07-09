# Private Web Form Project

## Table of Contents

- [Private Web Form Project](#private-web-form-project)
  - [Table of Contents](#table-of-contents)
    - [Problem](#problem)
  - [Solution](#solution)
  - [Obstacles to Overcome](#obstacles-to-overcome)

### Problem

We need to have a more elegant solution that can have field technicians do less data entry and be able to scale our input of data. Plus we strongly dislike dealing with PDFs.

## Solution

We propose that we build a web form that takes user input and puts it into an easily accessible data format that can **either** be accessed as CSV, JSON, or other easily-managed format for entry into any of our data-warehousing entry-points.

We can make this modular in the future by using [React.js](https://reactjs.org/) and creating sections as compontents.

## Obstacles to Overcome

- Needs to queue data for submission when offline.
  - Research Notes to Further Reading:
    - [Offline Forms Article](https://mxb.dev/blog/offline-forms/)
    - [Mozilla Docs on Service Worker API](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)
    - [Offline Posts with PWAs](https://medium.com/web-on-the-edge/offline-posts-with-progressive-web-apps-fc2dc4ad895)
