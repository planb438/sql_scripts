[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Ubuntu%2022.04%2B-lightgrey)](#)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-MicroK8s%20%7C%20kubeadm-blue)](#)
[![YouTube](https://img.shields.io/badge/YouTube-TechShorts-red)](https://www.youtube.com/@techshorts-p3z)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Adari%20Bain-blue)](https://www.linkedin.com/in/adari-bain-298924152/)

# 🗃️ SQL Scripts Collection

This repository contains a set of **SQL scripts** for working with relational databases such as **MySQL**, **PostgreSQL**, and **SQLite**. These scripts are designed for learning, automation, and real-world use cases like reporting, migrations, and data cleanup.

---

## 📂 What's Included

| File | Description |
|------|-------------|
| `create_tables.sql` | Creates example tables and sets up relationships |
| `insert_data.sql`   | Populates tables with sample data |
| `queries.sql`       | Sample `SELECT`, `JOIN`, and aggregation queries |
| `cleanup.sql`       | Drops tables and resets the schema |
| `migration_v1.sql`  | Example of a versioned database schema migration |

---

## 🧰 Supported Databases

- ✅ MySQL
- ✅ PostgreSQL
- ✅ SQLite (some syntax may vary)

---

## 🚀 Usage

Run scripts using your preferred SQL client or command-line tool:

```bash
# MySQL example
mysql -u your_user -p your_database < create_tables.sql

# PostgreSQL example
psql -U your_user -d your_database -f insert_data.sql
