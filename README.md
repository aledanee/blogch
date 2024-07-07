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

## Project Structure
Below is the structure of the project which organizes the code, templates, and other items:

blogch/
│
├── app/ # Main application package
│ ├── init.py # Initializes Python package
│ ├── main.py # Entry point to the FastAPI app
│ ├── dependencies.py # Dependency-related functions
│ ├── settings.py # Configuration and environment variables
│ │
│ ├── api/ # Web API logic
│ │ ├── init.py
│ │ ├── api.py # Routes and endpoints
│ │ ├── crud.py # CRUD operations for database
│ │ ├── schemas.py # Pydantic models for data validation
│ │ └── security.py # Security operations, e.g., password hashing, token generation
│ │
│ ├── models/ # Database models
│ │ ├── init.py
│ │ ├── models.py # SQLAlchemy models
│ │ └── base.py # Base class for models
│ │
│ ├── db/ # Database related modules
│ │ ├── init.py
│ │ ├── base_class.py # Base class for all models
│ │ ├── session.py # Database session management
│ │ └── init_db.py # Database initialization
│ │
│ └── templates/ # Templates for rendering (if not using a separate frontend)
│ ├── index.html
│ └── post.html
│
├── migrations/ # Database migrations
│ ├── versions/ # Individual migration scripts
│ └── env.py # Migration environment
│
├── tests/ # Test suite
│ ├── init.py
│ ├── test_config.py # Test configurations
│ └── test_main.py # Test cases for your application
│
├── requirements.txt # Project dependencies
└── README.md # Project documentation


## Requirements
Detailed information on project dependencies can be found in `requirements.txt`. It includes all necessary libraries to ensure proper environment setup.

## Functionality
- **Category Management:** Allows the blog owner to organize posts into categories, enhancing navigational ease and content discoverability.
- **Post Interactions for Readers:** Features like comments and likes to engage readers, alongside category-based navigation.
- **Responsive Design:** Ensures the blog is functional and visually appealing on various devices.

## Usage
Instructions on how to run and use the application will be detailed under this section.

## Development
This section will provide guidelines for developers looking to contribute to the project, including setting up their development environment, running tests, and making pull requests.

## Contributing
Interested in contributing? Great! Look at our `CONTRIBUTING.md` for guidelines on how to make effective pull requests and participate in the development process.

## License
Specify the license under which the project is made available.
