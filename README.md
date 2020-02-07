# REGEXER

Allows you to regex post fields on any post types.

Uses `preg_replace()` on a post_type / post_field combination. 

You can select preview or LIVE modes to test your regex before you apply it. 

Within the LIVE mode you can either specify a single post ID or leave it optionally blank to apply the regex to ALL posts of that post type.


## Regexes used:

1. `/\? \<a href.*/s`

1. `/\<p\>\? \<a.*/s`

1. `/\?ALL PARKOUR TUTORIALS.*/s`

1. `/#londonparkour.*/`