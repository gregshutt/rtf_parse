# RtfParse
A ruby miodule wrapping the GNU copmmand-line utility unrtf

## Dependencies
- [unrtf](https://www.gnu.org/software/unrtf/)
- [Open4](https://github.com/ahoward/open4)

##
```ruby
require 'path/to/rtf_parse.rb'
```

```ruby
RtfParse.to_text(rtf_text_or_file_path)
```

```ruby
RtfParse.to_html(rtf_text_or_file_path)
```

To use a custom config file:

```ruby
RtfParse.custom_parse(rtf_text_or_file_path,
  config_path: 'path/to/config/files/',
  tags_file: 'custom_config_file_name'
)
```
