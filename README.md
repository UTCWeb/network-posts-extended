# network-posts-extended
This is the plugin that is no longer supported that Marketing needs for the blog.utc.edu homepage. 

This plugin was originally found here: https://wordpress.org/plugins/network-posts-extended/, but is no longer supported. Downloads of this plugin were closed as of 5/19/2025.

Marketing uses this plugin for the homepage of the blog.utc.edu in order to show teasers from the most popular blogs across the multisite.

This repo includes updates on deprecations as follows:

- Deprecated: Using ${var} in strings is deprecated, use {$var} instead in /app/web/app/plugins/network-posts-extended/network-posts-extended.php on line 821 >>> `${prefix}blogs` changed to `{$prefix}blogs`
- Deprecated: Using ${var} in strings is deprecated, use {$var} instead in /app/web/app/plugins/network-posts-extended/components/db/NetsPostsQuery.php on line 323 >>> `${posts_table} ${join_tables}` changed to `{$posts_table} {$join_tables}`
- Deprecated: Using ${var} in strings is deprecated, use {$var} instead in /app/web/app/plugins/network-posts-extended/components/NetsPostsTemplateRenderer.php on line 44 >>> `{$key}` changed to `{$key}`

License GPL-3.0 license 
