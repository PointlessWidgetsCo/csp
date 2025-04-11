# Database of Commonwealth Supported Postgraduate Courses in Australia

## Overview
This project aims to provide a comprehensive list of postgraduate courses in Australia that are available as Commonwealth Supported Places (CSP). A Commonwealth Supported Place is a study place in a higher education course where the Australian government contributes to the cost of your education, meaning you pay a reduced student contribution compared to full-fee-paying students.

## Motivation
As higher education costs continue to rise, it can be challenging for students to find affordable postgraduate opportunities. This collection of CSP courses provides an invaluable resource for prospective postgraduate students looking to benefit from government-subsidised education. By gathering key details about various postgraduate programs, this project aims to make it easier for students to find courses that align with their career goals and financial needs.

## What Are Commonwealth Supported Places (CSP)?
Commonwealth Supported Places are available to Australian citizens, permanent residents, and New Zealand citizens for various undergraduate and postgraduate programs. The Australian government subsidises a portion of the tuition fees, significantly reducing the cost of education for eligible students. While the government covers part of the cost, students still need to contribute a portion of the tuition fee, which varies depending on the program and field of education.

## Dataset
The dataset contains the following details for each Commonwealth Supported Postgraduate Course:

1. **Course Name:** The official name of the postgraduate course.
1. **University Name:** The institution offering the course.
1. **State:** State of the university's primary campus.
1. **Duration:** The typical duration of the course, in years or semesters.
1. **Course Description:** A brief description of the course content and objectives.
1. **Updated Date:** The date the course information was last updated.
1. **Link to Course:** A direct link to the course page for further details.
1. **Field of Education, Broad (ASCED2):** My best guess of the course's field of education classification by the ASCED2 (Australian Standard Classification of Education) framework.
1. **Field of Education, Narrow (ASCED4):** My best guess of a more detailed classification of the course's field of education by ASCED4.
1. **Field of Education, Detailed (ASCED6):** My best guess of the most granular classification of the course's field of education by ASCED6.

## Methodology
To gather the data for this project, I used web scraping techniques to collect up-to-date information about Commonwealth Supported Postgraduate Courses from various Australian university websites. The methodology involved the following steps:

- **Identification of Target Websites:** First, I identified key Australian universities offering postgraduate programs with Commonwealth Supported Places.
- **Web Scraping Setup:** I set up a web scraping framework using Python libraries like BeautifulSoup and Scrapy. These tools allowed me to extract relevant data from university course pages.
- **Data Extraction:** The scraping process focused on extracting course names, university details, descriptions, duration, and fields of education classification.
- **Data Cleaning and Structuring:** After extraction, the data was cleaned to remove inconsistencies and structured into a table format that aligns with the required fields.
- **Data Updates:** Regular checks and updates were made to ensure that the information is as current as possible, including the "Updated Date" for each course.

## Caveats
- This list was heavily assisted by generative AI, so please use it with care and confirm details with official sources.
- There is no available information about CSP courses at **Batchelor Institute of Indigenous Tertiary Education**.
- CSPs are available at **University of Divinity** for students only from disadvantaged backgrounds.
- The **University of Melbourne** and **University of Canberra** assign CSP on a subject basis rather than on a course basis. Hence, to calculate costs of a course, you need to add individual subjects.
- **Bond University** is private, not-for-profit, university and hence not eligible for CSP.
- Each university is listed according to the location of their primary campus (some universities operate in multiple states). 

## Structure
The dataset is structured as a table, where each row corresponds to a specific postgraduate course. You can use this table to filter, sort, and explore courses by various fields, universities, or other criteria.

## Usage
This dataset can be used by prospective students, educational institutions, researchers, and anyone interested in understanding the landscape of Commonwealth Supported Postgraduate Courses in Australia.