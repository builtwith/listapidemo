# Introduction
Demo of making calls to the BuiltWith List API - this will spit out a list of all of the domains and page through all of the results.

# Example

* Install nodejs
* Download main.js and package.json into a new folder
* Run the following command in the folder where you placed the files above
```
  npm install
```

* Replace KEY below with your key from https://api.builtwith.com
* From the command line run 

```
  node main.js "KEY=[your key]&TECH=Shopify" 
``` 


# Additional Info

To get the list of domains into a file use the following command 
```
  node main.js "KEY=[your key]&TECH=Shopify" > shopify.tsv
```

When the process is completed shopify.tsv will list all of the results. You can vary the parameters based on the documentation at https://api.builtwith.com/lists-api


# Debug

If you get 'STOPPED BECAUSE OF ERROR' right away put the 'Initial Call:' URL into your browser to see the issue.
