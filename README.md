# KSInsights

📊 A weekly-updated dataset of **Kickstarter** projects in the **Technology** and **Design** categories (live & upcoming).  
🛠️ Built for creators, product developers, and researchers who want to track crowdfunding trends and discover market opportunities.

---

## 🔍 What is KSInsights?

KSInsights is an open-source project that automatically collects and publishes data from Kickstarter's **Technology** and **Design** categories. It focuses on **live** and **upcoming** projects, updated weekly.

Whether you're launching your first crowdfunding campaign or researching product ideas, this dataset gives you timely insights into what's trending, who's launching, and what people are backing.

---

## 📁 What's in the Dataset?

Each weekly dataset contains:

- `collected_at`
- `backers_count`
- `blurb`
- `category_id`
- `category_name`
- `category_parent_id`
- `category_parent_name`
- `category_url`
- `converted_pledged_amount`
- `country`
- `created_at`
- `creator_id`
- `creator_name`
- `creator_url`
- `currency`
- `deadline`
- `fx_rate`
- `goal`
- `id`
- `launched_at`
- `location_country`
- `location_id`
- `location_name`
- `location_state`
- `location_type`
- `name`
- `percent_funded`
- `pledged`
- `profile_blurb`
- `profile_id`
- `profile_name`
- `profile_project_id`
- `profile_state`
- `profile_state_changed_at`
- `project_url`
- `spotlight`
- `staff_pick`
- `state`
- `state_changed_at`
- `static_usd_rate`
- `usd_exchange_rate`
- `usd_pledged`
- `usd_type`

Datasets are stored in CSV format under the `/data/weekly/technology & design` folder structure.

---

## 🧠 Who is this for?

- 🚀 **Kickstarter creators**: See what others are launching, and identify gaps or oversaturation.
- 📈 **Product researchers**: Track trends in product design and tech innovation.
- 📰 **Journalists & analysts**: Use structured data to support crowdfunding coverage and reports.
- 🤖 **Data scientists**: Build models to predict campaign success or analyze launch patterns.

---

## 🔄 How is the data collected?

We use a Python-based scraper that queries Kickstarter's public project listings each week. The scraping process respects Kickstarter’s robots.txt and is designed for ethical data use.

---

## 📅 Update Frequency

- **Weekly**, every Friday (UTC)
- Each batch is timestamped and versioned.

---

## 🌐 Related Resources
🌍 [KS Insights](https://ksinsights.com)

## 📬 Contact
Have questions, suggestions, or need custom dataset?
📧 [domingo@ksinsights.com](mailto:domingo@ksinsights.com)

---

## MIT License

Copyright (c) 2025 KS Insights

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

