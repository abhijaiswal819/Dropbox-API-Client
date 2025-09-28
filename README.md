# Dropbox API Java Client

This is a simple Java program that demonstrates how to authenticate with the Dropbox Business API using an **OAuth2 Access Token** and fetch data from the **Team Info API** (`/2/team/get_info`).  

## 🚀 Features
- Connects to Dropbox API using Java `HttpClient`
- Fetches **team/organization information**
- Prints API response in JSON format
- Clean implementation without exposing confidential credentials

---

## 📋 Prerequisites
- Java 11 or higher
- A valid Dropbox Business **Access Token** with the required scopes  
  (e.g., `team_info.read`, `members.read`, `team_data.audit` depending on the endpoint)

---
