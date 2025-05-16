Web Data Extractor API

Overview

It is a powerful Web Application that gathers and extracts organized data from hundreds of thousands of web pages. Built by a passionate group of developers led by a freshly graduated Full Stack Developer, the primary functionality of this application employs the power of Regular Expressions (Regex) to find and extract meaningful patterns from raw web content.

Regardless of whether it's extracting contact numbers, formatting credit card numbers, or parsing time format and hashtags, this API makes data elegantly structured, cleaned, and ready to use.


 Features

The API supports extraction of the following data types:

Email Addresses
URLs
Phone Numbers
Credit Card Numbers
Time(both 12-hour and 24-hour formats)
HTML Tags
Hashtags
Currency Amounts


And the output must be anticipated as:
Email Addresses: ['user@example.com', 'firstname.lastname@company.co.uk'] URLs: ['https://www.example.com', 'http://subdomain.example.org/page'] Phone Numbers: ['(123) 456-7890', '123-456-7890', '123.456.7890'] Credit Card Numbers: ['1234 5678 9012 3456', '1234-5678-9012-3456'] Times: ['14:30', '2:30 PM'] HTML Tags: ['
', '
', ''] Hashtags: ['#example', '#ThisIsAHashtag'] Currency Amounts: ['$19.99', '$1,234.56']

Supports multiple phone formats:
(123) 456-7890


123-456-7890


123.456.7890
Supports both spaced and dashed formats:
1234 5678 9012 3456


1234-5678-9012-3456



