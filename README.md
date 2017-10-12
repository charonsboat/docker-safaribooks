# drm2/docker-safaribooks

A docker container for converting Safari books to `.epub` and `.mobi` formats (for use with Kindle and other e-readers).

## usage

Using this container is pretty simple. All you need to do is run the following command (replacing `<user>`, `<pass>`, and `<isbn>` with actual values):

```shell
docker run -v $(pwd)/books:/safaribooks/books --rm -it drm2/safaribooks <user> <pass> <isbn>
```

Your new books will be available in the `books` directory.

**Disclaimer:** This is just an experiment. Use at your own risk. SafariBooksOnline.com terms of use apply.
