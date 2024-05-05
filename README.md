# EX10 [PROJECT] Sentimental Analysis on Any Dataset Using Rapidminer
### DATE: 06-05-2024
### NAME: POOJA A
### REGISTER NO.: 212222240072
## AIM: To create a project for Sentimental Analysis on Any Dataset a Using Rapidminer
## Description: 
<div align = "justify">

### Procedure:
1) ***Import Excel data***
    <p>a. Drag the "Read Excel" operator from the IO folder onto the process canvas.
    <p>b. Double-click on the operator to open its configuration panel.
    <p>c. Specify the path to the Excel file you want to analyze.
    <p>d. Configure options such as sheet selection, header inclusion, etc.
    <p>e. Click on the "Run" button to execute the operator and import the Excel data.
2) ***Perform sentiment analysis with Generate Attributes operator***
    <p>a. Drag the "Generate Attributes" operator from the Operators panel onto the canvas.
    <p>b. Connect the output of the "Extract Sentiment" operator to the input of the "Generate Attributes" operator.
    <p>c. Double-click on the "Generate Attributes" operator to configure it.
    <p>d. Specify a name for the new sentiment attribute you want to generate (e.g., "Sentiment").
    <p>e. Choose the sentiment analysis algorithm, "VADER."
    <p>f. Click on the "Run" button to perform sentiment analysis on the Excel data and generate the sentiment attribute.
3) ***Interpret and export the results***
    <p>a. Analyze the sentiment analysis results from the generated visualizations.
    <p>b. If desired, drag the "Write Excel" operator onto the canvas to export the sentiment analysis results to a new Excel file.
    <p>c. Connect the output of the visualization operator(s) to the input of the "Write Excel" operator.
    <p>d. Configure the file path and other settings for the Excel export.
    <p>e. Click on the "Run" button to export the sentiment analysis results to a new Excel file.

### Output:
![327061786-52a7a5f5-3e43-4bb3-b063-92d5e092cced](https://github.com/poojaanbu0/WDM_EXP10/assets/119390329/d5076664-00b0-44e5-8305-d82c1353ec52)

![327061800-dfcf22bb-7628-45c8-91ab-5c9323f55f86](https://github.com/poojaanbu0/WDM_EXP10/assets/119390329/fa90e413-dbc5-45a9-8e49-2ead377dde88)

![327061825-41ed1365-e513-4729-93b2-b57c24c6cc2f](https://github.com/poojaanbu0/WDM_EXP10/assets/119390329/8f3e6c66-46a2-48e9-8a45-cf18690865f1)


### Result:
Thus sentimental analysis for twitter data using Rapidminer is done successfully.
