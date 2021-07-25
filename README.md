# Remedy Recommender System

## How to
Steps to run:
1. Navigate to directory containing the above code. The directory path should look like `/recommendersys`.
2. You can use(optional) the virtual environment as provided in the source code. To learn how to setup a virtual environment(different for windows and linux/mac), hit [this](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/).
3. Run `pip3 install -r requirements.txt`.
4. Run `python3 main.py`
5. Navigate to your web browser and enter the localhost url with port 8080 and route `/1`: `localhost:8080/1` or `127.0.0.1:8080/1`

As the UI rendering isn't complete yet, input has to be changed manually from the source file. To change the input:
1. Open file test.py
2. Jump to method named results at line 159 and change the value of input array named test_input.
3. Save the file.
4. Refresh the browser tab.

## Datasets Link
1. [Base dataset](https://www.kaggle.com/plarmuseau/sdsort)
2. [New Dataset](https://github.com/sud0lancer/Diagonosis-Precaution-dataset)

## Related thesis-work
This system was used in the following thesis work: 
```
  Author: "Sudhanshu et al."
  Title: "Recommending Next Best Course of Treatment based on similarities of Prognostic markers"
  Year: 2021
```
