# ISNA_Cronanews

## Context

The dataset contains more than 1500 articles about the status of the spread of the Coronavirus in Iran, published by the Iranian Students News Agency (ISNA). The articles are crawled from the website of the agency ("Corona in Iran" section which contains more than 100 pages) on November 10th, 2021. All of the articles are in Persian language which is the main spoken language in Iran.
Content

Each article is presented as a JSON object containing the following information:

    title: The main title of the article
    body: The body of the corresponding article (containing some lines of text)
    tags: The related tags attached to each article by the author (e.g., the province the news is about)
    category: The main category the article belongs to (e.g., "سلامت" which translates to "Health")
    publish_day: The day of the week on which the article was published
    publish_datetime: The date and time on which the article was published (according to the Solar Hijri calendar, and Tehran time [GMT +3:30])
    link: The link to the original webpage from which the article was obtained

Inspiration

The dataset can be used to gain insights into the spread of the COVID-19 in Iran, which was reported to be one of the most injured countries in the past years due to the unpleasant virus that has become a part of our lives for a while, unfortunately. It can also be used to infer some statistics about the number of people who were infected or passed away because of the virus. Moreover, pre-trained Persian language models can be adapted to the medical domain related to the Coronavirus using this small dataset.
