# Swift Docker

A proof of concept to create a multi plattform docker image for the swift nightly releases (Swift 5.6).
Based on the official Swift docker image at https://github.com/apple/swift-docker/blob/main/nightly-main/ubuntu/20.04/Dockerfile

## Usage

You can use this [multi-CPU architecture docker image](https://docs.docker.com/desktop/multi-arch/) as follows:
```
FROM ghcr.io/apodini/swift:nightly
```
The docker images is based on `ubuntu:20.04` and offeres the following architectures: `linux/arm64` & `linux/amd64` and therefore can be used on x86_64 and aarch64 architectures.

## Contributing
Contributions to this project are welcome. Please make sure to read the [contribution guidelines](https://github.com/Apodini/.github/blob/main/CONTRIBUTING.md) and the [contributor covenant code of conduct](https://github.com/Apodini/.github/blob/main/CODE_OF_CONDUCT.md) first.

## License
This project is licensed under the MIT License. See [License](https://github.com/Apodini/swift-docker/blob/develop/LICENSE) for more information.
