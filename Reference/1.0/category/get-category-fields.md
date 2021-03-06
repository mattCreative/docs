This call returns the data required to build a dynamic flows form based on the product creation requirements. It provides all options available for the choice fields as well as those featured in relationships (eg, Categories). It also provides information of field requirements, default values, etc.

#### Resource URL
GET [{{ api_url }}categories/fields]({{ api_url }}categories/fields)

<!--code-->
``` json
{
    "status": true,
    "result": {
        "parent": {
            "slug": "parent",
            "name": "Parent Category",
            "type": "relationship",
            "options": {
                "relates_to": 4
            },
            "required": false,
            "unique": false,
            "locked": true,
            "order": null,
            "instructions": null,
            "available": {
                "959732764679078722": "Uncategorized"
            },
            "value": null
        },
        "slug": {
            "slug": "slug",
            "name": "Slug",
            "type": "slug",
            "options": {
                "parent": "title"
            },
            "required": true,
            "unique": true,
            "locked": true,
            "order": null,
            "instructions": null,
            "value": null
        },
        "status": {
            "slug": "status",
            "name": "Status",
            "type": "choice",
            "options": {
                "choices": [
                    "Draft",
                    "Live"
                ],
                "default": 0
            },
            "required": true,
            "unique": false,
            "locked": true,
            "order": null,
            "instructions": null,
            "value": null
        },
        "title": {
            "slug": "title",
            "name": "Title",
            "type": "string",
            "options": {
                "multilingual": true
            },
            "required": true,
            "unique": false,
            "locked": true,
            "order": null,
            "instructions": null,
            "value": null
        },
        "description": {
            "slug": "description",
            "name": "Description",
            "type": "text",
            "options": {
                "multilingual": true,
                "wysiwyg": false
            },
            "required": true,
            "unique": false,
            "locked": true,
            "order": null,
            "instructions": null,
            "value": null
        }
    }
}
```
<!--/code-->
