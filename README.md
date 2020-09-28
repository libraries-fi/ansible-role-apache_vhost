# Ansible Role: apache_vhost

Create Apache site configuration files.

In `templates/wordpress_vhost.j2`, the variable `wordfence_waf_path` should point to `wordfence-waf.php` file which can be used to enable Wordfence Extended Protection. By default, the variable is undefined and is not used. If the variable is defined, the target file must exist or the page will be blank.

## License

MIT
