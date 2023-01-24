<a name="readme-top"></a>

# Table of Contents

- [About the Project](#about-project)
  - [Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
- [Getting Started](#getting-started)
  - [Setup](#setup)
  - [Usage](#usage)
- [Authors](#authors)
- [Show your support](#support)

# [Students comment crawler] <a name="about-project"></a>
This project is used to crawl student comments from many student websites.

## Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

This project uses the Selenium package for crawling. Chrome browser is also used.

### Key Features <a name="key-features"></a>

- **[Easy usage]**
- **[No need for user interaction]**
- **[output is a CSV file]**

## Getting Started <a name="getting-started"></a>

### Prerequisites

In order to run this project you need:

```sh
 !pip install selenium
```

Also, you need a chrome browser and its webdriver.

### Setup

Clone this repository to your desired folder:

```sh
  cd my-folder
  git clone git@github.com:Emad78/students-comment-crawler.git
```


### Usage

To run the project, based on a website that you want to crawl, you should run its code. There are three classes for crawling MehroMah, Gozine2 and Ghalamchi websites.
For Gozine2:

```sh
crawler = Crawler_Gozine2(url)
data = crawler.run()
```

For MehroMah:
```sh
crawler = Crawler_MehroMah()
data = crawler.run()
```

For Ghalamchi:
```sh
crawler = Crawler_Ghalamchi()
data = crawler.run(url)
```
output of run method is a pandas dataframe for all above objects. Crawler Ghalamchi and Crawler_Ghalamchi2 are same but use for different ghalamchi page with different XPath for finding elements


## Authors <a name="authors"></a>

**Author1**

- GitHub: [@Emad78](https://github.com/Emad78)



## Show your support <a name="support"></a>

If you like this project please give us a ⭐

<p align="right">(<a href="#readme-top">back to top</a>)</p>



