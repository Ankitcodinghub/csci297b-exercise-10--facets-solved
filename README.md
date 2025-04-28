# csci297b-exercise-10--facets-solved
**TO GET THIS SOLUTION VISIT:** [CSCI297B Exercise 10- facets Solved](https://www.ankitcodinghub.com/product/csci297b-exercise-10-facets-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116990&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI297B Exercise 10- facets Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
For this project, use the tidyverse library, which includes the mpg dataset.

For this project, you will turn in a single R markdown file, called exercise10.Rmd

1. What happens if you facet on a continuous variable?

2. What do the empty cells in plot with facet_grid(drv ~ cyl) mean? Run the following code. How do they relate to the resulting plot?

ggplot(mpg) + geom_point(aes(x = drv, y = cyl))

3. What plots does the following code make? What does . do?

ggplot(mpg) +

geom_point(aes(x = displ, y = hwy)) + facet_grid(drv ~ .)

ggplot(mpg) +

geom_point(aes(x = displ, y = hwy)) + facet_grid(. ~ cyl)

4. Take the first faceted plot in this section:

ggplot(mpg) +

geom_point(aes(x = displ, y = hwy)) + facet_wrap(~ class, nrow = 2)

What are the advantages to using faceting instead of the color aesthetic? What are the disadvantages? How might the balance change if you had a larger dataset?

5. Read ?facet_wrap. What does nrow do? What does ncol do? What other options control the layout of the individual panels? Why doesn’t facet_grid() have nrow and ncol arguments?

1

6. Which of the following plots makes it easier to compare engine size (displ) across carswith different drive trains? What does this say about when to place a faceting variable across rows or columns?

ggplot(mpg, aes(x = displ)) +

geom_histogram() + facet_grid(drv ~ .)

ggplot(mpg, aes(x = displ)) +

geom_histogram() + facet_grid(. ~ drv)

7. Recreate the following plot using facet_wrap() instead of facet_grid(). How do the positions of the facet labels change?

ggplot(mpg) +

geom_point(aes(x = displ, y = hwy)) + facet_grid(drv ~ .)

2
