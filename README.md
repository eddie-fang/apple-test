apple-test
==========

To Run: Download, then open up console.html with your favorite browser

Functional widgets:
- time slider on the top
- tabs switching between day/week/month/quarter/year
- tabs switching between units/billings
- X buttons on the filters
- X buttons on the content tags
- clicking between different filters on the left will highlight
- typing into the input text under content and provider, then press enter, will then add a tag
- clicking on the legends in the chart area
- clicking on the column headers in the table area

Assumptions:
- clicking on different filters will highlight
- typing into input text area, then pressing enter, will add a tag

Questions:
- what are the steps for a presentation on this mockup? (could then focus on those steps/what they show)
- why is filters mechanic different than content/provider?
- what happens when you click on the tabs for date, and for display?
- why was the initial design image so blurry?

Notes:
- used jquery, jquery-ui (heavy, but easy to use), highchart for chart, datatable for table
- wrote custom widget for timeline (usually will write own dropdown/slider)
- css classes were used mainly for use, so can transition into production code later
- normal css classes used, but usually use compass/scss/less
- Usually if missing from the design, I would ask for color codes/font size/font colors/gradient/images
- used div tables, div images
- data was added into the code as is (instead of loaded in), bypassing cross domain issues (just for demo)
- used google images (although if there was a high resolution image required, would use istockphoto/getty images)
- all dash convention for naming