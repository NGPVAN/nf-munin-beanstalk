# Beanstalk Tube Monitoringu

By default when enabled, this tool will create a graph of the aggregate values
of the current ready, urgent, reserved, delayed, and buried jobs in all the
tubes.

By symlinking or renaming the file, it will look at a specific tube:

```bash
# Monitor the FooBar tube
ln -s beanstalk beanstalk_tube_FooBar
```

