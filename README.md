# Web Application: EasySplit
#### A Web Application for Sharing Expenses Easily

Ziyu Tang, Xinlan Wu

## Introduction

EasySplit is an web app built with Python.

It can help quick calculate the result of bill splitting, demonstrate the visualizations of spending (ranking of individual spending, proportion of total/individual spending by categroy), and allow download the original table to save records for personalized use.

## Table of Contents

1. [Installation and Usage](#installation-and-usage)
2. [App Instruction](#App-Instruction)
3. [App Demo](#App-Demo)

## <a name="installation-and-usage"></a>Installation and Usage

Install pytest to test all functions of the object-oriented program:

```
! pip install pytest
```

To run pytest at Jupyter successfully, please install ipytest as well:

```
! install ipytest
```


Install dash to run the codes of application:

```
! install dash
```

## <a name="App-Instruction"></a>App Instruction

- Object-Oriented Program

The **Class BillSplit** contains all algorithms needed for the computation, including creating a dataframe according to the inputs, adding records, developing the balance sheet, splliting solution, and visualizations.

- pytest

All algorithms are tested via pytest, and all of them pass the test.

- App

The app contains two parts: **layout** and **callbacks**.

For the **layout**, it has input groups of expenses details (all participants, payer, amount, activity category, activiti participants), expenses details demonstrated via a table, and three tabs showing the results, including splitting solution, expenses summary, and individual summary.

For the **callbacks**, different buttons serve for different functions. 

Users can add participant's name by clicking **Sumbit**, and the options of payer and activity participants will bbe updated accordingly. By clicking **Add Expenses Record** after inputting each expenses record, users can see the expenses detail is updated in the table on the right simultaneously. Users can download the table by clicking **Download Table**, and get the splitting solution by clicking **Get Split Result**. The solution and visualizations are demonstrated from Tab 1 to Tab three with their names. Especially, for the tab **Individual Expenses Summary**, users can investigate different individual's plot by choosing the names from the dropdown.


## <a name="App-Demo"></a>App Demo

For detailed instruction about how to use this app, please watch the video [![How To Use EasySplit For A Better Expenses Sharing Experience](https://camius.com/wp-content/uploads/sites/4/2016/01/Start-live-demo.png)](https://drive.google.com/file/d/19unBmGrZ_abt7Oydl7NwW3IoBKU5bdGW/view?usp=sharing)
