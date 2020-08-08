# Typing Master

I am a slow typer, my max wpm (word per minute) is 63.

So let me break the record with machines.

I wrote web crawlers to type and break the record.

<img src="README.assets/monkey-type.gif" alt="monkey-type" style="zoom: 50%;" />

# Instructions

### Chrome Driver

The web crawler depends uses selenium python library which requires a browser driver, I used chrome driver.
You can download the latest verison here: https://chromedriver.chromium.org/, or you can use the one in this repo if it's compatible with your chrome browser.
I've uploaded the chrome driver for version 84.	

| OS        | Driver                                                   |
| --------- | -------------------------------------------------------- |
| Windows32 | [chromedriver](./chromedrivers/chromedriver_win32.zip)   |
| MacOS     | [chromedriver](./chromedrivers/chromedriver_mac64.zip)   |
| Linux x64 | [chromedriver](./chromedrivers/chromedriver_linux64.zip) |

### Environment

I use Anaconda, this is my environment configuration: [environment.yml](./environment.yml)

Run `conda env create -f environment.yml` to create a conda environment.

However, the main library used is `selenium`, you could also simply install `selenium`.

```bash
conda install -c conda-forge selenium		# install with conda
pip install selenium						# install with pip
```



### Jupyter Notebook

Code are written in Jupyter Notebook, you can convert the notebook into pure python code, but remember to comment out the last line `browser.close()` if you want to see the result, or if you are running the notebook, don't run this line, otherwise browser closes and you will lose the result. 


## Monkey Type

[code](./monkey-type.ipynb)

https://monkey-type.com/

![image-20200808014416218](README.assets/image-20200808014416218.png)

