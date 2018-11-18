---
title: Insert title here
key: 7bcbe1ffa6edd4d64b5ab0bbeefdeeb0

---
## **Case Study: Marketing Analytics**

```yaml
type: "TitleSlide"
key: "b6c2cf86c4"
```

`@lower_third`

name: Luke Pajer
title: Digital Marketing Specialist, Beacon


`@script`
Hello! Welcome to the course.

My name is Luke Pajer and I am a Digital Marketing Specialist at Beacon


---
## **Course Topics**

```yaml
type: "FullSlide"
key: "1f2b4e7734"
center_content: false
```

`@part1`
- **Clean Data Entry:** Data Validations {{1}}
- **Clean Data Aggregation:** Regular Expressions {{2}}
- **Visualize the Clean Data:** Google Charts {{3}}
- **Case Study:** Build a Marketing Analytics Dashboard {{4}}


`@script`
In this course, we will explore how to utilize Google Sheets for Marketing Analytics.

In this first chapter, we will cover how to ensure that data entry into the google sheet is clean and formatted correctly using the Google Sheets built-in tool Data Validations.

Next, we will look to aggregate data by using Regular Expressions to account for slight variations of names that sometimes occur when more than one party is entering data.

Then, will we visualize the data by constructing various charts that Google Sheets has available.

Finally, we will take what we learned from this course and create a Marketing Dashboard that will aid in analysis of Bing and Google Ads Campaign Data.


---
## **Data Validations for Clean Data Entry**

```yaml
type: "FullSlide"
key: "cafa36954d"
```

`@part1`
- **Google Sheets for Clean Data Entry**{{1}}
     - Allows for multiple parties to enter data in real time{{2}}
     - Built-in feature 'Data Validations' for cleaner data entry{{3}}
- **Data Validations**{{4}}
     - Mitigate data entry mistakes{{5}}
     - Apply to a selection of cells{{6}}
     - Rejects erroneous data{{7}}


`@script`
Google Sheets is a great way to allow multiple parties to collaborate on a data set

but, manually entering data almost always leads to a few mistakes.

Luckily, we have Data Validations which

help mitigate data entry mistakes

Are simply rules that you apply to a selection of cells.

and if the input cell does not meet the data validation, then an error is shown in the cell, and can even reject your entry outright.


---
## **Types of Data Validations in Google Sheets**

```yaml
type: "FullSlide"
key: "b4f148479e"
```

`@part1`
![](http://assets.datacamp.com/production/repositories/4074/datasets/5f31c0f906a4806c35f5654d6f0a6214a3db32d7/DataValidations.png)


`@script`
There are many different types of Data Validations, 

seven different types to be exact 

where each one performs a specific validation.


---
## **Data Validations: List from a range and List of items**

```yaml
type: "TwoColumns"
key: "117921cb42"
```

`@part1`
- **List from a range:**{{1}}
     - Input cell must match a value in a range of cells{{2}}
- **List of items: **{{3}}
     - Input cell must match a value from a list of items manually entered{{4}}
- Both lists may show as a dropdown{{5}}

**Works well when:**{{6}}
- There are a small number of options{{7}}


`@part2`
![](http://assets.datacamp.com/production/repositories/4074/datasets/d77beb6456f1f278e9f898b3a079161e6cd3d152/Drops.png)


`@script`
List from a Range and List of Items lets you enter in a list of items to match against the cell's input.  

If the cell does not match any of the items in the list, it will be rejected or show a warning.

The items that the cell must match can be viewed as a dropdown in the cell.

List validations works very well with multiple parties are entering data that have only a small number of options, such as 

days of the week

or Marketing Campaign Types


---
## **Data Validations: Number and Text**

```yaml
type: "TwoColumns"
key: "e1e18bf2d8"
```

`@part1`
- **Number:** measures if input cell{{1}}
     - is between, <, >, =, etc...{{2}}
- **Text: **measures if input cell{{3}}
     - contains 'xyz'{{4}}
     - Is a valid email address or URL{{5}}

**Works well when:**{{6}}
- There are an infinite number of options{{7}}


`@part2`
![](http://assets.datacamp.com/production/repositories/4074/datasets/a2738a9aa8e29c190ce803f0046616bccf1fe0c5/Number.png)


`@script`
The Number and Text Data Validations measure against a conditions that you set.

The 'Number' Data Validation measures if the input cell is between, greater than, less than, equal to, etc. a condition.

The 'Text' Data Validation measures if the input cell 

contains some string 

or it can even make sure that the input cell is a valid email address or URL

Both the number and text data validations work well when there are an infinite number of options for the cell, such as 

cost data 

or email addresses.


---
## **Data Validations: Date**

```yaml
type: "TwoColumns"
key: "f0a5595fbb"
```

`@part1`
- **Date:** checks if the input cell{{1}}
     - Is a valid date{{2}}
     - Is between certain dates{{3}}
     - Is before, after, or equal to a certain date{{4}}

**Works well when:**{{5}}
- All of the dates must have the exact same formatting{{6}}


`@part2`
![](http://assets.datacamp.com/production/repositories/4074/datasets/0bc212c8523d767c59d406eeadafd624c89668d1/Date.png)


`@script`
The Date Data Validation checks if the input cell

is a valid date,

is between two dates,

or is before, after, or equal to a certain date

This works well when all the dates must have the exact same formatting.  

such as the year-month-day format.


---
## **Data Validations: Checkbox**

```yaml
type: "TwoColumns"
key: "3c403607ec"
```

`@part1`
- **Checkbox:**{{1}}
     - Creates a checkbox in each cell in the selection{{2}}
     - Default cell values are True/False{{3}}
     - Can customize cell values, such as Active/Inactive{{4}}

**Works well when:**{{5}}
- there are only two possible answers{{6}}


`@part2`
![](http://assets.datacamp.com/production/repositories/4074/datasets/1fc05e996a1cd458e92443dd2cf3cf844e6fcf55/Check.png)


`@script`
The last data validation we will cover is the checkbox.

A checkbox is inserted into each of the cells in the data validation selection.

The default values are True for checked boxes and false for unchecked boxes.

You can customize the values for the boxes, 

such as, having Active for the checked boxes and Inactive for the unchecked boxes

The Checkbox data validation works well when there are only two possible answers

such as if a marketing campaign is currently running or not.


---
## Let's Practice!

```yaml
type: "FinalSlide"
key: "43dc4d6108"
```

`@script`
This has been a ton of information I have thrown at you, s

o why dont we test our understanding with a few multiple choice questions before we get into the specifics of each Data Validation type.

Good luck, stay positive, 

I’ll see you at the beginning of the next lesson!

