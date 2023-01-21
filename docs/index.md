# Getting Started

Full code on [github](https://github.com/ahmednafies/sanic_camelcase_middleware).

## Install
    pip install sanic_camelcase_middelware

## Dependencies
* [pyhumps](https://pypi.org/project/pyhumps/)
* [sanic](https://pypi.org/project/sanic/)

## Example
    from sanic import Sanic
    from sanic_camelcase_middleware import Camelize

    app = Sanic(__name__)
    Camelize(app)