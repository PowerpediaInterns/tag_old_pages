# tag_old_pages
Iterates through a wiki looking for pages that have not been edited in a specified amount of time and tags them with a template.

## Class variables for customization
### TEMPLATE
The template that will be used to tag pages (e.g `{{Update Needed}}`).

### AGE_CAP
A timedelta object, will be used to determine the maximum amount of time a page can be unedited before being tagged.\
https://docs.python.org/3/library/datetime.html#timedelta-objects for further details on working with timedelta objects.
