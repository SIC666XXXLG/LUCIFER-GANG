A user is considered active if the user has performed any of the following activities on {% ifversion fpt or ghes %}{% data variables.location.product_location %}{% elsif ghae %}{% data variables.product.product_name %}{% elsif ghec %}your enterprise{% endif %}.

- Signing into {% data variables.location.product_location %}
- Creating a repository
- Pushing to a repository
- Being added to a repository
- Changing the visibility of a repository
- Creating an issue or pull request
- Commenting on an issue or pull request
- Closing or reopening an issue or pull request
- Applying a label to an issue or pull request, or removing a label
- Assigning or unassigning an issue or pull request
- Requesting a review of a pull request, or removing a review request
- Creating or editing a comment in a pull request review
- Dismissing a comment in a pull request 
- Synchronizing a pull request
- Commenting on a commit
- Publishing a release
- Pushing to a wiki
- Watching a repository
- Starring a repository
- Deleting a repository
- Accessing resources by using a {% data variables.product.pat_generic %} or SSH key
- Joining an organization

{% ifversion ghes %}
A user will also be considered active if their account has been updated by LDAP.
{% endif %}
