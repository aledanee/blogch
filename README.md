
# blogch - Personal Blog System

## Project Overview
"blogch" is a personal blog system designed to publish, manage, and interact with content effectively. It supports functionalities for readers to view posts, like them, and comment, and for the blog owner to manage categories of posts using FastAPI and MySQL.

## Goals
- Enable the blog owner to organize posts into categories for better navigation and reader experience.
- Allow readers to engage with posts through likes, comments, and by navigating different categories.
- Maintain a responsive and intuitive interface.

## Scope
- Blog post and category creation, editing, and deletion by the blog owner.
- Reader interactions including viewing posts, liking them, and commenting.
- Category-based navigation of posts.
- Responsive design for compatibility across various devices.

## Stakeholders
- Blog Owner (Administrator)
- Readers (Users)
- Backend Developer
- Frontend Developer
- Quality Assurance Tester

## Requirements

### Functional Requirements
- Authentication system for the blog owner.
- CRUD operations for blog posts and categories by the blog owner.
- Viewing posts, liking posts, commenting on posts by readers.
- Navigation through categories by readers.

### Non-Functional Requirements
- Usability: Intuitive interface for both readers and the blog owner.
- Performance: Quick response times for all interactions within the blog.
- Security: Effective security protocols to prevent unauthorized management access and ensure data integrity.

## Use Cases

### Managing Categories
- **Actor:** Blog Owner
- **Description:** The blog owner can create, edit, and delete categories.
- **Steps:**
  1. Log in to the dashboard.
  2. Navigate to the 'Manage Categories' section.
  3. Perform actions such as adding a new category, editing an existing one, or deleting a category.

### Navigating Posts by Category
- **Actor:** Reader
- **Description:** Readers can view posts filtered by selected categories.
- **Steps:**
  1. Visit the blog homepage.
  2. Select a category from the category list.
  3. View posts associated with the chosen category.

## Functionality
- **Category Management:** Allows the blog owner to organize posts into categories, enhancing navigational ease and content discoverability.
- **Post Interactions for Readers:** Features like comments and likes to engage readers, alongside category-based navigation.
- **Responsive Design:** Ensures the blog is functional and visually appealing on various devices.

