# plotly_pyodide_dashboard

Imagine if everyone could share plotting information using dictionary notation, one could use any plotting library (Frontend) regardless of the programming language (Backend) that the data was processed in. This Dashboard uses dictionaries in Python or JavaScript to plot figures in any plotting library in the browser (Plotly, Danfo, etc).

This dashboard is unique because it uses a string-to-dictionary function (convert_dictionarylikestring_to_dictionary) that can transform dictionary strings into dictionary objects, more robustly than JSON.parse. JSON.parse requires that keys are surrounded by double quotes, thus causing conflicts with dictionary importation from other backend frameworks. Some backend programming languages use single quote, double quote, or no quotes thus causing conflicts when using JSON.parse. The convert_dictionarylikestring_to_dictionary function uses simple JavaScript parsing to transform any dictionary-like string, in the form of {key0: [], key1: []}, to a JavaScript object regardless of specific quotes around the key. 

[Latest Working Version] https://CodeSolutions2.github.io/plotly_pyodide_dashboard/index11.html


## Upwork
[Available for purchase on Upwork](https://www.upwork.com/services/product/development-it-frontend-js-dashboard-with-python-js-backend-dictionary-string-organization-1783176512136783700)
