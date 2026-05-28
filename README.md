# Inventory Movement Dashboard - Frontend

This is the frontend user interface for the Inventory Movement Dashboard, built with React and Vite. It provides a responsive, single-page application to upload, validate, and visualize stock movement data.

## 🚀 Features

* **Secure File Upload:** Allows users to upload a JSON file containing stock records.
* **Client-Side Validation:** Computes a SHA-256 digest of the uploaded file directly in the browser using the Web Crypto API, sending it to the backend for integrity verification.
* **Interactive Dashboard:** Displays data visualizations only after successful SHA validation.
    * **Pie Chart:** Shows the proportion of total quantity moved (IN vs. OUT).
    * **Time-Series Chart:** Displays a line chart of daily movement quantities, separated by IN and OUT types.
* **Dynamic Filtering:** Users can filter the dataset by a required date range (`from`, `to`) and movement type (`All`, `IN`, `OUT`).
* **Paginated Data Table:** Displays the raw, filtered stock movements (Date/Time, SKU, Movement Type, Quantity) limited to 10 rows per page.

## 🛠️ Tech Stack

* **Framework:** React 18
* **Build Tool:** Vite
* **Charting Library:** Recharts
* **HTTP Client:** Axios

---

## ⚙️ Prerequisites

Before you begin, ensure you have the following installed on your machine:

* **Node.js** (v18 or higher recommended)
* **npm** (comes with Node.js)

---

## 🏃‍♂️ Getting Started

### 1
