# Reflection: InventoryHub Full-Stack Project

## Overview
In this project, I developed a full-stack web application using Blazor WebAssembly for the front-end and a .NET Minimal API for the back-end. The goal was to implement seamless integration, debug issues, and optimize performance.

## Role of Microsoft Copilot
Microsoft Copilot played a significant role throughout development:

- Generated API integration code using HttpClient in Blazor
- Suggested fixes for API route mismatches
- Helped resolve CORS issues by configuring middleware
- Assisted in implementing error handling for JSON deserialization
- Helped structure nested JSON responses with category objects
- Provided suggestions for optimizing performance and reducing redundant API calls

## Challenges Faced
- API route mismatch caused 404 errors
- CORS issues blocked communication between frontend and backend
- JSON structure changes initially broke frontend parsing
- Port mismatches caused "Failed to fetch" errors

## How Issues Were Resolved
- Updated API routes to match backend endpoints
- Enabled CORS using AllowAnyOrigin, AllowAnyMethod, and AllowAnyHeader
- Implemented try-catch blocks for safe JSON parsing
- Verified backend endpoints using browser and Postman
- Corrected frontend API URLs with proper ports

## Key Learnings
- Importance of consistent API contracts between frontend and backend
- Handling cross-origin requests in web applications
- Debugging real-world integration issues
- Structuring JSON responses using nested objects
- Using Copilot effectively to speed up development and debugging

## Conclusion
This project improved my understanding of full-stack development and demonstrated how AI tools like Copilot can enhance productivity, reduce errors, and provide efficient solutions.
