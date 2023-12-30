<h1 align="center">Welcome to Dummy Hugo Site - Simple 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.1.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/fabien-tran/dummy-hugo-site-simple/blob/main/README.md" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/fabien-tran/dummy-hugo-site-simple/blob/main/LICENSE" target="_blank">
    <img alt="License: MIT Licence" src="https://img.shields.io/badge/License-MIT Licence-yellow.svg" />
  </a>
</p>

> Dummy site used to test your hugo modules and themes. 
> 
> It contains a home page, a section named "posts" with a few bundle pages and a short set of tags.
>
> Feel free to use it to try out your modules and themes.

### 🏠 [Homepage](https://github.com/fabien-tran)

### ✨ [Demo](https://fabien-tran.github.io/dummy-hugo-site-simple/)


## Prerequisites

Hugo
```sh
apt install hugo
```

Go
```sh
apt install golang-go
```

Git LFS
```
git lfs install
```

## Install

Clone the repository:
```sh
git clone https://github.com/fabien-tran/dummy-hugo-site-simple.git
```

## Usage

Add your theme in config/_default/modules.yaml to import it as a module:
```yaml
imports: 
  - path: github.com/<user>/<repo> 
```

Exemple:
```yaml
imports: 
  - path: github.com/hugoinaction/Eclectic
```


## Run tests

```sh
hugo server -D
```

## Author

👤 **Fabien Tran**

* Website: https://fabien-tran.github.io
* Github: [@fabien-tran](https://github.com/fabien-tran)
* LinkedIn: [@Fabien Tran](https://www.linkedin.com/in/fabien-tran-van-hung/)

## Show your support

Give a ⭐️ if this project helped you!


## 📝 License

Copyright © 2023 [Fabien Tran](https://github.com/fabien-tran).<br />
This project is [MIT Licence](LICENSE) licensed.

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_