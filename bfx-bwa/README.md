# Synopsis

Image for bwa indexing and alignment.

# Using with [Google Cloud Pipelines API](https://cloud.google.com/genomics/v1alpha2/pipelines)

Example invocation recipe in this Gist:

[https://gist.github.com/allenday/4c17e09de02e57984fcab0d91e042a34](https://gist.github.com/allenday/4c17e09de02e57984fcab0d91e042a34)

Grab the operation ID string `operations/...` and use it to monitor the job:

[https://gist.github.com/allenday/7480a7752747976dd4b34a9d9a1d0564](https://gist.github.com/allenday/7480a7752747976dd4b34a9d9a1d0564)

Console will block like this until complete:

[https://gist.github.com/allenday/89ee327c777e500b8f8ad517632fccdb](https://gist.github.com/allenday/89ee327c777e500b8f8ad517632fccdb)

Then output will be in `$OUTPUT_PATH`.

Done!
