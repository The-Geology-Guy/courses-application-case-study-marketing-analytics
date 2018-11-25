---
title: Insert title here
key: caecd8575ff0f31d5a6d891e710fd967

---
## Add a Dynamic Pie Chart for Budget Analysis

```yaml
type: "TitleSlide"
key: "6b571dd03b"
```

`@lower_third`

name: Luke Pajer
title: Digital Marketing Specialist, Beacon


`@script`
Now that we have created our dashboard, let us take the dashboard a step further by modifying the pie chart to be dynamic.

First, let us put on our ‘Marketing Director’ caps and think about how a dynamic pie chart would aid in determining each campaign’s ad group budget based on the previous year.


---
## Previous Year Ad Group Budget Analysis

```yaml
type: "FullSlide"
key: "3605481bcb"
```

`@part1`
![](http://assets.datacamp.com/production/repositories/4074/datasets/b5b4481d8f1af01dbcce848d5b4fefe33ade5b7c/DataSetPreview.png)


`@script`
Recall the data set we have been using throughout this chapter.

Sure, a Marketing Director could just sift through the table and make side calculations to get relative costs for each campaign ad group.

But… a pie chart will provide insight into how much each Ad Group is contributing to the overall campaign cost.

With the percent makeup of total cost for each Campaign, a marketing director should be able to properly set the budget for each Ad Group at the beginning of the year.


---
## Dynamic Pie Chart

```yaml
type: "TwoColumns"
key: "d8643db7fe"
```

`@part1`
- **Source Dropdown (Top)** to filter between Google, Bing, or All{{1}}
- **Campaign Dropdown (Bottom)** to filter between the Paid Search Campaigns{{2}}
- **Pie Chart** to visualize the Ad Groups associated with the selected Source and Campaign{{3}}


`@part2`
![](http://assets.datacamp.com/production/repositories/4074/datasets/4d0607d77d0dd8a851e157cb78b9f1b504a00a1b/pieAdGroup.png){{1}}


`@script`
Our goal for this Dynamic Pie chart is to build a

Source Dropdown using Data Validations to filter between Google and Bing Paid Search data, or to not filter at all by selecting All Sources.

Then, we will build a Campaign Dropdown using Data Validations to filter between the various Paid Search Campaigns

Finally, we will modify the existing Pie chart to filter for the ad groups associated with the selected Source and Campaign in the dropdowns.

With this setup, a marketing director will be able to accurately measure the percent makeup of the total cost of each campaign’s ad group.

This enables the director to make budget decisions such as the amount of budget needed for the ‘Mug Buyers’ ad group in the ‘Python Brand’ Campaign for Google Paid Search vs Bing Paid Search.


---
## Comparing Ad Group Budgets

```yaml
type: "TwoColumns"
key: "6b9d9222a5"
center_content: false
```

`@part1`
![](http://assets.datacamp.com/production/repositories/4074/datasets/bed7c8923ecfe4599d78c4bd1a615cf366e72f55/pythonBrand.png)


`@part2`
![](http://assets.datacamp.com/production/repositories/4074/datasets/ca73dd6058d82e5a047626ab1fd27d719ae2598f/DataCampBrand.png)


`@script`
Now that we have the dynamic pie chart set up, lets be the acting Marketing manager and set relative budgets for each of the two campaigns.

From the results below, the Python Brand Campaign would need to allocate the most money to the Mug Buyers Ad group, where the DataCamp brand would need the most money allocated to the Sweater Buyers Ad Group.

This may seem like a trivial conclusion, and you would be right.  But it is such an easy conclusion to draw because of the dynamic Pie Chart.
  
What this means is that a marketing director may spend their time improving campaigns in other areas rather than spending the time trying to sift through a spreadsheet to set budgets at a daily, weekly, monthly, or yearly rate (like we saw in this exercise).


---
## Let's get to work!

```yaml
type: "FinalSlide"
key: "0a367a233c"
```

`@script`
Now that you have an idea of how to put a Dynamic Pie Chart together, why dont you go give it a shot at building your very own!

Good Luck, Stay Positive.

I will see you after you complete this lesson!

