# wp-parser-json
A WP plugin to create json files with all the functions, hooks, filters, actions and classes (post types posts) from the [WP Parser plugin](https://github.com/WordPress/phpdoc-parser).

The files created are:
* functions.json
* hooks.json
* actions.json
* filters.json
* classes.json
* version.json


The JSON files have this structure (example functions.json)
```json
{
  "version":"4.4",
  "url":"https:\/\/developer.wordpress.org\/reference\/functions",
  "content":[
      {"title":"get_posts","slug":"get_posts"},
      {"title":"get_posts_by_author_sql","slug":"get_posts_by_author_sql"},
      
      {"title":"etc...","slug":"etc..."}
    ]
}
```
