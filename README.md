# CraftyCommerce
CraftyCommerce is an innovative e-commerce platform dedicated to connecting artisans with customers seeking unique, handcrafted products. Our mission is to empower small-scale artisans by providing a digital marketplace to showcase their creativity and craftsmanship.

## Team Members

- Alex Johnson - Project Manager
- Jamie Smith - Lead Developer
- Sam Taylor - Front-End Developer
- Riley Brown - Back-End Developer
- Casey Lee - UX/UI Designer
## Branch Purpose and Features Developed

### 1. `feature-product-listing`
**Purpose**: This branch was dedicated to developing the product listing functionality, allowing sellers to list their handcrafted products on the platform.

**Features Developed**:
- Functionality to add new products with details like name, description, price, and images.
- Implemented search and filter options for products to enhance user experience.

**Challenges Faced**:
- Integrating the search and filter functionality with the database proved to be challenging due to the diverse range of products and attributes.
- Ensuring that images uploaded by sellers were optimized for performance without compromising quality.

### 2. `feature-shopping-cart`
**Purpose**: This branch focused on implementing the shopping cart functionality, allowing users to add, remove, and modify items in their shopping cart.

**Features Developed**:
- Developed the ability for users to add items to the cart, adjust quantities, and remove items.
- Integrated a real-time update mechanism for the cart’s total price as items are added or removed.

**Challenges Faced**:
- Handling synchronization issues when multiple items were added or removed from the cart simultaneously.
- Optimizing the shopping cart for performance, especially under conditions of high user load.

### 3. `feature-customer-reviews`
**Purpose**: This branch was aimed at developing the customer review functionality, enabling customers to leave feedback on products they purchased.

**Features Developed**:
- Created a review system where customers can rate products and leave written feedback.
- Added a moderation system to filter inappropriate or spammy reviews.

**Challenges Faced**:
- Designing a robust moderation system that could effectively filter out spam and inappropriate content.
- Ensuring that the review system was user-friendly and didn’t discourage genuine feedback.

## Lessons Learned About Using Git in a Team Environment

1. **Branch Management**: Establishing a clear branching strategy (such as feature branches) is crucial for parallel development. It allows multiple team members to work on different features without interfering with each other's progress.

2. **Regular Merges and Updates**: Regularly updating feature branches with changes from the `master` branch (`git pull origin master`) helped to minimize merge conflicts and ensured that new features were always compatible with the latest codebase.

3. **Clear Commit Messages**: Writing descriptive commit messages (e.g., `git commit -m "Added product listing functionality"`) helped the team understand the changes being made and the reasons behind them. This practice improved communication and made it easier to track the project’s progress.

4. **Code Reviews and Pull Requests**: Utilizing pull requests for code reviews before merging changes into the `master` branch fostered collaboration and maintained code quality. It also provided an opportunity for team members to give feedback and suggest improvements.

5. **Conflict Resolution**: Merge conflicts are inevitable in a collaborative environment. The team learned that resolving conflicts early and frequently reduced the risk of more significant issues later in the development process.

6. **Backup and Recovery**: Understanding how to use Git effectively for backup and recovery (e.g., using branches and commit history) was vital for maintaining code integrity and preventing data loss during development.

7. **Continuous Learning**: The team found that continuous learning and adapting to new Git features and best practices were essential for improving workflow and collaboration efficiency.

By following these practices, the team was able to use Git effectively to manage development, collaborate on code, and deliver a robust and well-tested e-commerce platform.
