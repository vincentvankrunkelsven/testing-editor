---
title: R course
video_link: >-
  https://videos.datacamp.com/transcoded/1796_intro-stats-eda/v1/hls-ch0_0.master.m3u8
key: 9768ba199c69d74ed4428ad9a98d6007

--- type:TitleSlide
## Cool stuff

*** =lower_third
name: Andrew Bray
title: Assistant professor Statistics, Reed College

--- type:TwoColumns
## Testing stuff


*** =part1
What's this {{2}}

It's a cool thing {{1}}

*** =part2
![Elephant](https://s3-us-west-1.amazonaws.com/powr/defaults/image-slider2.jpg) {{3}}

*** =script
This is a tes

--- type:TwoRowsTwoColumns key:a8b4b41a6d
## Getting the data

*** =part1
- This is an example {{1}}
- Of a list {{2}}
 - Nested {{2}}
- Nesting is stupid {{6}}

*** =part2
```{r}
# Code looks like this
function(test) {
    return("test");
}
 ``` {{4}}

*** =part3
Watch out for this notification: {{6}}

![notification](http://s3.amazonaws.com/assets.datacamp.com/development/course_1540/datasets/editor_red_notification.png) {{6}}

*** =part4
Some **general** markdown can be on _this_ side. `test_function` to test this. {{5}}

*** =script
whaaat

--- type:TwoRows key:4c87db0f69
## Filtering the data

*** =part1
- Use functional programming {{1}}
- With `apply` {{2}}
 - _Functional_ because it expects a function {{3}}

*** =part2
```
>  # Load package
> library(openintro)

> # Load data
> data(hsb2)
 ``` {{4}}

*** =script
whaaat

--- type:FullSlide key:e2a4c8cfc9
## Slideception

*** =part1

This is a **joke** which references the movie _Inception_ {{1}}

![Slideception](http://s3.amazonaws.com/assets.datacamp.com/development/course_1540/datasets/Screen Shot 2017-01-04 at 17.51.06.png)

--- type:FullSlide key:152efdb06b
## Output

*** =part1
```{r} 
# View the structure of your data
> str(hsb2)
'data.frame': 200 obs. of  11 variables:
 $ id     : int  70 121 86 141 172 113 50 11 84 48 ...
 $ gender : chr  "male" "female" "male" "male" ...
 $ race   : chr  "white" "white" "white" "white" ...
 $ ses    : Factor w/ 3 levels "low","middle",..: 1 2 3 3 2 2 2 2 2 2 ...
 $ schtyp : Factor w/ 2 levels "public","private": 1 1 1 1 1 1 1 1 1 1 ...
 $ read   : int  57 68 44 63 47 44 50 34 63 57 ...
 $ write  : int  52 59 33 44 52 52 59 46 57 55 ...
 $ math   : int  41 53 54 47 57 51 42 45 54 52 ...
 $ science: int  47 63 58 53 53 63 53 39 58 50 ...
 $ socst  : int  57 61 31 56 61 61 61 36 51 51 ...
``` {{1}}

--- type:FullSlide key:376b472fe8
## Tables

*** =part1

| id  |  gender | race  |  ... | socst |
|-----|---------|-------|------|-------|
| 70  | male    | white |  ... | 57    |
| 121 | female  | white |  ... | 61    |
| 86  | male    | white |  ... | 31    |
| ... | ...     | ...   |  ... | ...   |
| 137 | female  | white |  ... | 61    |

This is the best _table_ ever **~~not~~** {{1}}

--- type:FullSlide key:c8df272b9a 
## Formulas

*** =part1
The **formula** for this is $n \rightarrow \infty$

$$\frac{1}{n}\sum\_{i=1}^{n} x\_{i}^{2} + y\_{i}^{2}$$ {{2}}

$$\begin{matrix} a & b & c \\\ d & e & f \\\ g & h & i \end{matrix}$$ {{3}}

### Get ready for the formula

--- type: TwoRows key:52aa2eae47
## Row slide

*** =part1
First time {{1}}

__This is something very cool__ {{2}}

*** =part2
We see a row slide {{2}}

```
# Show this first
for (i in 1..10) { print('cool') }
``` {{1}}

--- type:FinalSlide key:97866310d6
# Let's practice
