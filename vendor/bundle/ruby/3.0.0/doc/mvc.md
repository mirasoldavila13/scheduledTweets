## The model view controler (MVC) pattern

Get /about http/1.1
host 127.0.0.1

## routes
matches for the url that is requested
get for "/about"

i see you requested "/about", will give that to the aboutController to handle

## models
database wrapper
user
query for records
wrap individual for records

## view
your response body content
*html
*csv
*pdf
*xml

this is what gets sent back to the browser and displayed
## controller
decide how to process a request and define a purpose