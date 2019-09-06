# Modificar-header-wordpress

```php
function changeHeaders($headers)
{
    $headers['Content-Type'] = 'application/json; charset=utf-8';

    return $headers;     
}
add_filter('wp_headers', 'changeHeaders');
```
