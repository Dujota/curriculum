---
layout: home
title: SEI Flex
permalink: index.html
description: Listing of course modules and topics.
has_toc: false
---

# Software Engineering Immersive - Flex - Remote
{:.no_toc}

**Course Dates:** 07/25/2023 - 01/27/2024

**Holidays:** 9/2, 11/11, 11/22, 11/23, 11/25, 12/26, 12/27, 12/28, 12/30, 1/13

SEI is divided into four modules, each running for 5-7 weeks. The four modules
are:

| Module | Start Date | End Date |
| [Fundamentals](#1-welcome-intro-to-the-cli) | July 25, 2023 | September 25, 2023 |
| [Node & Express](#10-express-mongo-db)| September 26, 2023 | October 31, 2023 |
| [React](#15-project-2-presentations-react) | November 1, 2023 | December 1, 2023 |
| [Python & Django](#20-python) | December 2, 2023 | January 10, 2024 |
| [Capstone](#26-capstone) | January 10, 2024 | January 27, 2024 |

There are also multiple projects throughout the course, including a capstone
project at the very end, which runs from 01/11 to 01/26

{% for module in site.modules %}
{{ module }}
{% endfor %}
