# Quick BI

- Last Update: 2021-01-20
- Provider: [Alibaba Cloud (International)](https://www.alibabacloud.com)
- [Official Documentation](https://www.alibabacloud.com/help/product/30343.htm)

## What is it?

In short, Quick BI is a tool for doing data analysis. It allows data analysts to import data from a variety of sources, then build excel-style worksheets and data dashboards for manipulating and displaying the imported data. 

## Compare to

- Azure PowerBI

## The Bottom Line

Worth considering if you have 50 to a few hundred users who need to perform analysis and build display boards over large, dispersed data sets, but it is *expensive*. Quick BI would get you the most bang for your buck if you have target users in China, where other BI tools may not work as well. 

If you are a startup, look to low-cost open source tools first. 

## Pricing

Since Alibaba Cloud maintains two portals (alibabacloud.com for non-Chinese users, aliyun.com for Chinese users) pricing differs across the two sites.

### Pricing on alibabacloud.com

Payment methods: Subscription only (durations of **one year** or **two years** supported)
Versions: Pro, Enterprise Standard

Pricing also varies and *number of users*, but is (currently) the same across different regions. The table below lists prices for 2021 (last updated on 2021-01-20):

| Region        | Version      | Subscription Length | Number of Users | Price (USD) |
| ------------- | ------------ | ------------------- | --------------- | ----------- |
| Singapore     | Pro          | One Year            | 50              | 5,800       |
| Singapore     | Pro          | One Year            | 100             | 11,500      | 
| Singapore     | Pro          | One Year            | 150             | 17,000      |
| Singapore     | Pro          | One Year            | 200             | 22,000      |
| Singapore     | Pro          | Two Years           | 50              | 11,600      |
| Singapore     | Pro          | Two Years           | 100             | 23,000      | 
| Singapore     | Pro          | Two Years           | 150             | 34,000      |
| Singapore     | Pro          | Two Years           | 200             | 44,000      |
| Singapore     | Enterprise   | One Year            | 100             | 32,000      |
| Singapore     | Enterprise   | One Year            | 200             | 51,000      | 
| Singapore     | Enterprise   | One Year            | 300             | 68,000      |
| Singapore     | Enterprise   | Two Years           | 100             | 64,000      |
| Singapore     | Enterprise   | Two Years           | 200             | 102,000     | 
| Singapore     | Enterprise   | Two Years           | 300             | 136,000     |

### Pricing on aliyun.com

Payment methods: Subscription only (durations of **one year** or **two years** supported)
Versions: Basic (标准版), Advanced (高级版), and Professional (专业版).

| Version      | Number of Users | Subscription Length   | Price (CNY) |
| ------------ | --------------- | --------------------- | ----------- |
| Basic        | 1               | One Year              | 558         |
| Basic        | 2               | One Year              | 996         |
| Advanced     | 20              | One Year              | 18,000      |
| Advanced     | 20              | Two Years             | 36,000      |
| Advanced     | 50              | One Year              | 44,950      |
| Advanced     | 50              | Two Years             | 89,900      |
| Advanced     | 100             | One Year              | 89,000      |
| Advanced     | 100             | Two Years             | 179,800     |
| Advanced     | 150             | One Year              | 134,850     |
| Advanced     | 150             | Two Years             | 269,700     |
| Advanced     | 200             | One Year              | 179,800     |
| Advanced     | 200             | Two Years             | 359,600     |
| Professional | 50             | One Year               | 120,000     |
| Professional | 50             | Two Years              | 240,000     |
| Professional | 100            | One Year               | 200,000     |
| Professional | 100            | Two Years              | 400,000     |
| Professional | 200            | One Year               | 350,000     |
| Professional | 200            | Two Years              | 700,000     |
| Professional | 300            | One Year               | 450,000     |
| Professional | 300            | Two Years              | 900,000     |

## Supported Regions

Alibaba Cloud actually splits its services across two domains:

- https://www.alibabacloud.com for users outside Mainland China
- https://www.aliyun.com for users inside Mainland China

In many cases, the services available on each site are the same, but there can be differences in features or availability, as is the case with Quick BI. 

For Quick BI, the supported regions differ between these two sites:

### aliyun.com (Chinese Users)

Regions are non-selectable. Navigating to the Quick BI interface from the aliyun.com web console takes you directly into Quick BI, without the need to first select a region as on alibabacloud.com. 

### alibabacloud.com (non-Chinese Users)

- Singapore
- Hong Kong
- Malaysia (Kuala Lumpur)
- Germany (Frankfurt)

## Important Terms

- Data Source: this is where Quick BI will pull its data from (say, a MySQL database)
- Dataset: A subset of data (say, a table) from the Data Source
- Workbook: Essentially an excel sheet where you can perform analysis on data pulled from a Dataset (**this feature is only available in Quick BI's Pro and Enterprise versions**)
- Dashboard: A tiled interface for displaying multiple charts
- BI Portal: A collection of Dashboards

Workbooks, Dashboards, and BI Portals can all be published either for Internal users or via publicly accessible URLs. 

## FAQ 

### Can you replace one Quick BI data source with another?

Yes, starting from version 3.7.4 you can replace existing data sources with new ones. Existing datasets and dashboards should still work (assuming they datasets referenced by Quick BI exist in the new data source).

### Can I unpublish/republish a Dashboard?

Yes, published dashboards can be unpublished, starting from Quick BI version 3.6.3

### What happens if I don't pay my bill?

Data and associated Workbooks, Portals, and Worksheets will be kept for 7 days. After 7 days, everything is deleted. During the 7 day grace period, Quick BI can be renewed again with no data loss. 