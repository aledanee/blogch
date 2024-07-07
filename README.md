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

### Core Use Cases

#### Managing Categories
- **Actor:** Blog Owner
- **Description:** The blog owner can create, edit, and delete categories.
- **Steps:**
  1. Log in to the dashboard.
  2. Navigate to the 'Manage Categories' section.
  3. Perform actions such as adding a new category, editing an existing one, or deleting a category.

#### Navigating Posts by Category
- **Actor:** Reader
- **Description:** Readers can view posts filtered by selected categories.
- **Steps:**
  1. Visit the blog homepage.
  2. Select a category from the category list.
  3. View posts associated with the chosen category.

### Advanced Use Cases

#### Viewing a Specific Blog Post
- **Actor:** Reader
- **Description:** Readers can view the details of a specific blog post.
- **Steps:**
  1. Navigate to the blog homepage or a category page.
  2. Click on the title or thumbnail of a post.
  3. View the full content of the post, including multimedia elements like images or videos.

#### Liking a Blog Post
- **Actor:** Reader
- **Description:** Readers can express their appreciation for a post by liking it.
- **Steps:**
  1. While viewing a post, click the 'Like' button.
  2. The system increments the like count and displays the updated count immediately.

#### Editing a Blog Post
- **Actor:** Blog Owner
- **Description:** The blog owner edits an existing blog post to update or correct information.
- **Steps:**
  1. Log into the admin dashboard.
  2. Select the post to edit from a list or by searching.
  3. Update the content, tags, or associated images and save the changes.

#### Deleting a Blog Post
- **Actor:** Blog Owner
- **Description:** The blog owner deletes a blog post that is no longer relevant or needed.
- **Steps:**
  1. Log into the admin dashboard.
  2. Select the post to delete from a list or by searching.
  3. Confirm deletion to remove the post permanently from the blog.

#### Searching for Blog Posts
- **Actor:** Reader
- **Description:** Readers search for blog posts by keywords, tags, or categories.
- **Steps:**
  1. Use the search bar on the homepage or category pages.
  2. Enter the search terms and submit the search.
  3. View the list of posts that match the search criteria.

#### Subscribing to Blog Updates
- **Actor:** Reader
- **Description:** Readers subscribe to receive notifications or emails when new posts are published.
- **Steps:**
  1. Navigate to the subscription area on the blog homepage.
  2. Enter an email address and submit the subscription request.
  3. Receive confirmation of subscription and future updates via email.

#### Comment Moderation
- **Actor:** Blog Owner
- **Description:** The blog owner reviews and moderates comments to maintain quality and prevent spam.
- **Steps:**
  1. Log into the admin dashboard.
  2. Navigate to the comment moderation section.
  3. Approve, delete, or reply to comments as needed.

## Functionality
- **Category Management:** Allows the blog owner to organize posts into categories, enhancing navigational ease and content discoverability.
- **Post Interactions for Readers:** Features like comments and likes to engage readers, alongside category-based navigation.
- **Responsive Design:** Ensures the blog is functional and visually appealing on various devices.
