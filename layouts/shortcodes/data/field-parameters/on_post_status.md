## on_post_status

Lock the field value when your post is in a certain post status. A range of post statuses can be used by separating them with two hyphens (–).

Only used for Post data.
`on_post_status` is now part of the conditions array: `post_status_hide`, `post_status_value`

* Input:  parameters

Examples:

```
'on_post_status' => array(
	'value' => 'publish'
)
```

```
'on_post_status' => array(
	'value' => 'repair--closed'
)
```
