# PortSwigger Academy Write-ups

This repository contains all labs write-ups that I solved on [PortSwigger Web Security Academy](https://portswigger.net/web-security).

**Progression: 29/270**

| Categories                             | Lab                                                                                 | Difficulty |
| -------------------------------------- | ----------------------------------------------------------------------------------- | ---------- |
| **SQL injection**                      | SQL injection vulnerability in WHERE clause allowing retrieval of hidden data       | 🟢         |
|                                        | SQL injection vulnerability allowing login bypass                                   | 🟢         |
|                                        | SQL injection attack, querying the database type and version on Oracle              | 🔵         |
|                                        | SQL injection attack, querying the database type and version on MySQL and Microsoft | 🔵         |
|                                        | SQL injection attack, listing the database contents on non-Oracle databases         | 🔵         |
|                                        | SQL injection attack, listing the database contents on Oracle                       | 🔵         |
|                                        | SQL injection UNION attack, determining the number of columns returned by the query | 🔵         |
|                                        | SQL injection UNION attack, finding a column containing text                        | 🔵         |
|                                        | SQL injection UNION attack, retrieving data from other tables                       | 🔵         |
|                                        | SQL injection UNION attack, retrieving multiple values in a single column           | 🔵         |
|                                        | Blind SQL injection with conditional responses                                      | 🔵         |
| **Server-side request forgery (SSRF)** | Basic SSRF against the local server                                                 | 🟢         |
|                                        | Basic SSRF against another back-end system                                          | 🟢         |
| **OS command injection**               | OS command injection, simple case                                                   | 🟢         |
| **Path traversal**                     | File path traversal, simple case                                                    | 🟢         |
| **Access control vulnerabilities**     | Unprotected admin functionality                                                     | 🟢         |
|                                        | Unprotected admin functionality with unpredictable URL                              | 🟢         |
|                                        | User role controlled by request parameter                                           | 🟢         |
|                                        | User ID controlled by request parameter, with unpredictable user IDs                | 🟢         |
|                                        | User ID controlled by request parameter with password disclosure                    | 🟢         |
| **Authentication**                     | Username enumeration via different responses                                        | 🟢         |
|                                        | 2FA simple bypass                                                                   | 🟢         |
|                                        | Username enumeration via subtly different responses                                 | 🔵         |
| **File upload vulnerabilities**        | Remote code execution via web shell upload                                          | 🟢         |
|                                        | Web shell upload via Content-Type restriction bypass                                | 🟢         |
| **API testing**                        | Exploiting an API endpoint using documentation                                      | 🟢         |
|                                        | Exploiting server-side parameter pollution in a query string                        | 🔵         |
|                                        | Finding and exploiting an unused API endpoint                                       | 🔵         |
|                                        | Exploiting a mass assignment vulnerability                                          | 🔵         |
