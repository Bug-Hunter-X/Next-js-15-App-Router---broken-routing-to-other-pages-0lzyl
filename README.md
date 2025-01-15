# Next.js 15 App Router Routing Issue

This repository demonstrates a routing issue encountered in a Next.js 15 App Router application.

## Problem Description

When navigating from the home page to the about page using a Next.js Link component, the application throws a 404 error. The `about` page fails to render correctly.

## Steps to Reproduce

1. Clone this repository.
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev`
4. Navigate to `http://localhost:3000`
5. Click on the link to go to the 'About' page.

Expected Result: The about page should render successfully.
Actual Result: A 404 error is thrown.

## Solution

The issue lies in the file structure and missing `app` directory.  The provided solution correctly structures the files within the `app` directory.  In the `app` directory, this example uses the `page` file to denote pages.  Then, the page is accessible via a route. 
