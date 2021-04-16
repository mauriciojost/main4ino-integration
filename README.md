# README

Choose an arduino project, clone it here, and execute: 

```
ln -s botino-arduino/ arduino-project
```

Then run `integrate` which will read the `commands.list` file looking for:

```
command_to_send_to_device^regexp_to_assert_present_in_device_logs
```

