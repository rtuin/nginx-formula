# nginx-formula

This formula will install the latest stable version of Nginx from the official repo.

## Compatibility

This formula currently only works on Debian-based systems (Debian, Ubuntu etc).

## Contributing

Pull requests for other OSes and bug fixes are more than welcome.

## Usage

Include "nginx" in your project for the "full stack". Optionally you can select which states you require.
For usage with the Zend Server formula you should use "nginx.light" instead since that package already has its own Nginx installation.

## Configuration

The included pillar.example shows the available options.

## Todo

- Add configuration support (e.g. for modules)
- Add macro for easy vhost generation
- Add optional vhost management suppport
