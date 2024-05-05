# Great artists steal
`curl -s https://plugins.hex-rays.com/json_plugin_list.php |jq 'sort_by(.downloads)[] | {name, downloads}'`

