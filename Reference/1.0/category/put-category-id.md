<!--
@title Update a category
@author Moltin Ltd
@description Updates a category with the given ID
@order 2.2

@sidebar 1
@family Category
@rate No
@auth Yes
@format JSON
@http PUT
@version beta
-->
This call edits a category with a given ID. There are no minumum required parameters and only those differing from current values will be updated, as such you can pass all or one of the fields and there will be no difference.


#### Resource URL
PUT [{{ api_url }}category/:id]({{ api_url }}category/:id)


#### Parameters
Key | Type | Description
--- | ---- | -----------
title*optional* | String | The Title of the category, must be unique
slug*optional* | String | The Slug/URI of the category, must be unique
parent*optional* | Integer | The Parent category ID of the category, can be null
status*optional* | Choice (1 or 0) | Is the product Live or a Draft
description*optional* | String | The Description of the product

<!--code-->
#### Example Successful Response
``` json
{
  "status": true,
  "result": {
    "id": "60",
    "parent": null,
    "title": "I have just updated my title, isn't that great!",
    "slug": "featured",
    "status": {
      "key": "1",
      "value": "Live"
    },
    "description": "Featured products",
    "images": []
  }
}
```


### Example Failed Response
``` json
{
    "status": false,
    "errors": [
        "Slug must be unique",
        "Description is required"
    ]
}
```
<!--/code-->