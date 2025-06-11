# No Cannabis Incubator

A static site powered by [Hugo](https://gohugo.io/) using the [Paige theme](https://themes.gohugo.io/themes/paige/).

## Prerequisites

- [Go](https://golang.org/dl/) (for installing Hugo)
- [Git](https://git-scm.com/)

## Installation

### 1. Install Hugo

Follow the [official Hugo installation guide](https://gohugo.io/getting-started/installing/):

```sh
brew install hugo
# or for other platforms, see the Hugo docs
```

### 2. Clone the Repository

```sh
git clone https://github.com/your-username/no-cannabis-incubator.git
cd no-cannabis-incubator
```

### 3. Add the Paige Theme

```sh
git submodule add https://github.com/willfaught/paige.git themes/paige
```

Or download it manually from the [Paige theme page](https://themes.gohugo.io/themes/paige/).

### 4. Configure the Theme

In your `config.toml` (or `config.yaml`), set:

```toml
theme = "paige"
```

## Running the Site Locally

```sh
hugo server
```

Visit [http://localhost:1313](http://localhost:1313) in your browser.

## Resources

- [Hugo Documentation](https://gohugo.io/documentation/)
- [Paige Theme Documentation](https://github.com/willfaught/paige)
- [Hugo Themes](https://themes.gohugo.io/)
