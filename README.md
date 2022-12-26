# Data-Visualization-Visualize-Data-with-a-Bar-Chart

Challenge 

Fulfill the below user stories and get all of the tests to pass. Use whichever libraries or APIs you need. Give it your own personal style.

You can use HTML, JavaScript, CSS, and the D3 svg-based visualization library. The tests require axes to be generated using the D3 axis property, which automatically generates ticks along the axis. These ticks are required for passing the D3 tests because their positions are used to determine alignment of graphed elements. You will find information about generating axes at https://github.com/d3/d3/blob/master/API.md#axes-d3-axis. Required (non-virtual) DOM elements are queried on the moment of each test. If you use a frontend framework (like Vue for example), the test results may be inaccurate for dynamic content. We hope to accommodate them eventually, but these frameworks are not currently supported for D3 projects.

User Story #1-3: Chart
A title with a corresponding id="title".
A g element x-axis with a corresponding id="x-axis".
A g element y-axis with a corresponding id="y-axis".

User Story #4: Both axes should contain multiple tick labels, each with a corresponding class="tick".
User Story #5: My chart should have a rect element for each data point with a corresponding class="bar" displaying the data.
User Story #6: Each bar should have the properties data-date and data-gdp containing date and GDP values.

User Story #7-9: Bar elements
Data-date properties should match the order of the provided data.
Data-gdp properties should match the order of the provided data.
Height should accurately represent the data's corresponding GDP.

User Story #10: The data-date attribute and its corresponding bar element should align with the corresponding value on the x-axis.
User Story #11: The data-gdp attribute and its corresponding bar element should align with the corresponding value on the y-axis.

User Story #12: I can mouse over an area and see a tooltip with a corresponding id="tooltip" which displays more information about the area.
User Story #13: My tooltip should have a data-date property that corresponds to the data-date of the active area.

Here is the dataset you will need to complete this project: https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/GDP-data.json

You can build your project by using this CodePen template and clicking Save to create your own pen. Or you can use this CDN link to run the tests in any environment you like: https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js.

Once you're done, submit the URL to your working project with all its tests passing.

CodeSwing
In Visual Studio Code, use CodeSwing to create a Basic CSS HTML and JavaScript template. Use the following steps: 
Launch 
1.	Install the CodeSwing extension and then reload VS Code
Create the swing
1.	Run the CodeSwing: New Swing... command, and select the desired template
2.	Select the Basic: HTML/CSS/JavaScript

