# Application server

### Concepts
*For this project, we expect you to look at these concepts:*
- [Web Server](https://intranet.alxswe.com/concepts/17)
- [Server](https://intranet.alxswe.com/concepts/67)
- [Web stack debugging](https://intranet.alxswe.com/concepts/68)

![App server img](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2018/9/c7d1ed0a2e10d1b4e9b3.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230309%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230309T144321Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=3aa62898cdc6056ac681b6230cb3428b2cc7aef420c544c7f507c8cb0c4b167f)

## Background Context
Your web infrastructure is already serving web pages via `Nginx` that you installed in your [first web stack project](https://intranet.alxswe.com/rltoken/95oRNZ-zRGwLxtWECJqsWA). While a web server can also serve dynamic content, this task is usually given to an application server. In this project you will add this piece to your infrastructure, plug it to your `Nginx` and make is serve your Airbnb clone project.

## Resources
**Read or watch:**
- [Application server vs web server](https://intranet.alxswe.com/rltoken/B9fOBzIxX_t1289WAuRzJw)
- [Running Gunicorn](https://intranet.alxswe.com/rltoken/2LF1j7xKJGYaUtD1HKgUeQ)
- [Be careful with the way Flask manages slash](https://intranet.alxswe.com/rltoken/lEg0zpkkDcLtdl3VD4ACRQ) in [route](https://intranet.alxswe.com/rltoken/Zn8fYk-U9YRm7Z5Coqqb0g) - `strict_slashes`
- [Upstart documentation](https://intranet.alxswe.com/rltoken/mcEsKqFsjJA3tHAjiMknaw)
