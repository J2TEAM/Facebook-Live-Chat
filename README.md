# Facebook Live Chat
A jQuery plugin to embed Facebook Live Chat into your website, blog, or forum.

## Screenshot

![Facebook Live Chat](http://i.imgur.com/nr4kKOf.png)

## Example/Usage

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>Facebook Live Chat</title>
    </head>
    <body>
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
        <script src="fb-live-chat.min.js"></script>
        <script>
        fbLiveChat.init({
            sdk_locale: 'en_US',
            facebook_page: 'JunoOkyoBlog', // required
            position: 'right',
            header_text: 'Online Support',
            header_background_color: '#4e69a2',
            show_close_btn: true,
            animation_speed: 400,
            auto_show_delay: 5000
        });
        </script>
    </body>
</html>
```

Or see [example.html](example.html).

## Options

| Key Name                | Value Type     | Default value  |
|-------------------------|----------------|----------------|
| sdk_locale              | String         | en_US          |
| facebook_page           | String         | JunoOkyoBlog   |
| position                | String         | right          |
| header_text             | String         | Online Support |
| header_background_color | String         | #4e69a2        |
| show_close_btn          | Boolean        | true           |
| animation_speed         | Number/String  | 400            |
| auto_show_delay         | Number         | 0              |

**Note:**

- `sdk_locale` is [Locales and Languages Supported by Facebook](https://www.facebook.com/translations/FacebookLocales.xml).
- Only `facebook_page` is required.
- `position` can be "left" or "right".
- `animation_speed` is jQuery duration (slow/400/fast).
- Keep `auto_show_delay` equal to 0 if you don't want to show automatically.
- The unit of `animation_speed` and `auto_show_delay` is millisecond.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Credits

[Juno_okyo](http://junookyo.blogspot.com/) from [J2TeaM](https://github.com/J2TeaM).

## License

This work is licensed under a [MIT LICENSE](LICENSE).
