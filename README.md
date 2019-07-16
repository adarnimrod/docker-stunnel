# Stunnel Docker image

> Dockerized stunnel

## Usage example

```
docker run -e 'HOST=foo.example.com' -e 'PORT=443' -p '443:443' adarnimrod/stunnel
```

## Environment variables

Name | Description | Default value
--- | --- | ---
`DEBUG` | Debugging level | `5` (notice)
`PORT` | Port to connect and forward
`CLIENT` | Client mode | `yes`
`HOST` | Remote host

## License

This software is licensed under the MIT license (see `LICENSE.txt`).

## Author Information

Nimrod Adar, [contact me](mailto:nimrod@shore.co.il) or visit my [website](
https://www.shore.co.il/). Patches are welcome via [`git send-email`](
http://git-scm.com/book/en/v2/Git-Commands-Email). The repository is located
at: <https://www.shore.co.il/git/>.
