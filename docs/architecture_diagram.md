# ClutterClear AI Agent - Architecture Diagram

```text
+--------------------------------------------------+
|               User Captures Screenshot           |
+--------------------------------------------------+
                         |
                         v
+--------------------------------------------------+
|         Screenshot Detection Service             |
|   (MediaStore API / Screenshot Observer)         |
+--------------------------------------------------+
                         |
                         v
+--------------------------------------------------+
|               OCR Text Extraction                |
|                  (ML Kit OCR)                    |
+--------------------------------------------------+
                         |
                         v
+--------------------------------------------------+
|           AI Context Analysis Engine             |
|     - Detect screenshot intent                   |
|     - Extract semantic meaning                   |
|     - Understand content category                |
+--------------------------------------------------+
                         |
                         v
+--------------------------------------------------+
|        Microsoft Foundry Reasoning Agent         |
|                                                  |
|  - Multi-step screenshot reasoning               |
|  - Importance detection                          |
|  - Smart categorization                          |
|  - Cleanup recommendation                        |
|  - Folder prioritization                         |
+--------------------------------------------------+
                         |
                         v
+--------------------------------------------------+
|           Smart Categorization System            |
|                                                  |
|  Education | Payments | Social | Documents       |
|  Sports    | AI       | Travel | Miscellaneous   |
+--------------------------------------------------+
                         |
                         v
+--------------------------------------------------+
|           Screenshot Organization Layer          |
|                                                  |
|  - Auto folder placement                         |
|  - Smart filtering                               |
|  - Multi-select cleanup                          |
|  - User-created folders                          |
+--------------------------------------------------+
                         |
                         v
+--------------------------------------------------+
|             Interactive User Interface           |
|                                                  |
|  - Swipe & zoom preview                          |
|  - Fullscreen viewer                             |
|  - Smart cleanup actions                         |
|  - AI-powered screenshot management              |
+--------------------------------------------------+
```

---

## Core Technologies

- Android (Java/Kotlin)
- ML Kit OCR
- Microsoft Foundry Agent Service
- WorkManager
- MediaStore API
- Custom AI Categorization Logic

---

## AI Agent Responsibilities

The ClutterClear AI Agent performs intelligent reasoning on screenshots by analyzing textual and visual context, understanding screenshot intent, categorizing content, and assisting users with smart organization and cleanup workflows.
